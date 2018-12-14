Report
---------

Web Site Design (SWD500)

Report By Alexander Zietara Nicholls

Introduction

The aim of this project is to research the best approaches for creating a fully responsive, dynamic website that will act as a personal portfolio.  This report sets out the planning, preparation, research and methods/techniques used in the design process. 

Research & Options Analysis  

There are 2 types of design – responsive and adaptive.  Responsive Design is a design feature that allows your website to be fully compatible for many different devices (e.g. phone, tablet and pc) using HTML and CSS media queries. CSS Media queries are a set of CSS commands that are used within a CSS file to adjust the viewport height and width. Research also looked at grid systems. Two types of grid systems include Flexbox and CSS grid.  Adaptive Design is easier to maintain but is more restrictive as it requires different layouts for different screen sizes.  Taking the two types into consideration, responsive design is the preferred approach because it will ensure the website meets latest design trends.  (Anon., n.d.)

There are two types of scrolling features that can be used in a web-site to show the flow of the webpage; scrolling can either be top to bottom (vertical – most common) or left to right (horizontal).  Horizontal was chosen as best suited the website as it gave a sense of progression of ‘time’. (tricks, n.d.) 

Search Engine Optimization (SEO) uses algorithms to push relevant topics to the top of the page. This was considered as metadata can be used to improve your sites reputation by providing a search engine description or brief of the page. Good reputation for SEO helps increase your search engine rankings. (Techquickie, Jun 6, 2017) It is important to ensure your website doesn’t appear different within different browsers, therefore consideration was given to browser compatibility plugins e.g. Babel. 

File structure and storage is key for building a website. It helps file organisation and file directory when referring to a file within your code. When adding an image in a html file, having a good root directory links the file from its destination to your HTML file. There are a number on the market, such as Drop Box, Googledrive, iCloud and OneDrive.  Preference was for GitHub as it has a good reputation as a service tool for managing and storing web files using git and is relatively easy to use. (Anon., n.d.)

Visual impact of the site is a major consideration.  Good colour schemes are used to bring your website to life, create impact and make it memorable. (DeMatas, Nov 22 2017).  Typography is another design element researched. Preference is for Helvetic font as it is clear, modern and smart and can be used in different sizes to maintain the design.   (GCFLearnFree.org, Aug 10, 2016)

Aurelia, Ember.js, Angular, React and Vue were Frameworks reviewed. The source used (Erik, Jan 8, 2018) listed each one from 5 – 1. I believed that Vue is the best one.

Methods 

Project Time Management Plan 

Report 30% (44 hours) and Development 70% (100 hours) - (144hrs)

Stage	Duration (hrs)	Start Date	Completion Date
Research & Analysis 	10	28-Sept	04-Oct
Planning 	10	05-Oct	11-Oct
UX Design	10	12-Oct 	18-Oct
UI Design 	4	19-Oct	21-Oct
Experimentation 	10	22-Oct	29-Oct
Development 	90	30-Oct	06-Dec
Testing	9	07-Dec	13-Dec
Launch	1	14-Dec	14-Dec


 


Speciﬁcation - outline of project design needs, features, functions

The overall aim is to produce a modern portfolio website to showcase expertise as a web designer.  The following table sets out the design features. 

Needs	Features 	Functions 
Device Compatible 	Responsive Design using CSS Grid 	Media Queries, CSS and HTML allows the device to be compatible for multiple different devices – phone, tablet and laptop/PC. 
Good Navigation 	Navigation Bar using HTML and CSS 	HTML tags – anchor tags and href value, unorder-list tags and li-tags. This links all the pages together. 
Browser Compatibility 	Browser compatible 	Using webpack and Babel enables the site to adapt to old and new versions. 
Interactive	Live video wallpaper or parallax effect.	Using JavaScript, HTML and CSS to create website features. 
Branding	Simple, modern, clean, effective	black, white grey Modern shapes, 


Test Plan 

Testing is a vital stage of web-design.  The two different types of tests to be used are functional and usability. The functional testing involves  testing out the software functions and features. ( (Anon., n.d.))

User and usability testing will involve a user testing out the usability and interface. The user testing will also enable the website to be evaluated to see if it meets expectations and goals set out at the start of the project.   ( (Anon., n.d.))

The test plans below have been created and will be used to undertake technical and user testing.  After the test plan, surveys will be created for both plans to analyse each test. Once the tests have successfully been carried out, information will be gathered and assessed to see if it meets predicted outcomes. If not problems and solutions will need to be taken into consideration.  




