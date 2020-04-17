<p align="center"><img src="./images/ManoaFitnessFinderLogo.png"></p><br><br>

This website can be found at:<br>
[https://manoafitnessfinder.meteorapp.com](https://manoafitnessfinder.meteorapp.com)

<br>
The repository for this website can be found at:<br>
[https://github.com/manoafitnessfinder](https://github.com/manoafitnessfinder)

## Table of contents

* [Description](#description)
* [Team Members](#team-members)
* [User Guide](#user-guide)
* [Milestone 1](#milestone-1)
* [Milestone 2](#milestone-1)
* [Coming Soon](#coming-soon)

## Description

The problem: The freshman fifteen! So many students enter and go through college feeling too ashamed to go to the gym alone or feeling afraid to go on a run alone because of safety concerns.

The solution: The Fitness Finder application allows students to log in to the application and create a profile which specifies things like their gender, interests (e.g. strength training, running, outdoors), level (e.g. just starting, intermediate), “looking for” (e.g. a mentor to help me improve, a friend to keep me company while running, spotter/gym buddy), and goals (e.g. run an 8 minute mile, squat 200 lbs, hike Stairway to Heaven). The app would pair the user with someone with matching/similar interests.

Advanced implementation would also include the ability to document meetups (for safety or progress tracking), upload photos for each completed outing, and a feed where users can see the completed meetups/workouts their friends/matched users have done.

Notes on privacy and safety: Users can only sign up if they have UH email address. The website would also warn users when setting up a meeting with a matched user to meet in advance in a public place, like the gym. In the “Beyond the Basics” section I go into detail on a scheduling/progress tracking feature that would allow users to document every single meeting, which should deter other users with dubious intentions.


## Team Members
### Patrick McCrindle
<p align="center"><img src="./images/patrick.jpg" height="250" width="250"></p>
I'm currently a Junior at UH Manoa studying Security Science. Having had no prior expierence with website design this class has been a whirlwind of new information. My interests for the this project is learning to implement basic website security and refining my knowledge of software engineering.

### Lucy Rock
<p align="center"><img src="./images/lucy.jpg" height="250" width="250"></p>
I'm currently a Junior at UH Manoa, studying to get my BS in Computer Science. I am excited for this assignment because I have always had an interest in web design, and I can't wait to apply what I've learned in this class so far.

### Sophia Rathyen
<p align="center"><img src="./images/sophia.png" height="250" width="250"></p>
I'm a junior at UH Manoa double majoring in Computer Science and Russian. I have a passion for graphic design and art and hope to make use of some of those skills while designing this site. Along the way, I also hope to become adept in using Meteor and MongoDB. I'm looking forward to merging my interest in fitness and software engineering to create a useful, beneficial website for other students.

### Nathan Anderson
<p align="center"><img src="./images/Nathan.png" height="250" width="250"></p>
Website design is my passion. Growing up on my father's Javascript farm gave me a lifelong love of creating websites and an appreciation of the development skills required. It's become my dream to create the best Meteor app React designed intellij developed website for finding fitness partners in the Manoa area.

### Christine Uehara
<p align="center"><img src="./images/cyueharaProfilePic.JPG" height="250" width="250"></p>
I'm currently a Junior at UH Manoa, studying to get my BS in Computer Science. I have some experience in designing websites using a website developer, nothing like what we are learning in class. I am excited to take what I learned while working on this project and apply it to the website I am currently designing for work. 

## User Guide

### Landing page 
This is the user's introduction to Manoa Fitness Finder.<br>

<p align="center"><img src="./images/M1-Landing.PNG"></p>


### About page
This page presents basic information about the purpose and vision of our app.<br>

<p align="center"><img src="./images/M1-About.png"></p>

### Login page
All links that contain "Login" lead here. Users can access their account specific feed pages and profile information once logged in.

<p align="center"><img src="./images/M1-SignIn.PNG"></p>


### Sign Up page
Allows new users to create accounts on Manoa Fitness Finder. Also prompts for basic user information which will contribute to their account. 

<p align="center"><img src="./images/M1-SignUp.PNG"></p>

### User profile page
Displays the users current information as other people on the website would view them. Contains a link to edit their information.

<p align="center"><img src="./images/M1-User.png" width="400"></p>
<b>Notes:</b><br/>
* Later, will possibly add a "progress tracking" feature on the bottom part of page<br/>
* Add an "add as friend" feature<br/><br/>


## Milestone 1

<a href="https://github.com/manoafitnessfinder/app/projects/1">MileStone 1</a>

<p align="center"><img src="./images/milestone_1.PNG" width="400"></p>

## Milestone 2

<a href="https://github.com/manoafitnessfinder/app/projects/2">MileStone 2</a>

<p align="center"><img src="./images/milestone_2.PNG" width="400"></p>

## Coming Soon

### Admin home page
Description is a work in progress as feature-set hasn't been decided on. All users visible and certain administrative actions can be taken from this page.

<p align="center"><img src="./images/image0.jpg"></p>


### User home page
Work in progress
This is what the user will see after they log-in to their account. 

<p align="center"><img src="./images/UserHomePage1.png"></p>


### Match/Find users page
A page that filters other profiles visible to the user based on the users preferences. This page looks to match Mentors/Mentees,<!--is Mentee a word? Like, I'm sure it is but it just doesn't feel right.--> gym partners of equal level, and workout interests.
<p align="center"><img src="./images/match.png" width="400"></p>


### Schedule/Calendar page
Allows logged in users to see their matches schedules and post their workouts. Can switch between calendar view and events view.
<p align="center"><img src="./images/schedule.png" width="400"></p>


Users can schedule workouts: If the other user agrees, to a proposed match, they can use a scheduling page to create a new scheduled workout (date, time, place). This workout will be visible to ONLY the two users it concerns to protect their privacy.<br><br>

### Edit Profile

User will be able edit their profile. Including interests, picture, first and last name.

## Potential Features

### PROGRESS TRACKING

Once the date/time passes for a scheduled workout, it will go into the user’s “progress” section of their profile – something like “(user1name) completed a 2.5 mile run with (user2name) on (date).” The user is then able to go in and edit the workout to add the time it was completed in, as well as add a picture that might have been taken on the run which they want to share. This will be posted to the friend feed if a “public” switch is toggled to on. Things like “place” can be toggled to “private” to protect the privacy of anyone who goes on recurring runs in the same place.<br>
Progress tracking, ctd: Progress tracking would have an “overall” card displaying your first workout vs. your most recent workout. For example, “first recorded bench press: 100 lb” and beneath it “most recent PR: 200 lbs with (spotterusername)”.<br><br>
### FRIEND FEED PAGE

All public progress cards are displayed for friends and matched users (maybe a feed which includes everyone on site?)<br><br>
Users can toggle match finding on/off if they find the perfect gym buddy, so they can instead use the site solely to record their progress.<br><br>
