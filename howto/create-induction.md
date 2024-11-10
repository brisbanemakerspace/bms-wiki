---
title: How to create an induction
description: How to create an induction in moodle
published: true
date: 2024-11-10T21:23:11.263Z
tags: 
editor: markdown
dateCreated: 2024-06-22T23:23:49.017Z
---

# How to create an induction in BMS Learn (Moodle)
BMS Learn is our inductions platform - which is just the name of our Moodle instance. All of our tools that carry reasonable levels of risk require induction. When setting up a new tool that's been acquired, an induction is required before members can use it. Follow the guide below to create a new tool in moodle so that members can learn how to use it.

> You can find a list of all Moodle courses [here](https://learn.brisbanemaker.space/course/).
{.is-info}


## 1. Get the right permissions
Before you can do anything in this guide, you need the right permissions. We use single sign on which means you already have an account, just [tap here](https://learn.brisbanemaker.space) to login using the member portal.

***After you've logged in at least once***, please reach out to someone on the infrastructure team or committee to adjust your permissions. We'll need to assign a role that allows you to create and edit Moodle courses. *Note for admins: that page is [right here](https://learn.brisbanemaker.space/admin/roles/assign.php?contextid=1&roleid=2).*

## 2. Create a new course
Each induction is called a course in Moodle. To do create a new one, follow the steps below.

1. [Tap here](https://learn.brisbanemaker.space/course/edit.php) to open the new course form.
2. Update the "General" course settings like in the screenshot below. Fill in the two course name fields, select the correct category and **make sure the course end date is NOT ENABLED**. Please use the format "TOOL_NAME Induction" for the name and description.
![moodle1.png](/howto/moodle/moodle1.png =x600)
3. Scroll down and add a short description and image of the tool (you can just copy these from the wiki page).
![moodle2.png](/howto/moodle/moodle2.png =x600)
4. Scroll down and tap "Save and display" to continue.
![moodle3.png](/howto/moodle/moodle3.png =x600)

## 3. Hide announcements
By default, Moodle shows an announcements category in the course. We don't use this so let's hide it.

1. After creating/opening the new course, click on "Announcements".
![moodle4.png](/howto/moodle/moodle4.png =x600)
2. Open the settings tab, scroll down to the "Common module settings" and expand it. Now change "Availability" to "Hide on course page".
![moodle5.png](/howto/moodle/moodle5.png =x600)
3. Make sure to save your changes.
![moodle6.png](/howto/moodle/moodle6.png =x600)

## 4. Start adding the course content
Now that we've created the course, we need to add the content! All courses need to be signed off by the head maker to check for consistency before it can go live - but feel free to test it out on a few people for feedback.

1. Open up the course you just created. You can find a list of all courses [here](https://learn.brisbanemaker.space/course/management.php).
2. This section is coming soon! For now, we recommend searching YouTube for some tutorials / pointers - perhaps something from the list below:
		1. A very short intro ([link here](https://www.youtube.com/watch?v=j3US7x4yqkw))
  	2. A long-ish playlist, feel free to watch all or skip some videos. ([link here](https://www.youtube.com/watch?v=qN-2AOLMRGc&list=PLnEMTyuGwIbHMN0LgepAQVOoz2lST6Y8x))

Notes:
* Courses should be split up into sections that take no longer than about 10 minutes each where possible. Aim to have any written or video content broken up into approximately 5 minute sections followed by a short quiz to check understanding.
* Any "attestations" (ie agreements they agree to) should also be included in a final quiz section at the end. This might be something like "I agree to never leave the laser cutter running while stepping outside the inclusion zone or I will have my laser cutter access removed.". It should only include *tool specific* attestations, not general things like "I will operate this tool safely".