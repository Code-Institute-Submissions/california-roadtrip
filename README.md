![Welcome](https://california-roadtrip-nikl.c9users.io/assets/css/images/readme.png)

This is the readme file of a Single Page Application, or Single Page Interface (from now on abbreviated to SPI), called 'California Roadtrip'. 
This webapplication provides the users a set of useful information to prepare their holiday roadtrip to the US state of California. 
Generaly the website can show the user information about routes and locations (Google Maps, Google Places) and give the user choises between a variation of accomodations in different price and luxury level's. 
The design is focused on transparency and a simple, attractive usable interface.


This project concerns the second official assignment at Code Institute (see more about Code Institute at www.codeinstitute.net). 

Niels de Klerk (february, 2019)


## UX perspective 

User stories, as an important part of the UX design, are short, simple descriptions of a feature told from the perspective of the person who desires the new capability, 
usually a user or customer of the system. In a random order a list of important user stories has been drawn up bellow from the perspective of the specific user that we aim for: 

*	"I want to see directly what kind of website I’m looking at"; 
*	"I want to see what the main goal of the website is (defined by differtend indicators)"; 
*	"I want to easely use the mechanics of the website and see what the result is of clicking trough the highlighted content or event handling options"; 
*	"I want to possibility to easely return to a previous state within the workflow of the website";
*	"I want to see marks, highlighted buttons or other indicators that can show the results of single or multiple actions that i take on the website". 


In the following link additional information concerning the UX/UI design can be found. 
This includes wireframes and mockups and basic images for the branddesign: 

https://drive.google.com/drive/folders/1PtXtJduz-PELMQiYZTIpvAgPSXKjqaYd?usp=sharing

## Features

Existing Features (week 6 - 2019) 

*	Main feature 1 - A splited SPE with a left frame for data, input fields, event handling and images, and on the right a rendered map in the specific UX/UI design of the project; 
*	Main feature 2 - Integrated Google Places API, Google Maps JavaScript API, Directions API, Maps Embed API to load specific routes on the map; 
*	Main feature 3 - Preselected routes defined that relies on the mentioned API's; 
*	Main feature 4 - Accomodations data and images available using JQuery; 
*	Feature UX/UI 1 – Splashscreen with specific UX/UI design as starting (and turnback) point and access to the SPI; 
*	Feature UX/UI 2 – Easy and clear dark/grayscale design with bright and colorfull images that makes it more attractive for the user; 
*	Feature UX/UI 3 – Warning information available when displaying the SPE on a resolution that will not suit the best user experience;
*	Proces/Flow  1 - Indicatiors (markers/button colors) that show the phase/status about actions that the user takes; 
*	Proces/Flow  2 – Possibilty to switch between splashscreen and the SPE. 

Features Left to Implement (in a random order listed below)

*	Remove 'standard' Google zoomlevel options that automaticly render by using the Maps API; 
*	Add customer login in de main navigation bar for (existing) customers (basic portal functionality);  
*	Add customer stories as an extra section on the website; 
*	Add Google analytics to generate relevant data;  
*   Replace dummy images and text on for customerlogo's with a matching description.  

## Technologies Used

In this section all of the languages, frameworks, libraries, and other tools that have been used are mentioned. 

*	HTML 5 - 
    *The website uses HTML5 as a fundamental basis for building the website.

*	CSS3 - 
    *The website uses CSS3 with regard to the styling of all elements within the website. For this a separate layout has been created within the page structure. 
    *CSS is used for all content, including: images, layout of color and background, etc.

*	Bootstrap 3.7.6. - 
    * The open-source Bootstrap framework has been used to implement some basic templates for forms, buttons and navigation. 
    *   Bootstrap has also been used to stand with a responsive design of the web page.

*	Cloud9 - 
    *AWS (Amazon) Cloud9, a cloud-based integrated development environment (IDE) that has been used to write, run, and debug the code used for the website. 

*	GitHub - 
    *GitHub has been used for version control of the code by using Git. 
    *During the realization of the project, Git was daily used.

*	Core JavaScript - 
    *Core Javascript has been used to use the event handling functionality's on specific buttons. 

*	Jquery libraries - 
    *Jquery has been used for most interactive parts of the SPE. JQuery has been used to render the maps with specific routes and selections on specific buttons. 

*	Fontawesome - 
    *Fontawesome as a toolkit has been used to the UX/UI so the SPE has is own brand identity. 

*	Google Developer Environment - 
    *The Google Developer Environment has been setup to use the different places API's, and also to check the traffic of the API's and to learn about other relevant data in the API dashboard. 

*	Google API's  - 
    *The used API's are mentioned in the list of existing features. 


## Testing

Various methods have been used to test the code of the website. During development, there has been continuously tested on the quality of the code. 
This has been done by checking the correct functionality of the code on different screensizes, different resolutions,
different devices (mobile, tablet, desktop). This approach is used from the start to the end of the realization of the project.

Site viewed and tested in the following browsers:

    * Firefox
    * Safari 
    * Chrome

The design choise has been made that the SPI will not be showed on resolution with a lower width then 1200px. 
When using the SPE at a lower resolution, the quality of the application is to much reduced. From the UX/UI perspective, the user will recieve an instruction how to use the SPE when opening on a unsuitable screensize and what 
to do to next. 

The SPE has been tested on the following devices and is fitted for purpose on a laptop, desktop or large desktop: 

    * Macbook 13" 
    * Macbook 15"
    * Windows 10 desktop 27" 
    * Iphone 8 (to test warning message)

Mockups and sketches were also used to continuously build and deliver in accordance to the initial plan and design of the website.
In the final phase of the project, the opinion of a number of people was asked. We used professinoals and non professionals to see iff the site functions properly from a certain perspective. 
In order to be able to check whether the code functions as it was conceived during the design phase, we tested the functions on a basis of different scenarios.
Below the main features described that are basic functions as currently available on the site.

* Main navigation and information - 
    * Go to SPI (app.html) using the splashscreen/startscreen (index.html). 
    * Navigate back to index.html using the 'return' button.
    * Try to navigate on a screensize with a resolution lower than 1200px width.
    * Try to select specific input fields. 
  
* Use of the Maps - 
    * Select a route trough the button selector. 
    * Switch beweteen routes using the button selector.  
 
* Links - 
    * Select a accomodation. 
    * Switch between accomodations. 
    * Clear all selected accomodations.
    * Open the external link to external website (Nortstack).

* UX/UI - 
    * Verify that the navigation and google maps show the selected information.
    * Verify the changes at the splashscreen (index.html) on different screensizes (regarding user experience and clarity of design).

## Issuelist 

| Issue number    | Description     | Implemented Solution  |
| ------------- |:-------------:| -----:|
| 1	| Buttons load accomodation image but not the text | encapsulated content in same div |
| 2	| Google Places and Maps API wont load routes  | Debugging JS file  |
| 3	| Favicon won't load      | Added correct references  |
| 4 | W3C error about deprecated form styling   | Debugging form styling  |
| 5 | Console Error Javascript  |  ? n/a |
| 6 | Console Error Javascript  |  ? n/a |
| 7 | Toggle won't start with hidden property | Added display none and display block properties  |
| 8 | Images not fully responsive | Rebuild Bootstrap columns |
| 9 | Maps won't show desired postion| Changed zoomlevel in scriptfile|

## Work method 

During the development of this project Trello (Trello.com) is used as a simple project management tool to develop in a controlled project environment. I have used the 'trello-board' for all the 
actions within the project; initializing the project until the completion. The trello-board has been used for: preperation actions, building functionalities, testwork and debugging. 

Below a screenshot taken halfway of the realization.

![Trello screenshot](https://california-roadtrip-nikl.c9users.io/assets/css/images/trello.png)

## Deployment

The website is made in the AWS Cloud9 environment. To give a good idea of the development progress, short deliveries are always placed at the workspace on GitHub. 
uring the development period a upload was made to GitHub after every 3 to 4 hours of development work.

It has happened a few times that i faced some debugging actions that also changed good working code. Thanks to a restoration via GitHub, i was able to continue working on improving the project quickly. 
The way the Git process is used is as follows:

1. Builded the site on a local environment.
2. Staged the files in the stage area.
3. Perform push to Github to renew the working environment. (Git directory / repository).

The website is now live in a testing environment, available at the following link: https://nikl881.github.io/california_roadtrip/index.html. 
After implementing the remaining features listed above the site will be live at: www.nortstack.com/portfolio/california_roadtrip/index.html. 


## Credits

This README file is based on the Code Institute template.

## Media

*  All media files, used for the design of the project are selfmade. 
*  The used demo photo's are downloaded from the Shutterstock database (https://www.shutterstock.com) 

## Acknowledgements

I would like to thank Anthony Ngene (https://github.com/tonymontaro) as a supervisor and mentor in the development of this project. 
Thanks to his feedback, I have been given the correct insights to achieve this result.

I learned some fundamentals about integrating and using Google APIs (including Google Maps Rendering, Google Dashboard, etc.). 
This project was just a introduction,  I definitely want to learn more about this subject in the future. 
In addition, I gained  basic knowledge about the use (and power) of Jquery and I tried to make a step in the more complex world of JavaScript.

I'am  looking forward to the upcoming topics and challenges.