
# Front-end Milestone Project - Viper Gym

*Developer: Anthony Guillermo*

 - Project Brief 
 - Technologies
 - UXD
 - Deployment
 - Tests and Fixes
 - Media
 - Acknowledgements
 

## Project Brief

In this project I was tasked with building a front-end site presenting useful information to users, using all the technologies  learnt so far in this course.

The data was to be presented in way that helps users achieve their goals and and advance the site owners goals.

Build a website for a gym (Viper Gym) mainly using technologies such as HTML, CSS and as on option bootstrap and or other CSS libraries or frameworks. The project may be started using wireframes, as taught in the UX lesson.

Viper Gym is a relatively new business opened 5 years ago. The following requirements were given by the gym after meeting with the client;

 - The users of the site are gym members and potential members who want to know about the gym and it's procedures
 - They would also like to showcase photos of members using the gym, their facilities, classes and timetables for classes.
 - Also provide information about the gym's location , opening hours and contact details.

## Technologies

 - HTML5
 - CSS3
 - [Bootstrap v4.4.1](https://getbootstrap.com/)
- [Font Awesome v4.7.0](https://fontawesome.com/v4.7.0/)

## UXD

**Strategy**

|Focus	|User Needs	|Business Objectives	|
|:------------:|:------------:|:------------:|
|Aims	|Interested in joining the gym	|Increase members	|
|	|Look at gym's facilities/classes	|Retain members	|
|Clients|Get membership for myself/pro athletes/friends| Increase customer base|
|User objectives|View photos of gym members and facilities|Gain gym exposure
|	|Read about gym philosophy/training plan|		|
|	|Read about gym/sports dome/recovery center/trainers|		|
|	|Find out address/contact information/social media links| 		|
|	|Find out timetable of classes|		|

**Scope**

|Focus	|Functional Specification	|Content Requirements	|
|:------------:|:------------:|:------------:|
|Features	|Home	|Join gym/read 3 Step Plan	|
|Future Features|Facilities	|Read about gym facilities	|
|	|Gallery	|View photo gallery|
|	|Classes	|View classes timetable|
|	|Sign In / Sign Up|Join gym or member log in|
|	|Where to find us|Access location and opening hours|
|	|Get in touch|Access email address and phone|
|	|Social Media|Access social media links|
|	|~~Bookings~~|~~Book a class or private workout~~|

**Structure**

|Focus	|Interaction Design	|Information Architecture	|
|:------------:|:------------:|:------------:|
|Information Structure	|How to navigate the site	|Navigational Structure (Tree/Dashboard)	|
|Groupings|Mobile- hamburger navigation|Home/Facilities/Gallery/Classes/Sign In Sign Up|
|	|Desktop/Tablet - navbar|Home - Sign Up/Three Step Plan	|	
|	|	|Facilities - Gym/Sports Dome/Recover Center/Trainers|
|	|	|Gallery - Photos|
|	|	|Classes - Timetable|
|	|	|Sign In/Sign Up - Form (modal)|

**Skeleton**

|Focus	|Interaction Design	|Navigational Design	|
|:------------:|:------------:|:------------:|
|Presentation of information|[See Wireframe](https://github.com/anthonybguillermo/frontend-project/blob/master/wireframe/wireframe-vipergym.pdf)|Home|
|User Navigation|Desktop/Tablet/Mobile - location/hours/contact details/social links in footer|Facilities
|	|	|Gallery|
|	|	|Classes|
|	|	|Sign In/Sign Up|

**Surface**

|Focus	|Visual Design	|
|:------------:|:------------:|
|Look of finished product|	|
|Colors and typography used|[Oxanium Font](https://fonts.googleapis.com/css?family=Oxanium&display=swap)	|
|	|#66b933	|
|	|#474140|

## Deployment

 - On project repo page on GitHub click on "Settings"
 - Scroll  down to "GitHub Pages"
 - Select master branch from drop down bar under "Sources"
 - Select "Save"
 - Project link: [Viper Gym](https://anthonybguillermo.github.io/frontend-project/) 

## Tests and Fixes

**Mobile** 

Tested on Chrome mobile simulator

***Mobile Issue***

In facilities page was overlapping/blocking navigation bar

***Mobile Fix***

Adding a class in "Trainers" column to hide the text when on mobile.

> class="col-12 col-lg-3 d-none d-sm-block"

***Desktop/Tablet***

Tested on Chrome desktop and tablet simulator

***Desktop/Tablet Issue***

There was a gap between the the "Hero Image" on the Home page and the "3 Step Plan" section. 

***Desktop/Tablet Fix***

In "content-container" changed "margin-top" to "padding-top".

> .content-container {
padding-top: 75px;
padding-bottom: 75px;
}

## Media

The photos used in this project were taken from [pxhere.com](pxhere.com)

## Acknowledgements

Inspiration for this project was taken from [razer.com](razer.com) , [Mamba Sports Academy](https://mambasportsacademy.com/) and previous Code Institute Projects (Love Running, Resume and Whiskey Drop).
              
