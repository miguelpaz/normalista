# normalista
![Image of Normalista teachers](http://www.memoriasdelsigloxx.cl/601/articles-54181_imagen.jpg)
A Jekyll course template for teachers who like to write markdown, host contents in Github pages and don´t want to worry about servers.
This is a work in progress. For now it just includes research documentation. 

Index
-----------

* [About](#about)
* [Goals](#goals)
* [Users](#users)
* [Layouts](#layouts)
* [Contents](#contents)
* [Type of lesson materials](#type-of-lesson-materials)
* [Use normalista](#use-normalista)
* [Inspiration and acknowledgements](#inspiration-and-acknowledgements)
* [Contributors](#constributors)



About
-----------

**normalista** is a [Jekyll](https://jekyllrb.com/) course template for those who teach, are comfortable writing [Markdown](http://whatismarkdown.com/) and are not very interested in setting up databases or maintaining web servers, but rather prefer to host Course materials in Github and present it all in a website. 

Given the fact that course materials do not require publishing a lot of posts constantly or need to call contents from a database, using [Jekyll with Github Pages](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/), instead of more complex platforms, seems like a great fit for teachers like me and you. 

Plus its free and open source👌🏽.

FYI: This project is called normalista as an homage to the **best teachers** I ever had in Chile who were [Normalista](https://en.wikipedia.org/wiki/Normal_school) teachers. They set the bar high, like the teachers [from the photo](http://www.memoriasdelsigloxx.cl/601/w3-article-54181.html). 

### Why Jekyll
 
- Allows you to write Markdown or [Textile](https://txstyle.org/)
- Comes with a templating engine called [Liquid](https://shopify.github.io/liquid/) and HTML & CSS with a logical [structure](http://yeswejekyll.com/).  
- Generates pretty [nice looking](http://jekyllthemes.org/) static websites with “categories, pages, posts, and custom layouts”.

### Why Github and Github pages
 
If you teach anything that includes code (in my case Data and Journalism) and collaborative work, Github is the place to be.
- You can create your course as an [Organization](https://help.github.com/articles/about-organizations/), like this [Advanced JS course](https://github.com/advanced-js) example. 
- Students can [Clone](https://help.github.com/articles/cloning-a-repository/) (copy in your computer) or [Fork](https://help.github.com/articles/about-forks/) (create a copy online in Github) the course and assignments. When they are done with an assignment in their repository, they can make a [Pull Request](https://help.github.com/articles/using-pull-requests/) to your course repository (via Github tell you they made changes so you can review the assignment, approve it or ask for modifications).
- Reuse course materials to create other courses.
- Keep track of changes and invite contributors.
- You can request Github for free education accounts for private repositories.
- Github pages allows you to create and host your course website and plays well with Jekyll.

Goals
-----------
* To learn by doing, store my Course materials and offer them to students in one place 
* To save time by reusing normalista in many courses
* To provide a open source simple Jekyll template for dear colleagues like you 👐🏽


Users
-----------
**Teachers** who 

- Like tinkering and learning while teaching 
- Want to keep course materials organized in one place 
- Want to offer Students the course materials in a clean website that works well in mobile  
- Want to use normalista for more than one course (and even improve it 🤘🏽)
- Want to be more efficient with their time and reduce email/slack/sms/etc load

**Students** who

- Deal with lots of class materials organized and stored in various formats (Google Docs, Slack, Dropbox, Email, etc)
- Want to have a one stop shop for (most of) the Course materials
- Have to learn about Github, Jekyll, Markdown, HTML&CSS, Javascript and more

**Organizations** which

- May be looking for Jekyll templates for their course materials, teachers and students

Layouts
-----------
- Home: Landing page with summary of everything. A course has a name or title, a clear call to action blurb or subheadline, a description, a lesson plan and other things you can see in **Contents**
- Course description and lesson plan (class by class)
- Class (step by step)
- Activities or assignments and deadlines
- Readings and deadlines
- Instructor/s: Not sure if it needs its own page but when there are one instructor plus adjuncts or coaches or two or more instructors it might be worthwhile 
- More resources: tutorials and any other materials that might be worth including if students want to dive deeper. This could be served from a spreadsheet as a table (datatables, for example) with sorting, filtering, search, or tags or categories (example: offline first, javascript, etc) or may be other useful way to show

Contents
-----------  
A Course Syllabus when it includes everything (sometimes it may not include everything listed) has:
- Course name or title (sometimes has a code like JOUR20162)
- Duration (5 weeks), period, dates and time (Mondays, 9:00 am to 1:00 pm, from July X to August X), place (Room 301, 3rd floor, School of X, address), sometimes also includes requirements (need a computer, have done X course before)
- Course Description 
- Course Learning Objectives
- Instructor
- Office hours and preferred communication channels
- Assignments, Readings & Due Dates
- Grading Rubric
- Assignment Values
- Plagiarism and Copyright
- Code of conduct and diversity statement
- Lesson plan class by class (or week-by-week)

Type of lesson materials
---------------
- Presentations: keynotes, pptx, google slides, speackerdeck, revelas slides, explain, show and lead the class subjects and activities.
- Tutorials: text documents that include descriptive images and links mostly that show how to learn something step by step. This can be used by the teacher or the student can read and follow up individually. Great tutorials include self descriptive names that can be understood right away by the non initiated or less abstract thinker. If you use `foo bar` type of namings, many students will stop right there and get blocked. Be as obvious as you can and if your mom understands the names you are ok. Comparisons, analogies and every day examples kick ass. 
- How to’s: Short and sweet text documents that include descriptive images and links mostly (video tutorials work too). They teach to do one thing well and easy. Example: How to create a Carto map without geodata. 
- Activities and exercises: There are many types of activities that we can draft. From very complex ones to very simple ones. However, the goal is to outline simple and replicable templates for class and workshop exercises that can help us save time when  preparing classes as well as lead us to plan activities that cover all the bases (what, how, why, when, with what, how to follow up after). 
All activities **must explain what you will do, why you will do it (what’s in it for you), use real life data and should build from the previous lesson (so a Student can test what they learned before in a new activity)**.

Example from DataBasic.io (simple but engaging): 
- Using WTcsv in english (.PDF guide).   
- Who is the template for: The instructor and he will use it to lead the activity. Important note: In activities for your students you will not add the stuff for the instructor but should be able to know all of this if you are the instructor.
- What does it have: Guideline for the instructor to use the template and run the activity.

Anatomy of an activity template (from the example linked above):
- Headline / call to action
- What is the tool or method or lesson about and why it is important for you (what’s in it for me as a student)
- Add a good real life example for icebreaker
- Learning Goals
- Run the Activity: Explanation on how to run the activity			
- You should be able to answer yourself things like: Duration of activity, What’s your audience, Difficulty level, Space and requirements, Reminders, Terms you will Introduce.


Use normalista
---------------
Pending. Here we will describe how to download, configure and personalize (colors, fonts, basically) normalista.


Inspiration and acknowledgements
---------------

normalista stands in the shoulders of giants and learns from many individuals and organizations that have done great work and thought a huge deal about online documentation, educational materials and ways to present everything for teachers and students. 
Beyond the trove of many good online learning platforms, here are some that for one reason or another I would like to highlight in no particular order: P2P University and their [Jekyll Course Template](https://p2pu.github.io/jekyll-course-template/), [18F’s Guides](https://pages.18f.gov/guides/) and [Guides Template](https://pages.18f.gov/guides-template/), [Mozilla Learning Network](https://learning.mozilla.org/), [Mozilla Developer Network](https://developer.mozilla.org/), [Databasic.io](www.databasic.io), [Datatherapy.org](www.datatherapy.org),[W3Schools](http://www.w3schools.com/), [Google developer tutorials](https://developers.google.com/maps/documentation/javascript/get-api-key), Dan Nguyen’s Small Data Journalism [course website](http://www.smalldatajournalism.com/), Lena Groeger’s [Design course](http://lenagroeger.com/design), [Read the docs](https://readthedocs.org/), and everyone that has ever written Journalism training materials at IRE and the NICAR community.

Contributors
---------------

Add list of awesome creative people who have contributed in some form to the project:

Name, Last name 🤓

If you want to **contribute** submit an issue proposing layouts, user cases, improvements, learning activities, ideas worth checking, etc.  
