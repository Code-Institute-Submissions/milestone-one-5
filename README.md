# Darwiche Band - Milestone One Project for Code Institute Fullstack Web Developer course by Jays-T


### Hello and welcome! This is a site created and designed to promote my hard rock band Darwiche - Jays-T

# CONTENTS
* UX
  * Structure
  * Owner Goals
  * User Goals
  * User Stories
  * Design process
* Features
* Technologies Used
* Sites Sourced from
* Testing
* Bugs
* Deployment
* Credits

# **UX**

## Structure

* The site is structured as a one page website scrolling over fixed background images or 'Parallax' sections.
* The landing page features the Band Logo front and center with the Band name image fading in 
* I placed the Band Logo as the Hero Image on the landing page with the intention of developing further Brand Awareness for the band. 
* The'Parallax' effect sometimes causes display issues on smaller devices
* The smooth scrolling overlap feature and fixed background images are disabled on smaller devices and the site reverts to a single page long scroll site at a width of 1024px
* There is a Navigation bar at the top of the site - This bar is fixed and does not dissapear when scrolling - The Navigation bar collapses on smaller devices and a button appears which gives access to the Nav-Links on smaller devices
* Users can navigate to each section on the site by clicking the appropriate link within the Navigation bar - The buttons/links are designated by name corresponding to their respective sections
* Users can also scroll through the site by clicking on the small down facing chevrons located at the bottom of each section.

## **Interactions that are fully functional include:**
1. The Local Site Navigation links located in the Navigation Bar fixed at the top of the site - These links also function on smaller devices and are accessed via the Toggle at the top right of the screen
1. The Social Media links in the sidebar which are linked to external sites
1. Links to open Modals (a small overlay box with content)
1. Links to close Modals
1. All scrolling chevrons

## **Areas where a link or interaction will not function as intended:**

1. The 'Get my free download' in the Call to Action modal opened by clicking on the ! Free Download of our latest Album ! and the icon on the right side.
1. All of the 'Tickets' buttons in the 'Shows' section
1. The 'Send project request' in the Lets Work Together modal in the 'Contact' section.
1. The 'Sign Up' form at the bottom of the 'Contact' section.

### **This is because this is a static site with no backend currently.**

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
* You'll see my initial idea, noted as Darwiche Idea 1 in my site mockup, is quite different to Darwiche Idea 2.

* <a href="https://github.com/Jays-T/milestone-one/tree/master/wireframes/ms1-mockup1.pdf">Initial site mockup</a>
* <a href="https://github.com/Jays-T/milestone-one/tree/master/wireframes/ms1SiteMap.pdf">Site Map mockup</a>

My decision to go with a smooth scrolling/fixed background image 'Parallax' effect was made when I saw these projects:

* https://fabibrachetta.github.io/kuua/
* https://code-institute-org.github.io/ucfd-example-project/#about

I looked into the 'Parallax' effect and found a great resource here:
* https://www.w3schools.com/howto/tryhow_css_parallax_demo.htm



# Features

* **Navigation Bar:**  This section allows the user to easily navigate to any section of the site
* **About:**    This section gives the user a very brief background about the band and its current state
* **Music:**    This section allows users to listen to music recorded/created by the band by using the media player
* **Shows:**    This section allows users to get immediate information regarding upcoming shows they might wish to attend
* **Gallery:** This section gives the user access to more specific information about each individual band member
* **Contact:**  This section gives the user information as to how to contact the band and also includes a call to action to subscribe
Users can subscribe to a mailing list if they wish to be regularly informed about relevant band news by filling out the email form and clicking the submit button 
(**note that the subscribe action does not actually currently function due to this site being simply a static site with no backend**)

* **Call to Action:** This section allows users to subscribe to get a free download of the bands latest album and also informs users that they can sign up to get news about the band

## Features not addressed in this iteration of the site and my reasons for not including them

* **Shop:**     I didn't include this section as it requires backend coding far beyond my current level of knowledge
* **News:**     I didn't include this section as I under the current scope of this project it wasn't urgent or relevant enough to the project to include

# Technologies Used

* <a href="https://html.com/">HTML</a> - for overall structure
* <a href="https://css-tricks.com/">Css</a> - to style the site
* <a href="https://getbootstrap.com">Bootstrap</a> - for responsive Grid structures and Modals
* <a href="https://jquery.com/">jQuery</a> - Used for the media player which was sourced from http://amazingaudioplayer.com
* <a href="https://www.javascript.com/">JavaScript</a> - Used by the media player and Boostrap Modals
* <a href="https://fontawesome.com/">Font Awesome</a> - for icons
* <a href="https://fonts.google.com/">Google Fonts</a> - for fonts
* <a href="https://www.gitpod.io/">Gitpod</a> - as my development environment
* <a href="https://github.com/">GitHub</a> - for version control and site Deployment


# Sites sourced from

* https://www.w3schools.com
* https://ianlunn.github.io/Hover/
* http://amazingaudioplayer.com
* https://css-tricks.com/


# Testing

## This site has been tested manually

Browsers tested in: 
* Chrome
* Microsoft Edge

Phones tested on: 
* Huawei P20Lite
* iPhone 6

Site also tested with Chrome's built in 'Inspect Element' preview panes simulating the iPad Pro, iPad, iPhone X, iPhone 6/7/8 plus, iPhone 6/7/8, iPhone 5 SE, Pixel 2 XL, Pixel 2 and Galaxy S5.


1. All links in the NavBar were tested at various sizes both at full screen and collapsed. Links worked across platforms and devices
1. Home icon on the NavBar tested and working
1. Call to action "Free download" link was tested, modal opened across platforms and devices
1. Clicked through each scrolling chevron to ensure that they worked and that they were targetting the correct id and section
1. Verified that each clickable section of the band members in the 'Gallery' worked and that the correct modal opened.
1. All modals/pop ups across the site were found to open and close without issue *(apart from the issue listed under **bugs not yet fixed**).

* I tested each form to make sure that the required sections such as 'name' and 'email' triggered a fail if they were not filled in.

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
* I coded the project using GitPod as my development environment. 
* To deploy the project I first used commits regularly while coding. I then pushed the committed files from the GitPod IDE to the master branch of the main repository on GitHub.
* After pushing the files I went to my repository and clicked on the 'Settings' tab near the top of the page and scrolled down to the 'GitHub Pages' section.
* I selected the Source as the 'Master Branch' and the site is built from the 'Master Branch'.
* You can view the deployed site here: https://jays-t.github.io/milestone-one/
* There are no differences between the currently deployed site and the development version at this time.

# To run locally

To clone this project from GitHub:

* Under the repository name, click "Clone or download".
  1. In the Clone with HTTPs section, copy the clone URL for the repository ( For this repository: https://github.com/Jays-T/milestone-one.git ).
  1. In your local IDE open Git Bash.
  1. Change the current working directory to the location where you want the cloned directory to be made.
  1. Type git clone, and then paste the URL you copied in Step 3.
  1. The command should look like this:  git clone https://github.com/Jays-T/milestone-one.git
  1. Press enter and your local clone will be created and the response should be something like this:
  * $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> * Cloning into `Spoon-Knife`...
> * remote: Counting objects: 10, done.
> * remote: Compressing objects: 100% (8/8), done.
> * remove: Total 10 (delta 1), reused 10 (delta 1)
> * Unpacking objects: 100% (10/10), done.
* For further reading and troubleshooting on cloning a repository from GitHub <a href="https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository">here</a>.

# To preview in browser

If you are using gitpod as your IDE:
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