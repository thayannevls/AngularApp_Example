# AngularApp_Example
Example of an Angular.js application.

### Directory Layout
Based on https://scotch.io/tutorials/angularjs-best-practices-directory-structure
```
  app/    --> AngularJs App
----- shared/   --> acts as reusable components or partials of our site
----- components/  --> each component is treated as a mini Angular app
---------- home/     --> Home Section
--------------- homeController.js
--------------- homeService.js
--------------- homeView.html
----- app.module.js  --> File that will handle the setup of your app
----- app.routes.js  --> File that will handle all the routes
assets/    --> Contain all the assets needed for your app that are not related your AngularJS code
----- img/      --> Images and icons for your app
----- css/      --> All styles and style related files (SCSS or LESS files)
----- js/       --> JavaScript files written for your app that are not for angular
----- libs/     --> Third-party libraries such as jQuery, Moment, Underscore, etc.
index.html  --> File that handle loading in all the libraries and Angular elements
```

