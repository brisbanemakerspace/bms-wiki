---
title: Discourse (Member Forum)
description: Find out how our discourse (member forum) instance works, how to update it and add plugins etc.
published: true
date: 2023-10-26T06:45:32.959Z
tags: 
editor: markdown
dateCreated: 2023-10-26T06:44:02.174Z
---

# Discourse Documentation
Discourse is the software that runs our member forum available at https://forum.brisbanemaker.space.

It runs on serv01 in a docker container provided by Bitnami and managed by caprover. The bitname docker image is (here)[https://docs.bitnami.com/aws/apps/discourse/].

**Setup By:** Jaimyn Mayer (@jabelone)
**Maintained By:** Jaimyn Mayer (@jabelone)

# Updates
You can follow the Bitnami guide here: https://docs.bitnami.com/aws/apps/discourse/administration/upgrade/

It has also been copied below for future reference if the link changes etc.

Create a database backup of the running application with the following command:
```
pg_dump -U postgres bitnami_discourse > backup.sql
```

Create a tarball with the uploaded files of the running application, which are located in the public/uploads directory:
```
tar -czvf uploads.tar.gz /bitnami/discourse/public/uploads
```

Copy both backups to the server hosting the new version.

On the new server, stop all servers and start only PostgreSQL and Redis:

```
/opt/bitnami/ctlscript.sh stop
/opt/bitnami/ctlscript.sh start postgresql
/opt/bitnami/ctlscript.sh start redis
```

Remove the previous database:
```
/opt/bitnami/postgresql/bin/psql -U postgres -c "CREATE DATABASE bitnami_discourse; GRANT ALL PRIVILEGES ON DATABASE bitnami_discourse TO bn_discourse;"
/opt/bitnami/postgresql/bin/psql -U postgres -d bitnami_discourse -c "CREATE EXTENSION hstore; CREATE EXTENSION pg_trgm;"
```

Restore the new database:
```
psql -U postgres bitnami_discourse < backup.sql
```

Navigate to the Discourse installation directory and migrate the database:
```
cd /opt/bitnami/discourse
RAILS_ENV=production bundle exec rake db:migrate
```
Restore the uploaded files in the new server:

```
tar -xzvf uploads.tar.gz -C /
```

Restart all servers:
```
/opt/bitnami/ctlscript.sh start
```

# Installing Plugins
You can follow the Bitnami guide here: https://docs.bitnami.com/aws/apps/discourse/configuration/install-plugins/

It has also been copied below for future reference if the link changes etc.

You might want to extend the functionality of Discourse by installing a plugin. If you want to do this, you must get the repository URL for the plugin (where PLUGIN_REPO_URL is the URL to the repository of the plugin you want to install, like: https://github.com/discourse/discourse-akismet):

Follow these steps below to install a new plugin:
1. SSH into the discourse docker container on serv01.
	Figure out which container it is: `docker ps | grep discourse`
  SSH into it: `docker exec -it srv-captain--bms-forum.XXXXX /bin/bash`

2. Navigate to the Discourse installation directory:
		`cd /opt/bitnami/discourse`

3. Next, install the plugin:
		`RAILS_ENV=production bundle exec rake plugin:install repo=<PLUGIN_REPO_URL>`

4. Finally, precompile new assets to be used by the plugin:
		`RAILS_ENV=production bundle exec rake assets:precompile`