
## Janica's Developer Portfolio 

*This is a portfolio website that is meant to be updated as I learn more coding principles. The purpose is to showcase my work to potential employers.* 



## Setup 
That which is required to run the site is a browser and this URL: 


## Usage

The site features a title of the developer's name at the top, Janica Jensen. Directly beneath, one will find a navigation bar which includes links for "About", "Work", and "Contact". Clicking each of these will redirect the user to the part of the site that contains that information. It is a one-page application, therefore it will only auto-scroll the user to the indicated section. Note that there is a hover effect over all links "< a >"
 elements. 
 
 The first section is the "About", which includes a short description of myself and an Apple MeMoji portrait. 

 The second section is the "Work" section, which includes clickable images and text that will redirect the user to those apps. The featured app, Horiseon, is the largest. It is followed by three imaginary apps that I came up with while at a work meeting. The descriptions are silly and they are meant to be, please do not take them too seriously, they are not real. Clicking the Horiseon banner will indeed redirect you to that GitHub Pages site, while clicking the other 3 false apps will take you to a Canva site that I created purely to show that I can make the links work, since it was a part of the requriements. 
 
 The last section is the "Contact" section. This includes a form to contact the developer, a text-input box for the message, an email input box, and a send button. Please note that these will not do anything, unfortunately, we have not learned how to make those form inputs functional yet. They are there purely as dummy parts. There is also a link to my LinkedIn, which is real. Note that my name on LinkedIn is different than on the site, this is merely due to the fact that I am known with my maiden name at my current work and do not wish to update LinkedIn until I am officially no longer an employee with them. 

Something to note is that there are pseudo classes on the 3 gallery apps to make them slightly larger upon hover. All < a > elements and the SEND button in the Contact section have a color change upon hover. The body was given a smooth scroll effect. There are alt tags for all images and care was taken to ensure semantic tags were included in the HTML. 

## Team

* Janica Jackson Jensen 

## Errors and bugs
 
-  No footer is included due to the fact that there is nothing I could possibly put there. 
- The form doesn't actually work, it's decorative. Once I know how to make it work, I will. We have not yet hit that part of the curriculum. 
- The Horiseon logo with the actual horizon/sun isn't real. 
- If one actually navigates to the Horiseon site, clicking the links will not actually move you on the page. I believe this is a GitHub pages problem, as it works just fine in LiveServer.

## Appearance and URL
URL again, can be found here: 
![](assets/app%20screenshot%201.png)
![](assets/app%20screenshot%202.png)

## Requirement check: 


- Application's links all function correctly.

- Application's CSS selectors and properties are consolidated 🟡 and organized to follow semantic structure✅.
     -*I did my best with this. Some things, when removed, just messed it all up. Though some made sense to move elsewhere, when tried, they broke. They do, howeever, follow the best structure possible.*

- Application's CSS file is properly commented.✅

- Application deployed at live URL.✅

- Application loads with no errors.✅

- Application GitHub URL submitted.✅

- GitHub repository that contains application code.✅

- Application resembles (at least 90%) screenshots provided in challenge instructions.✅
    - *Our TAs said it was OK if ours did not look like the example provided as long as it met requirements. *

Repository has a unique name.✅

Repository follows best practices for file structure and naming conventions.✅

Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.✅

Repository contains multiple descriptive commit messages. ✅

Repository contains a quality README file with description, screenshot, and link to deployed application.✅

GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name ✅, a recent photo or avatar ✅, and links to sections about them ✅, their work✅, and how to contact them✅

WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section

WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications ✅

WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others ✅

WHEN I click on the images of the applications 
THEN I am taken to that deployed application ✅

WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport 🟡
    - *I really did my best with this. Sometimes the items would not change upon resize, I added a viewport tag in the HTML to see if that would help and it did, somewhat, but parts of my site still don't optimize.*