# SASS Personal Project

#### _By **Ginger Lee Kretschmer**_

## Description

**SASS Week 3:** A personal project that is an extension of a 2-day in-class project. This application redesigns and builds the Epicodus Learn How to Program landing page using SASS.

## Installation
To view this repository copy this [link](https://gingerlee.github.io/sass-week3/) into the browser of your choice.

### SASS 2-day Project Feedback
The past two days in class were spent planning out a redesign of the Learn How to Program landing page for the Epicodus curriculum.

**Day 1:** The first day was spent learning and using Sketch to wireframe two different versions of the site. I really enjoyed the process of wireframing and using sketch. We drew out two different versions of the site, in three different viewport sizes, desktop, tablet and mobile. One thing that I wish I spent more time on was planning out the ways we were specifically going to use SASS in our project in our planning document.

**Day 2:** The second day we spent coding out the new redesign. We used Materialize SASS and that was really great learning how to integrate a CSS SASS framework with our own SASS. We also utilized Grid CSS Layout, which was great to learn and see how a 2-dimensional system can be so powerful. We built our own loops to build our grid and the site turned out pretty great. I think a downfall was getting caught up in small content black holes, spending so much time looking for images and content that took away from the foundational work that we should have been focusing on first. Overall, I think SASS is great for organizing CSS code in to specific sections and files, it creates a great way to find what you are looking for. It also seems like if it is not set up properly it could be really hard to maintain, so taking time in the start and keeping good practices in organizing code into it's specific section/partial file is extremely important throughout the process.

### SASS Elements Used

| SASS Element      |   Description    |  Use in Application   |
|------------|-------------|--------------|
|**Nesting**|Sass will let you nest your CSS selectors in a way that follows the same visual hierarchy of your HTML. | We used nesting syntactical styling throughout our SCSS files. It makes our code much easier to read.|
| **Variables** | Just like javaScript, SASS utilizes variables that can be reused throughout the site to make changing content easier. | We made variables for colors and fonts.|
|**Mixins** | A mixin groups CSS declarations that are reuseable throughout the site. One can pass in values to make a mixin more flexible. A good use of a mixin is for vendor prefixes. | We used mixins for centering content on our site.|
|**Partials**| You can create partial Sass files that contain little snippets of CSS that you can include in other Sass files. This is a great way to modularize your CSS and help keep things easier to maintain. A partial is simply a Sass file named with a leading underscore. You might name it something like _partial.scss. The underscore lets Sass know that the file is only a partial file and that it should not be generated into a CSS file. Sass partials are used with the @import directive.| We created many SASS partials files that helped us clean up or SCSS code and separate out into our 7-1 file structure. It made our code easy to find and update and compartmentalize. It was great for organization.
|**Import** | Sass builds on top of the current CSS @import but instead of requiring an HTTP request, Sass will take the file that you want to import and combine it with the file you're importing into so you can serve a single CSS file to the web browser. | We were able to import various partial files that we creates, as well as the many partial files from the Materialize SASS framework we incorporated.|

### Changes for this personal project
Working alone today, I am excited to work in the console more and import my CSS code changes there to my stylesheet, it seems like a much faster process, and I plan to commit often to make sure nothing is lost. I am not sure how I will set up my grid system yet, either using Materialize or Grid layout. I also want to add in more graphics this time around.

### Technology Used
* HTML
* javaScript
* CSS
* SCSS
* SASS
* Materialize
* Sketch
