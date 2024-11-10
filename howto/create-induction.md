---
title: How to create an induction
description: How to create an induction in moodle
published: true
date: 2024-11-10T23:58:02.386Z
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

1. Create a new course by tapping the correct link below (or right click and open in new tab):
	- [Non Working Group Induction](https://learn.brisbanemaker.space/course/edit.php)
  	- [Digifab Induction](https://learn.brisbanemaker.space/course/edit.php?category=2)
  	- [Woodshop Induction](https://learn.brisbanemaker.space/course/edit.php?category=3)
    - Otherwise [tap here](https://learn.brisbanemaker.space/course/index.php), select the correct category, then under "More" select "Add a new course".
    - If the correct category doesn't exist yet (such as for a recently formed working group) please ask in the **#safety-and-inductions** discord channel. *Note to admins: create a new category [here](https://learn.brisbanemaker.space/course/editcategory.php?parent=0).*
2. Update the "General" course settings like in the screenshot below. Fill in the two course name fields, select the correct category and **make sure the course end date is NOT ENABLED**. Please use the format "TOOL_NAME ![moodle7.png](/howto/moodle/moodle7.png)Induction" for the name and description.

	*Note to admins: the "Course ID number" field is how Member Matters synchronises course completion data. Copy the value from the manage interlock / door page.*
![moodle1.png](/howto/moodle/moodle1.png =600x)
3. Scroll down and add a short description and a cover image using this [canva template](https://www.canva.com/brand/brand-templates/DAGWHw5Hhgw). Include an indicated time to complete. A good example is below.

> This laser cutter induction will teach you the basics of safely using our laser cutter. This induction will take around 40-60 minutes.

![moodle2.png](/howto/moodle/moodle2.png =600x)
4. Scroll down and tap "Save and display" to continue.
![moodle3.png](/howto/moodle/moodle3.png =600x)

## 3. Start adding the course content
Now that we've created the course, we need to add the content! All courses need to be signed off by the head maker to check for consistency before it can go live - but feel free to test it out on a few people for feedback.

1. Start by creating a list of all topics you want included in your course. Courses should be split up into sections that take no longer than 10 minutes each where possible. Aim to have any written or video content broken up into approximately 5 minute sections followed by a short quiz to check understanding.
2. Courses should be split up into sections that take no longer than about 10 minutes each where possible. Aim to have any written or video content broken up into approximately 5 minute sections followed by a short quiz to check understanding.
3. After following the above steps your course should already be open, but if you've lost it - you can find a list of all courses [here](https://learn.brisbanemaker.space/course/management.php).
> Make sure you have turned on edit mode in the top right hand corner or you won't be able to make changes.
{.is-warning}

4. You may have a few empty topics by default, feel free to edit these, or delete them all and start fresh. Once you've got the list of topics you want to include in your course, tap "Add an activity or resource" to start adding content. It's a good idea to put a short introduction about what this course will cover inside a "**Text and media area**" resource under the very first topic.
![moodle7.png](/howto/moodle/moodle7.png =600x)
5. Once you've tapped "Add an activity or resource" under a topic, you're presented with a few options. We recommend using a "**Text and media area**" followed by a "**Quiz**" for each topic in your induction course. You can embed a video (either external or one you filmed and uploaded to the BMS YouTube account) or put text and images directly into it. For topics with lots of content, you should use a "**Page**" resource instead of a "**Text and media area**",
![moodle7.png](/howto/moodle/moodle8.png =600x)
> If you're a moodle expert and see something missing that you want to use, drop a message in the **#safety-and-inductions** channel on Discord. We've disabled most of them by default to make it less confusing.
{.is-info}
6. 

Notes:
* Any "attestations" (ie agreements they agree to) should also be included in a final quiz section at the end. This might be something like "I agree to never leave the laser cutter running while stepping outside the inclusion zone or I will have my laser cutter access removed.". It should only include *tool specific* attestations, not general things like "I will operate this tool safely".