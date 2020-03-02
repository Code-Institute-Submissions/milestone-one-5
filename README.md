# Darwiche Band - Milestone One Project for Code Institute Fullstack Web Developer course by Jays-T


### Hello and welcome! This is a site created and designed to promote my hard rock band Darwiche - Jays-T

# **UX**
* The site is structured as a one page website scrolling over fixed background images or 'Parallax' sections.
* The landing page features the Band Logo front and center with the Band name image fading in 
* I placed the Band Logo as the Hero Image on the landing page with the intention of developing further Brand Awareness for the band. 
* The'Parallax' effect sometimes causes display issues on smaller devices
* The smooth scrolling overlap feature and fixed background images are disabled on smaller devices and the site reverts to a single page long scroll site at a width of 1024px
* There is a Navigation bar at the top of the site - This bar is fixed and does not dissapear when scrolling - The Navigation bar collapses on smaller devices and a button appears which gives access to the Nav-Links on smaller devices
* Users can navigate to each section on the site by clicking the appropriate link within the Navigation bar - The buttons/links are designated by name corresponding to their respective sections


## Owner Goals
#### For the owner the goals are:

* Increase Band visibility
* Increase Brand awareness
* Showcase music
* Inform users of upcoming shows 
* Generate a mailing list of subscribers

## User Goals

#### For the user the goals are:

* Gain knowledge about the band
* Listen to music created by the band
* Get information regarding upcoming shows
* Find out how to get relevant information from the band on a regular basis
* Get to know more about their favorite band member or members
* Purchase merch with band branding
* Book the band for various events

## User Stories

1. "As a **Fan** of the band I want to find out if my favorite band, Darwiche, have any upcoming shows near me so that I can go and see them live." -- Fan X
1. "As a **Fan** I'd like to support the band and would like to know if they have any merch for sale, maybe some t-shirts?" -- Fan Y
1. "As a **music lover** I would like to hear what the music of this band I've just discovered sounds like." -- Random Music Lover
1. "As a **music blogger** I would like to find out a little bit more about each member of the band." -- Music blogger

# Design process
My decision to go with a smooth scrolling/fixed background image 'Parallax' effect was made when I saw these projects:
* https://fabibrachetta.github.io/kuua/
* https://code-institute-org.github.io/ucfd-example-project/#about

I looked into the 'Parallax' effect and found a great resource here:
* https://www.w3schools.com/howto/tryhow_css_parallax_demo.htm

<a href="https://github.com/Jays-T/workspace/milestone-one/wireframes/ms1-mockup1.pdf">site mockup</a>

# Features

* Navigation Bar:  This section allows the user to easily navigate to any section of the site
* About:    This section gives the user a very brief background about the band and its current state
* Music:    This section allows users to listen to music recorded/created by the band by using the media player
* Shows:    This section allows users to get immediate information regarding upcoming shows they might wish to attend
* Gallery: This section gives the user more specific information about each individual band member
* Contact:  This section gives the user information as to how to contact the band and also includes a call to action to subscribe
Users can subscribe to a mailing list if they wish to be regularly informed about relevant band news by filling out the email form and clicking the submit button 
(**note that the subscribe action does not actually currently function due to this site being simply a static site with no backend**)

* Call to Action: This section allows users to subscribe to get a free download of the bands latest album and also informs users that they can sign up to get news about the band

## Features not addressed in this iteration of the site and my reasons for not including them

* Shop:     I didn't include this section as it requires backend coding far beyond my current level of knowledge

# Technologies Used

* HTML5 - for overall structure
* Css3 - to style the site
* Bootstrap - for responsive Grid structures and Modals
* jQuery - Used for the media player which was sourced from http://amazingaudioplayer.com
* javascript - Used by the media player and Boostrap Modals
* Font Awesome - for icons
* Google Fonts - for fonts
* Gitpod - as my development environment
* GitHub - for version control and site Deployment


# Sites sourced from

* https://www.w3schools.com
* https://ianlunn.github.io/Hover/
* http://amazingaudioplayer.com


# Testing

In this section, you need to convince the assessor that you have conducted enough testing to 
legitimately believe that the site works well. Essentially, in this part you will want to go 
over all of your user stories from the UX section and ensure that they all work as intended, 
with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, 
provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much 
detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

# Bugs

### Bugs found during initial testing and fixed 

**NavBar Bug #1**
* Collapsed NavBar data toggle found to be unresponsive once triggered and collapsible link section of the NavBar found to not automatically collapse after a link had been clicked -
### **I fixed this issue by adding the 'data-toggle' and 'data-target' commands to each individual list item within the NavBar - This fixed NavBar Bug #1 but caused NavBar Bug #2**
**NavBar Bug #2**
* Main Navbar found to be collapsing each time one of the list items was engaged(clicked) causing a wierd visual effect 
* The solution I eventually went with to this issue was not the most elegant or efficient solution but I wanted to stick to HTML and CSS as much as possible 
* I found that when trying to solve the issue using jQuery or javascript I was unable to understand what was required. 
* My solution was to have two instances of the NavBar:
   1. One which would only be visible on larger devices which would not collapse and for this I used the standard bootstrap NavBar code
   1. One which would only be visible on devices at the original bootstrap breakpoint and for which 'data-toggle' and 'data-target' 
commands would be added to each individual list item within the NavBar.

### **In subsequent versions of the site I plan on only having one NavBar and fixing the issues found using jQuery or JavaScript**

* Issue found with selected Fonts not displaying correctly on smaller devices - 

### Bugs not yet fixed

* Issue with background images shifting slightly to the right when a modal is opened on a PC - 
this is due to the scroll bar on the right side of PC browsers, I was unable to find a fix via HTML or CSS and so I plan to fix this issue in subsequent versions of the site


# Deployment
* This project and all project files are hosted on GitHub via my GitHub repository at https://github.com/Jays-T/milestone-one 
* To deploy the project I went to the 'Settings' tab near the top of the page and scrolled down to the 'GitHub Pages' section.
* I selected the Source as the 'Master Branch' and the site is built from the 'Master Branch'.
* There are no differences between the currently deployed site and the development version at this time.

# To run locally
The project runs only from the Master branch the main directory of which is:  /workspace/milestone-one
When in the main directory enter the following into the command prompt
1. python3 -m http.server
1. This will run the contents of the directory on a local web server, on port 8000.
1. If you are working in Gitpod this will give you an option to 'open browser' which will open the default 'index.html'
1. If you want to stop the local server from running simply press crtl + C

# **Credits**

**Code**
Some of the code for the parallax scrolling style was adapted from these sources:

* https://www.w3schools.com/howto/howto_css_parallax.asp
* https://www.w3schools.com/howto/tryhow_css_parallax_demo.htm

Hover/Chevron animation sourced from:

https://ianlunn.github.io/Hover/

## Content

The text was written by myself

Media
The photos and music used and presented within this site are owned by myself and my band, Darwiche

## Acknowledgements

I received inspiration for this project from:

* https://code-institute-org.github.io/ucfd-example-project/#about
* https://fabibrachetta.github.io/kuua/
* https://www.w3schools.com/howto/tryhow_css_parallax_demo.htm