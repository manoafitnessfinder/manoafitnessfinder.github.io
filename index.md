<p align="center"><img src="./images/logo.png"></p><br><br>

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
* [Milestone 2](#milestone-2)
* [Milestone 3](#milestone-3)
* [Coming Soon](#coming-soon)

## Overview

The problem: The freshman fifteen! So many students enter and go through college feeling too ashamed to go to the gym alone or feeling afraid to go on a run alone because of safety concerns.

The solution: Manoa Fitness Finder allows students to log in and create a profile which allows them to set their: age, upload an image, a brief description, gender, interests (e.g. Running, Lifting, Acrobatics, Calisthenics, Walking, Hiking, and Climbing), level (e.g. beginner, intermediate, or advanced), seeking (e.g. Gym Buddy, Mentor, Mentee, or no Preference), and goals (e.g. run an 8 minute mile, squat 200 lbs, hike Stairway to Heaven). The app would pair the user with someone with matching/similar interests.

After creating a profile you can create an event that you are intending to go on and want others to join, or sign-up for an event that someone else has posted. You can add people to your friends list after browsing the list of other users. 

Advanced implementation would also include the ability to document meetups (for safety or progress tracking), upload photos for each completed outing, and a feed where users can see the completed meetups/workouts their friends/matched users have done.

Notes on privacy and safety: The website would also warn users when setting up a meeting with a matched user to meet in advance in a public place, like the gym.


## Team Members

### Patrick McCrindle
<p align="center"><img src="./images/patrick.jpg" height="250" width="250" alt = ""></p>
I'm currently a Junior at UH Manoa studying Security Science. Having had no prior expierence with website design this class has been a whirlwind of new information. My interests for the this project is learning to implement basic website security and refining my knowledge of software engineering.

### Lucy Rock
<p align="center"><img src="./images/lucy.jpg" height="250" width="250" alt = ""></p>
I'm currently a Junior at UH Manoa, studying to get my BS in Computer Science. I am excited for this assignment because I have always had an interest in web design, and I can't wait to apply what I've learned in this class so far.

### Sophia Rathyen
<p align="center"><img src="./images/sophia.png" height="250" width="250" alt = ""></p>
I'm a junior at UH Manoa double majoring in Computer Science and Russian. I have a passion for graphic design and art and hope to make use of some of those skills while designing this site. Along the way, I also hope to become adept in using Meteor and MongoDB. I'm looking forward to merging my interest in fitness and software engineering to create a useful, beneficial website for other students.

### Nathan Anderson
<p align="center"><img src="./images/Nathan.png" height="250" width="250" alt = ""></p>
Website design is my passion. Growing up on my father's Javascript farm gave me a lifelong love of creating websites and an appreciation of the development skills required. It's become my dream to create the best Meteor app React designed intellij developed website for finding fitness partners in the Manoa area.

### Christine Uehara
<p align="center"><img src="./images/cyueharaProfilePic.JPG" height="250" width="250" alt = ""></p>
I'm currently a Junior at UH Manoa, studying to get my BS in Computer Science. I have some experience in designing websites using a website developer, nothing like what we are learning in class. I am excited to take what I learned while working on this project and apply it to the website I am currently designing for work. 

## Galaxy Deployment

View our current website at <a href="http://manoafitnessfinder.meteorapp.com/#/">Manoa Fitness Finder</a>.

## User Guide

### Landing page 
[http://manoafitnessfinder.meteorapp.com/#/](http://manoafitnessfinder.meteorapp.com/#/)<br>
This is the user's introduction to Manoa Fitness Finder.<br>

<p align="center"><img src="./images/M1-Landing.PNG" alt = ""></p>

### About page
[http://manoafitnessfinder.meteorapp.com/#/about](http://manoafitnessfinder.meteorapp.com/#/about)<br>
This page presents basic information about the purpose and vision of our app.<br>

<p align="center"><img src="./images/M1-About.png" alt = ""></p>

### Login page
[http://manoafitnessfinder.meteorapp.com/#/signin](http://manoafitnessfinder.meteorapp.com/#/signin)<br>
All links that contain "Login" lead here. Users can access their account specific feed pages and profile information once logged in.

<p align="center"><img src="./images/M1-SignIn.PNG" alt = ""></p>


### Sign Up page
[http://manoafitnessfinder.meteorapp.com/#/signup](http://manoafitnessfinder.meteorapp.com/#/signup)<br>
Allows new users to create accounts on Manoa Fitness Finder. Also prompts for basic user information which will contribute to their account. 

<p align="center"><img src="./images/M1-SignUp.PNG" alt = ""></p>

### User profile page
[http://manoafitnessfinder.meteorapp.com/#/profile](http://manoafitnessfinder.meteorapp.com/#/profile)<br>
Displays the users current information as other people on the website would view them. Contains a link to edit their information.

<p align="center"><img src="./images/M1-User2.png" width="400" alt = ""></p>
<b>Notes:</b><br/>
* Later, will possibly add a "progress tracking" feature on the bottom part of page<br/>
* Add an "add as friend" feature<br/><br/>

### All Users Page
[http://manoafitnessfinder.meteorapp.com/#/AllProfiles](http://manoafitnessfinder.meteorapp.com/#/AllProfiles)<br>
This page lists all users on the site, allowing you to filter based on age, interests, fitness level, and seeking status.

<p align="center"><img src="./images/AllProfiles.PNG"></p>

### Events
[http://manoafitnessfinder.meteorapp.com/#/schedule](http://manoafitnessfinder.meteorapp.com/#/schedule)<br>
Here you'll be able to view events that you and your friends have created.

<p align="center"><img src="./images/events.png"></p>

### Another User
This is the page to view another User's profile. There will be key features missing such as the edit profile button.

<p align="center"><img src="./images/OtherUser.PNG"></p>

### Friends Page
[http://manoafitnessfinder.meteorapp.com/#/friends](http://manoafitnessfinder.meteorapp.com/#/friends)<br>
Lists all of the profiles you have added to your friends list.

<p align="center"><img src="./images/FriendsList.PNG"></p>


## Developer Guide

First you will need install <a href = "https://www.meteor.com/install">Meteor</a>. Second you will need to install <a href = "https://nodejs.org/en/download/">Node.js</a>. 

Thrid go to the our <a href = "https://github.com/manoafitnessfinder/app">github</a> and download it as a template. Fourth copy it to your local machine by clicking "Clone or Download". 

Now cd into the app directory of the local your local copy and perform:

`
$ meteor npm install
`

Followed by:

`
$ npm install moment --save
`

With that all out of the way launch the application with the included start script:

`
$ meteor npm run start
`

Now you have a local instance running. You can modify the code as you want. Feel free to email us with issues you may be having at manoafitnessfinder@gmail.com.

## Milestone 1

<a href="https://github.com/manoafitnessfinder/app/projects/1">MileStone 1</a>

<p align="center"><img src="./images/milestone_1.PNG" width="400" alt = ""></p>

## Milestone 2

<a href="https://github.com/manoafitnessfinder/app/projects/2">MileStone 2</a>

<p align="center"><img src="./images/milestone_2.PNG" width="400" alt = ""></p>

## Milestone 3

<a href="https://github.com/manoafitnessfinder/app/projects/3">MileStone 3</a>

<p align="center"><img src="./images/milestone_3.PNG" width="400" alt = ""></p>