Functional Testing Plan
Tests	Expectation	Outcome	Problem(s)	Solution(s)	Comments
Code	HTML, CSS meets W3C validation standards. No syntax errors and quality of code is at a high standard.				
Website and Page Performance	Fast and interactive. Quick loading speeds and response times. 				
Responsive – Is it Multi Device Compatible	The layout works on all devices from phones to tablets to Laptops and PCs				
Browser Compatibility 	Fully compatible for all new and old browsers
				
Website Features 
Performance	•	Live Background video plays instantly when the user clicks on to the homepage. 
•	Parallax responds to mouse movement
•	Blog and Project widgets are responding and regularly updating content. 				
Navigation- 	Links all work and user can easily navigate through site. 				
Form testing	Contact Form works and validates correctly.
				


Stress and endurance behaviour – Can the website handle its workload	Website can achieve the set workload aimed. 				

Usability and Interface Test Plan 

Tests	Expectation	Outcome	Problem	Solution(s)	Comments
Content	Images, Videos, Text should be working. 
•	There should be no grammar and spelling mistakes within the work.
•	The teste should be able to easily understand your information.
•	Images should be positioned in the same place as the UI design with the proper sizes. 
•	Text/fonts should have a 
•	and be readable for the user.
				
User Navigation 	User should be able to navigate their way through the website without getting confused or lost.  				
Design Elements	All design elements should match the visual style guide and UI design. 				
Screen Resolutions	As the website is responsive. It should work on different window sizes				
Website Features 	Horizontal scroll, live video and parallax effect should work accordingly. 				


Coding Style – HTML, CSS and JS 

Having a HTML style is great for quality and readability of your code. Good HTML is a requirement to meet the W3C standards. For the website, I will use my own HTML style guide. 

Element tags should use lower case letters. The code that will be written, includes closed tags at the end of your code. Attributes values should have quotation marks when referring to a name of an attribute. Images should include an alt when describing an image. This is a requirement when validating your code. 

Commenting code (“/ HTML code /”) is a way of describing a function or block of code. This makes your code readable and understandable for people without any/little programming knowledge. It benefits developers, for instance from own experience code commenting can help you keep track of where your code is and test out lines or blocks of code. 
Code structure is important for keeping your code clean and organised. Indentation and white-space are two rules that help improve your code structure. White-spacing should be used when including child tags within a parent tag.  

For the chosen CSS coding style, I will use SASS. It will allow me to write out CSS in a simple format using SASS or SCSS syntax. Using variables, I can store CSS properties in set variables, so they can be reused through-out the code.  SASS can help provide with nesting HTML elements.  Mixins could be used within the site when using a group of CSS features.  During the project I will also refer back to the SASS style guide to help validate my SASS code – 

For JS coding styles I am aiming to use the WS3 schools style guide. The JS code will have to be properly indented and use regular white spacing to make sure the layout of my code is shows good practice.  Semi-colons should always be used at the end of each statement, variable and function. Open brackets will need to be used when starting a function and a new line should be used when adding a closed bracket. 

Lint and Hint extensions/tools could be used to help validate my code. This will help with my code consistency and improve the overall quality of code for my programming languages. A good extension that I use on VS code is 

File, folder and image structure for website

 


GitHub – GitHub branch strategy

GitHub flow is a branch strategy that is used to manage our work. Here is a diagram below from GitHub explaining this: 

 
Image source: https://cdn-images-1.medium.com/max/1600/1*iHPPa72N11sBI_JSDEGxEA.png

Mainly I use branching for team projects however I do use it in self-projects. For this website, I will use the GitHub Flow system to test out different features. Here is an example to demonstrate how it would be used: 

 


Experimentation


Responsive Design Grid Experiment - https://codepen.io/alex-william-ziet-ra-nicholls/pen/oQvPKp 



References

References
Anon., n.d. [Online] 
Available at: https://github.com 
Anon., n.d. Functional Testing. [Online] 
Available at: softwaretestingfundamentals.com/functional-testing/
Anon., n.d. Responsive vs Adaptive Design. [Online] 
Available at: http://mediumwell.com/responsive-adaptive-mobile/
Anon., n.d. Usability Testing. [Online] 
Available at: What is usability testing? | Experience UXhttps://www.experienceux.co.uk/faqs/what-is-usability-testing/
DeMatas, D., Nov 22 2017. Why Website Color Schemes Matter & How to Use Them Right. [Online] 
Available at: https://www.x-cart.com/blog/website-color-schemes.html
Erik, P. W., Jan 8, 2018. Top 5 Web Development Frameworks in 2018. [Online] 
Available at: https://www.youtube.com/watch?v=cPPNb3iQc9E
GCFLearnFree.org, Aug 10, 2016. Beginning Graphic Design: Typography. [Online] 
Available at: https://www.youtube.com/watch?v=sByzHoiYFX0
Techquickie, Jun 6, 2017. What is SEO (Search Engine Optimization)?. [Online] 
Available at: https://www.youtube.com/watch?v=COL_qPL5xsg
tricks, C., n.d. pure css horizontal scrolling. [Online] 
Available at: https://css-tricks.com/pure-css-horizontal-scrolling/ 




