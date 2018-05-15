# Project Overview

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

You are **responsible** for scheduling time with your squad to seek approval for each deliverable by the end of the corresponding day, excluding `Saturday` and `Sunday`.

|  Day | Deliverable | Status
|---|---| ---|
|May 1st| Project Description | completed
|May 8th| Wireframes / Priority Matrix / Functional Components | completed
|May 15th| External API(s) Decision / Core Application Structure (HTML, CSS, etc.) | completed
|May 22nd| Minimal Viable Product | Incomplete
|May 29th| Styling / Bug Fixes | Incomplete


## Project Description

Alfred Web Design Studio is a web development company based in New York delivering WordPress tailored solutions(custom themes, plugins, widgets, responsive design) url[ https://alfredwebdesign.com/] , the mission of this project is to upgrade the functionality of the site and bring it back to life, the idea is to implement what was learned in the JSD class to add interactivity and ajax navigation across the site as well as a portfolio filtering system and improve the show case of products. 

The website is built on WordPress, all content is available on json format so it expands the way content is displayed retrieving the information the site already have. the wp rest api has been installed to make all the content in the site available on JSON format by accesing the endpoints https://alfredwebdesign.com/wp-json/wp/v2/pages/, the new features for the site would be to change the body of the page using json when you click on any of the pages, the front page specifically will have a custom slideshow that we will be building from scratch to display featured content on the site, a portfolio filtering system, a mobile dynamic display and a step by step contact form.

## Wireframes

Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe.
Home Page Blocks and Areas
<img src="https://www.alfredwebdesign.com/alfred/wp-content/uploads/2018/05/Alfred-Web-Design-Home-Page-Mockup.png">

Featured Content Slider and fields 
<img src="https://www.alfredwebdesign.com/alfred/wp-content/uploads/2018/05/slider-component.jpg">

Main Content Area to replace its content dynamically using ajax
<img src="https://www.alfredwebdesign.com/alfred/wp-content/uploads/2018/05/main-container.jpg">

Main Content Area inner page with sidebar
<img src="https://www.alfredwebdesign.com/alfred/wp-content/uploads/2018/05/main-content-inner-page.jpg">

Contact Form with Multiple steps

Step 1
<img src="https://www.alfredwebdesign.com/alfred/wp-content/uploads/2018/05/contact-us-step-1.jpg">


Step 2
<img src="https://www.alfredwebdesign.com/alfred/wp-content/uploads/2018/05/contact-us-step-2.jpg">


Step 3
<img src="https://www.alfredwebdesign.com/alfred/wp-content/uploads/2018/05/contact-us-step-3.jpg">


Step 4
<img src="https://www.alfredwebdesign.com/alfred/wp-content/uploads/2018/05/contact-us-step-4.jpg">


Step 5
<img src="https://www.alfredwebdesign.com/alfred/wp-content/uploads/2018/05/contact-us-step-5.jpg">


## Priority Matrix

## Functional Components

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Defining Areas to be refactored and functionality logic | A | 4hrs| 2hrs | 2hrs |
| Creating Mockups of the pages in the site | A | 2hrs| 2hrs | 2hrs |
| Rafactoring HTML/CSS | A | 6hrs| 0hrs | 0hrs |
| Setting up end points using the wp rest api | B | 3hrs| 2hrs | 2hrs |
| Update Theme to support new functionalities and modify files | B | 4hrs| 0hrs | 0hrs |
| Create custom ajax loading functionality for the site navigation | B | 4hrs| 0hrs | 0hrs |
| Create Product filtering functionality for the products page | B | 4hrs| 0hrs | 0hrs |
| Create Dynamic Contact form with step by step transitions | B | 4hrs| 0hrs | 0hrs |
| Total Time | / | 19hrs| 19hrs | 19hrs |  

### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP 

- Find and use external api 
- Render data on page 
- Allow user to choose favorites 
- Save their choices in firebase

#### PostMVP 

- Add user auth

## Functional Components

Based on the initial logic defined in the previous  phases section try and breakdown the logic further into functional components, and by that we mean functions.  Does your logic indicate that code could be encapsulated for the purpose of reusablility.  Once a function has been defined it can then be incorporated into a class as a method. 

Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. 

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Adding Form | H | 3hrs| 3.5hrs | 3.5hrs |
| Working with API | H | 3hrs| 2.5hrs | 2.5hrs |
| Total | H | 6hrs| 5hrs | 5hrs |

## Helper Functions
Helper functions should be generic enought that they can be reused in other applications. Use this section to document all helper functions that fall into this category.

| Function | Description | 
| --- | :---: |  
| Capitalize | This will capitalize the first letter in a string of text | 

## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description  

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## jQuery Discoveries
 Use this section to list some, but not all, of the jQuery methods and\or functionality discovered while working on this project.

## Change Log
 Use this section to document what changes were made and the reasoning behind those changes.  

## Issues and Resolutions
 Use this section to list of all major issues encountered and their resolution.

#### SAMPLE.....
**ERROR**: app.js:34 Uncaught SyntaxError: Unexpected identifier                                
**RESOLUTION**: Missing comma after first object in sources {} object
