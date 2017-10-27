# Mobile First - Code 301, Day 3

**Author**: Nick Gibson and Catherine Looper

**Version**: 1.3.0

## Overview

Our goal is to use jQuery to dynamically render the content based on user input by making modifications to the provided starter code.

Our goal is to use jQuery to create a dynamic site that renders all article elements using an article template that sources data from a separate blogArticles.js file. Our goal is to refactor for loops into forEach loops.

Our goal is to create a responsive web site that changes when the viewport is at a certain width, in order to maximum user experience on mobile and desktop devices. Our design had to match comp images provided to us.

## Getting Started
Load the index.html from the root directory.

A user must create an Article Constructor function to be populated with the rawData properties using contextual this. A user must use jQuery traversal and setter methods to fill in the current template clone with values of the properties of this particular Article instance. A user must link to blogArticles.js to populate the article template.

Ideally, a user would not have to build this app on their own machine. They can just access it once it is deployed on the web via a URL in their browser, and the product will display and respond to the user's viewport.

## Architecture
To build this app, we used the jQuery library to create an article template to populate our app with data sourced from our data file.

We approached this design with a mobile first mindset. Then we used media queries to adjust the design for viewports wider than 640px. We are using HTML and CSS, as well as normalize.css and the icomoon hamburger menu icon.

## Change Log
10-26-17 9:00AM - We started working on the lab and created our directory structure with Catherine as driver and Nick G as navigator. We then completed the TODO on the article.js file and the first few TODOs in the index.html and articleView.js file.

10-26-17 10:00AM - We then switched to Nick G as driver and Catherine as navigator and completed the set up of the author and category filters.

10-26-17 11:20AM - We then switched to Catherine as driver and Nick G as navigator to complete the remaining TODO items and update the README.

## Credits and Collaborations
* Code Fellows - https://www.codefellows.org/
* normalize.css - https://necolas.github.io/normalize.css/
* icomoon - https://icomoon.io/
* jQuery - https://jquery.com/
