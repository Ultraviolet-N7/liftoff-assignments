# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
Most roller derby teams require their skaters to attend a minimum number of practices a month - for safety, among 
other reasons. The methods used to log and track individual skaters' practices vary widely, with little consistency. 
My current team has their players log practice hours through the Basecamp app, which automatically updates a 
Google sheet. In order to view how many practices they've already logged, a player needs to pull up that Google 
sheet outside of Basecamp, find the row with their name, and scroll until they find the column for that month. Other 
tracking methods I've seen used by other teams include having players sign in on a physical sheet every practice, 
and designating someone to post the names of whomever they remembered seeing to Facebook. The methods used by teams 
to actually schedule practices can vary pretty widely as well.

I'm going to create what I'm calling (for now) a practice hub. For the minimal viable version, the user will log in to 
see their dashboard. The user's dashboard will show how many practice credits they've earned so far for that month. 
From the dashboard, the user will be able to log the practices they've attended, and the number of credits those 
practices were worth. The dashboard will also feature a Google calendar that shows practice and event dates. From the 
dashboard, users will be able to click a link to a table showing the practice credits logged by the entire team. A 
potential future version could include the creation of administrator accounts. The administrator would be able to set 
the practice dates/types, set the number of credits each practice is worth, and set dashboard links to important 
documents. Another potential feature is enabling the user to log practices by clicking directly on them in the calendar.

### MVP Features
User login: Users will be able to create an account and log in. Each user will have a personal dashboard.

CRUD functionality: Users will be able to log their practice date, type(s), and the number of credits received. 
That data will be stored in an SQL database. Users will also be able to view the data of other users in a table.

Calendar: Users will be able to view a Google Calendar showing upcoming practices and events.

### "Nice to have" Features
Admin access and privileges: Admins would add practices to the calendar and set the type/number of credits associated 
with each. Admins would also be able to add links to important documents directly to the users' dashboards.

Data submission built into calendar: Users would be able to log their practices by clicking on a practice (or a 
button associated with that practice) in the calendar. The work of setting their practice credits would be done one 
the back end, using info submitted by the admins.

Google login integration

### Technologies
Java
Spring Boot
MySQL
Hibernate
Thymeleaf templates
Google Calendar API

### What I'll Have to Learn
I'll need to get much more comfortable with user authentication, and ideally, learn how to incorporate admin 
accounts into my user authentication. I will also need to learn how to use data from the Google Calendar API. I'm 
still not overly experienced or comfortable styling with Bootstrap, so I think that is going to be a challenge as well.

### Project Tracker
https://trello.com/b/dfRhnEvc