Bibliography 


CSS Grid Layout 


https://www.youtube.com/watch?v=g13dSerjICk&t=447s

Jan 16, 2018 by Academind


https://www.youtube.com/watch?v=jScmyS_Iy04
Oct 15, 2017 by Chris Hawkes


https://www.youtube.com/watch?v=O3fVMm-Ef0Y
Improving Web and Mobile App Typography - 5 basic guidelines
Jan 3, 2017 by Sketch Together





Appendices 

Apendix 1 – High fedility wireframes for pc and mobile



Appendix 3 – Low fedility wireframes for pc and mobile

 
  

Testing and Evaluation 
-----------------------

Testing	Expectation	Outcome	Problem(s)	Solution(s)	Comments
Code

HTML Validation Screenshot
 

CSS Validation Screenshot
 	HTML, CSS meets W3C validation standards. No syntax errors and quality of code is at a high standard.	HTML and CSS code is valid and meets all the necessary requirements set out by W3C standards. 
	None	None	No Errors where found for both HTML and CSS validation. 
Website and Page Performance	Fast and interactive. Quick loading speeds and response times. 	Meets expectations 	None	None	Page speeds considerably efficient and fast for a beta version assessed by refreshing webpage within browser
Responsive – Is it Multi Device Compatible
Phone

 

Tablet


 

Desktop

 	The layout works on all devices from phones to tablets to Laptops and PCs	Very responsive and exceeded expectations. 	None	None	Media Queries working fine and adapting to screen sizes. 
Browser Compatibility 
Chrome
 

Safari 
 

Firefox 

 

	Fully compatible for all new and old browsers
	UI functions and appears the same in all browsers. 
	None	None	Compatible
Website Features 
Performance

Menu

 

Scroll-btn 
 
	All features work within the website.  	Menu works and responds as expected. 
Scroll button and form not working.  Problem Scroll button does not seem to respond when ‘clicked’. 
Form and ‘Send’ button also is not functioning.   	Problem –When examining the code, a potential cause of the problem is that the “menu” div is interfering with the functions of the “scroll-btn” and the “c-form” form.	Solution 1 - 
One solution is to adjust the css properties for the menu so that it does not disrupt the interactions with the other functions in the website. 
Solution 2 – Create js functions for form and scroll button. 	This problem was recently discovered and noticeable when adding in the full-screen menu. Before the website is launched this needs to be addressed. 
Navigation

Menu 

 
Top-bar

 
	Links all work and user can easily navigate through site. 	Menu responds and works. 	Only flaw to this navigation menu is the full-screen menu does not disappear when user clicks on page link.	Solution – add JavaScript ‘css styling’ and ‘event Listener’ to the function for the menu to hide after user clicks on one of the page links  	The menu worked well but is still a work in progress and the problems identified in this test plan  will need to be resolved before the launch.
Form testing
 	Contact Form works and responds to user input
	Contact Form does appear and is responsive, but user cannot type in the inputs. 	Due to the menu the form does not work at the moment. 	Solution – Menu needs to be fixed in order for the form to respond to user input. 
	Form responds to screen size.
Form does not have validation. This would need to be addressed before the launch. 


Stress and endurance behaviour – Can the website handle its workload	Website can achieve the set workload aimed. 	Expectation achieved. 	None	None	No comments
Content 	Images, Videos, Text should be working. 
•	There should be no grammar and spelling mistakes within the work.
•	Information should be understandable
•	Images should be positioned in the same place as the UI design with the proper sizes. 
•	Text/fonts should be responsive and readable. 	Expectation achieved.	None 	None	No comments
Design Elements	All design elements should match the visual style guide and UI design.
 	Expectation achieved	None	None	No comments


Hardcopies of these documents can be found in the Assignment/Docs Folder

Screenshots can be found in Assignment/Screenshots

Github Repo - 

