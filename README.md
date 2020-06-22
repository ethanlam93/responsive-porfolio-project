# responsive-portfolio-project

<h2>PROJECT INTRODUCTION</h2>
For this Portfolio project, I am given a wireframe of a basic portfolio case and I will utilize HTML and CSS with Bootstrap to mimic the wireframe, as well as adding some personalized information to it. 

In order to add the complexity of this project, the website has to be responsive to different default screen-size. For Ex: the column will stack up once the website is at a smaller width.
<br>



<h2>PRORJECT PROCEDURES:</h2>

1. Sketch out the bootstrap grid system based on the desired wireframe.
2. Decide how many columns and rows are on each page
3. Decide the contents that go inside each box
4. Code the HTML
5. Style using CSS
6. Refactor
7. Upload to Git Repo
8. Test Deployment on different browsers and different browser sizes


<h2>PROJECT DETAILS</h2>
Some important details regarding the execution of my HTML files:

* This website is 100% based on bootstrap with some tweaks to customized the looks and sizes to match the wireframes given.
* I utilized Bootstrap grid system with ".container", "row", and "col-" classes to build responsive body
* I utilized comments a lot throughout the project to make sure the evaluator understand what and why such codes are executed
* The Navigation Bar and Footer Bar for all three pages are identical codes.
* I also utilized Google Font "Banger" for the Logo and "Robotto" for the rest of the website, limit my fonts to only 2, using external stylesheet
* For the Portfolio.html container, I also use sub-row and sub-column to construct the responsive gallery
* In order to make better codes, I try to use semantic tags such as main, header, section, figure, figcaption, form
* For better access to media, I used a local folder named "media" to contain all the images used on the website
<br>

Some important details regarding the execution of my CSS files:
* I throw in some pseudo-classes to get a little practice. Ex: I use hover for nav bar links to change color and size when hover over
* I also learned to use the pseudo element selector :placeholder-shown to style input form placeholder fonts
* The main thing I code for the CSS file is to adjust the responsiveness of the "col-" class to react to a specific width, usually we can use col-md or col-sm or col-lg but those width are defined by Bootstrap. Because this project ask for a specific width, I had to copy bootstrap properties for each "col-" class and re-style them in CSS using !important to override Bootstrap predefined behaviors
* GOOGLE CHROME INSPECT TOOL is GOLDEN for this project. By toggling the properties under the style tab, i know exactly where to fix my styling errors or insert a new style.
* As i thought i completed the project, when I take full page screenshot of my html file, i run into a HUGE ISSUE: something in my body is overflown, which means the total width is higher than the screen width, after 5 hours of trying to inspect which part of my body caused the issue, i found an trick to fix it: by inserting an attribute called "overflown-x: hidden" into by body


