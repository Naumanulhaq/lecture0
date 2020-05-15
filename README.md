# Project 0

Web Programming with Python and JavaScript

I have chosen to design my personal webpage.

## Table of Content
- [Introduction](#Introduction)
- [Technologies](#Technologies)
- [Project description](#Project-description)

### Introduction:
It is the first training project of CS50’s Web development using Python and JavaScript. Being a beginner I have chosen to design my own webpage so I can practise and learn the skills those are necessary to clear the project 0 of CS50's Web.

This webdesign include:
- Four different .html pages, and it is possible to get from any page to any other page by following the hyperlinks.
- Ordered or unordered lists, a table, and an image.
- One stylesheet file.
- CSS properties, CSS selectors (#id and .class selector).
- Mobile-responsive @media query, about the styling changes for smaller screens.
- Bootstrap 4, taking advantage of Bootstrap component, and two Bootstrap columns for layout purposes using Bootstrap’s grid model.
- SCSS variable, SCSS nesting, and SCSS inheritance.

### Technologies:
Project is created with

- HTML 5
- JavaScript
- Bootstrap 4
- Sass

### Project description:

This portfolio has 4 html pages and a linked style.css.

  - [index.html](#home-page)
  - [blog.html](#blog)
  - [projects.html](#projects)
  - [contact.html](#contact)
  - style.css

All these .html pages are linked through hyperlinks.

# Home page:
Index.html is the main front page of this portfolio and it comprises of an image, text, hyperlinks and navigation tab.

#### Description:

- Each html page has a bootstrap library and a linked css file named **style.css**.
- I am managing my style.css file from style.scss, because I am using SCSS variables, nesting and inheritance. By typing ``` $ sass --watch style.scss:style.css ``` the watch flag keep telling Sass to watch your source code for changes and recompile CSS each time the file is saved.
- Code starts with a bootstrap 4 navigation bar (collapsible) with an unordered list of **Home, Blog, Projects and contact**. All of them are hyperlinked.
- Then the main content of the main page have a container with a class of a bootstrap that manages the content according to the screen size, that is large, medium and small screen size. Defining how many columns would it take out of 12 depending upon the screen sizes, that is called a bootstrap grid model. In this specific grid model, one class contains an image and the other one has text in it.
- To make the image responsive with respect to screen sizes I have defined a class named img-fluid.
- Inside text there are two hyperlinks; One is inside the text to navigate to another webpage (https://www.esri.com/en-us/what-is-gis/overview) that has information about the GIS. Just in case if someone doesn’t know what that term means and the other one navigates to the **projects** section inside my portfolio.

# Blog

Blog page contains the @media query, bootstrap 4 container and images.

#### Description:

Blog page has the same navigation bar and a container of bootstrap. The difference here is the *@media query*, which is used to improve the visualization (blog page contains multiple images and text associates with them) on small screen size devices on top of bootstrap 4. *@media query* is applied on two diferent screen sizes, that is, for small screen size```(max-width:768px)```and medium screen size ```(max-width:1000px) and (min-width:767px)```. In each *@media query*, every class of the blog with their respective images, their width's are kept fixed with the aligning property of *margin-right* and *margin-left*.

# Projects

Project page is the simplest one, and has a table of 3 rows and 2 columns, that has few sample projects with respect to their tools. The headers of each column are *Tools* and *Projects*. Second column (*Projects*) has number of ordered list that further has several list items and then few unordered list items; and the same structure goes for all the rows.

# Contact

Contact page has 3 boxes to take an input from the user:

- Name (input tag)
- Email (input tag)
- Message (textarea tag)

and a **Submit** button. Right now there is no connection with the server so the submit button will only make a pop up to appear on the screen with a message (Success! message sent successfully.) that will then fade away after 3 seconds with the help of a JavaScript library called  *JQuery*.
