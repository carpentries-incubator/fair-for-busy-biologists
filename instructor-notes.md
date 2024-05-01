---
title: 'Instructor Notes'
---

## General remarks

This course is an adopted, shorter version of our [FAIR in (bio) practice](https://carpentries-incubator.github.io/fair-bio-practice/) course. 

The original course "works" and the exercises have been valued as good or excellent, but the uptake is low cause it is a long course.
This is a more trimmed version, but, you should check the full one for more in depth information, to check other exercises or to include a new episode.

The original course was designed during COVID-19 pandemic for an online delivery.
We heavily depend on the online setting, ie. video call with breakout rooms, the ether pads for collaborative writing. 
We are not sure if this course in its current form would work in real-world workshop. For one there is will an significant overhead in starting group activities (people need to move around etc).
Unlike speaking up, the pads allows multiple student provide answers and suggestion in the same time. 

We delivered the training as 2 x 3:15 (3 and quoter) hours modules.  

The `instructors` folders contains the slide decks for the delivery, which works better than scrolling through carpentry website.

There are also set of word documents with content of the etherpad with the exercises for the student. They are bundled into "days" and should be copied into pads before the workshop. 

We tried to order the episodes in logical sequence, but they can be shuffled around.

Pads and main text contain clues about timings for excercise and teaching,
as measured during our deliveries. 


### Breakout rooms

Generally, students asked for more time in the group activities in their feedback forms. 
We typically give 5 minutes for the breakout rooms. While it may feel too short for an "active" group, it feels long for not so "engaged" one. So it is a balance. 
Also, we make sure to discuss the groups' answers so more time in the rooms will extend the episodes duration.

The groups should be about 5-7 participants if possible, that should guarantee sufficient level of engaged students in each group (despite our effort some students remain muted all the workshop).
We used zoom for the delivery and could see in the breakout room dialog who has muted mic and camera off and active speakers.
We tried to move participants between groups if one turned too particularly quiet.
We also send broadcast messages encouraging switching mic etc.

### Etherpads

In our experience, students are more inclined to write down their answers, comments and suggestions than speaking up. So the "discussion" challenges are moved into the pad and we ask to write answers commenting on them.

For the True/False quizzes, selecting correct answers we typically start talking over the exercise when we notice than first students are finishing the given exercise. 
It makes the course more dynamic, while we expect our audience accustomed to multitasking such as listening while completing a test.

The quiz like test (true/false, agree, select) are an excuse to comment on the answers. Always if there are some wrong answers, but, also to stress out the most important aspects of the topic.

For the end of episode quiz, we tend to ask students to complete them during the break and after the break comment only on "wrong" answers.

## Specifics for each episode

### 0. Welcome

You can start breakout rooms so students can introduce themselves in the groups.

### 1. Introduction to Open Science

When presenting Open Access explain what other "benefits" it brought with it (apart from costs free access). For example, the time save in trips to libraries or asking inter-libraries loans. 
That should act as an example for the 


Exercise 1. Personal benefits of being “open”

Answers will tend to cluster, you can comment on that. 

We talk about the typically overlooked: 
**"distinguish yourself from the crowd"**, 
as in the current "transition" period having those skills can still make a difference as all job/grants/fellowship competitors would have typically have good academic record. Open practices can be this one extra point.

Exercise 2. Barriers

Check IP epiosde in the big course, you may need it to explain the IP concerns

### Being FAIR

Exercise 1. Impossible ...

We give some teams a) the Impossible protocol and some b) the Imposible Average.
Those two work the best. 
We said that it is going to be a race who can get the answers first.
We warn there is no time to read the full manuscript, nor it is how we "typically look for data and protocols".

Sometimes there are answers to 1a. For the average in 5-7 minutes it is rather unlikely. 
We then explain what was the problem with 1a and demonstrate the problem with 1b. 
Show the tables with meaningless headers, say how to get the right column.
Then copy from from pdf to excel the table to show hot it gets scrambled.

That scrambling depends in what program the pdf was oppended. We recommend firefox or bing as they usually do not copy nicely (Acrobat does much better job). Foreign locales also can mess up with copying.

Exercise 2. FAIR Example

Typically some answers for I or R end up in A.

You should do quick demo of the zenodo record and highlight the most important part (or point to them using the students answers), Visits and download counters are good candidates


### 2. Intro to metadata


Exercise 1. What to include

Start by typing the title and the purpose.
you can ask people to think first of the C. elegans image and what should be added there, so start with domain specific ie microscopy, then go general.
You need to add the crucial metadata elements if student did not think about them, for example genotype, tissue type , generally sample description, some experimental conditions


### 3. (Meta)data in Excel

Show what happens when saved as text (there are also merged cells which messed up row, date change, not only lost of color).


### 4. Files organisation

This notepad must be reformatted online before the class. The file/directory names should in mono-space so they align nicely. 
That is being lost during copying from word.

Exercise 1.

The aim is to show how sorting helps finding info unless the naming convention messes up with the sorting.

Exercise 4: Typical folder organizations

The webpage contains our answer to this exercise. The wet projects typically do not get good answers.

### 5. Reusable analysis

The notebook and data files are on [GitHub](https://github.com/BioRDM/fair-jupyter)

We just start jupyter from the network directory on the server and pass the link to students. We asked them first to make a copy of the notebook (the notebook is readonly), that creates some race condition but after a while student have their own copy.

More fancy setup is possible but that was good enough.

That is code-along episode with instructor performing the tasks together with the students.

Before the exercises the instructor should walk through the notebook elements and explain why it is good fot the analysis.

In case the group contains advanced users, ask them to illustrate all variables on the graphic. R offers much more than just multipane graphic, a novel visualisations are possible.


### 6. Public repositories

Instructor should click through the appropriate repository records when discussing the students answers.

Exercise 2: Dataset discovery
- after student assessment try, clicking into keyword
that gives nothing, comment on it.

The search for "neuromuscular junction", if you scroll down you will find exotic hits like

*Surveys of Forest Birds on Puerto Rico, 2015*

Exercise 3: Domain specific repositories.

You may try to assign domain to room and let the students choose room for a group activity.
Or you ask students to keep typing their answers working on their own.

At some instructor should demonstrate some of the features of all the repos which are being evaluated, so the other students also see them. Either using the students answer of showing one of the instructor "favourite" feature of each repo.

Exercise 4: Finding a repository

When discussing answers show how FAIR sharing fails for omics type with too many hits and why the curated lists from funders and journals are good place to start.


