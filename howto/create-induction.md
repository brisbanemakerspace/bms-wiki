---
title: How to create an induction
description: How to create an induction in moodle
published: true
date: 2024-11-11T00:48:12.031Z
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
2. Update the "General" course settings like in the screenshot below. Fill in the two course name fields, select the correct category and **make sure the course end date is NOT ENABLED**. Please use the format "TOOL_NAME Induction" for the name and description.

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
6. If a member has to watch a video or read the content in the "**Text and media area**", you should explicitly write this. A good example is below.
> Please watch the video below and then continue to the quiz.

7. To embed a YouTube video (note: all BMS produced videos should be uploaded to our YouTube account) tap the URL icon pictued below. Then enter the URL into "Enter a URL" and tap "Create link" to save it. Once you save this topic and go back to the course view (next step), you'll see the link turn into the proper embeded YouTube video. Feel free to add multiple videos to a topic, but put them in separate "**Text and media area**" resources.
![moodle9.png](/howto/moodle/moodle12.png =600x)

8. Once you've finished adding content to all of your topics, don't forget to save your course. In fact, you should do this everytime you make a major change so you don't lose any work.
![moodle9.png](/howto/moodle/moodle11.png =600x)

## 4. Start adding the course quizzes
All BMS inductions should have quizzes in order to check someone has actually completed the content. Question phrasing is a whole topic by itself, but try to follow these guidelines:
- Don't use "gotcha" questions based on phrasing or exact numbers - unless that phrasing/precision is critical to safety or understanding. e.g. both "lense focal point" and "lens focus point" or "pi is 3.142" and "pi is 3.14" are correct answers - don't mark one as incorrect.
- Use a mixture of multiple choice, true/false and other types of questions to break things up.
- Stick to 10 quiz questions - if you need to use more, break up the module into smaller topics.
- The aim of the quiz is to check if they (a) absorbed most of the content and (b) understand most of the content. No-one is perfect and you shouldn't expect anyone to always get 100%.

This guide is incomplete, so we recommend watching this tutorial until there's more information here: https://www.youtube.com/watch?v=7lm-_8-UOFg

### Quiz Marking/Completion Settings
As above, the aim of a quiz is to check if they (a) absorbed most of the content and (b) understand most of the content. No-one is perfect and you shouldn't expect anyone to always get 100%. You should generally leave all the default settings alone unless someone or an instruction on this wiki page has instructed you to change it.

Configure the completion setting as follows:
- set the passing mark to 80-90%
- allow unlimited attempts/retries
- don't set a time limit

### Attestation / Agreements
An "attestation" is an agreement that must be agreed to, to pass an induction.

If necessary, this should be included in the final topic with a quiz. This might be something like "*I agree to never leave the laser cutter running while stepping outside the inclusion zone or I will have my laser cutter access removed*". It should only include *tool specific* agreements, not general things like "*I will operate this tool safely*". To create one of these, just use a multiple choice quiz question, mark it as mandatory, and only add a single answer "yes I agree" or similar.