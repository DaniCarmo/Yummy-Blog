# Yummy Blog 
  

View the live site [here](https://yummy-blog-b6c8aefad68f.herokuapp.com/). 


![screenshot of the live site](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/responsive/ipad.air.png?raw=true) 
  

## Contents 


* [Purpose](#purpose) 

* [User Experience](#user-experience) 

   * [Project Goals](#project-goals) 

   * [User Stories](#user-stories) 

   * [Database Schema](#database-schema) 

   * [Wireframes](#wireframes) 

   * [Color Scheme and Typography](#color-scheme) 

* [Features](#features) 

   * [Existing Features](#existing-features) 

      * [Homepage](#the-main-menu) 

      * [The Search Bar](#the-search-bar) 

      * [User login](#user login) 

      * [Meal Planner](#meal-planner) 

      * [Recipe Updates](#recipe-updates) 

   * [Future Features](#future-features) 

* [Technologies Used](#technologies-used) 

* [Testing](#testing) 

     * [Manual Testing](#manual-testing) 

     * [Automated Testing](#automated-testing) 

     * [Unfixed Bugs](#unfixed-bugs) 

* [Deployment](#deployment) 

   * [Deploying the App](#deploying-the-app) 

   * [Forking The Repository](#forking-the-repository) 

   * [Cloning The Repository](#cloning-the-repository) 

   * [Heroku](#heroku) 

* [Credits](#credits) 



## Purpose


This recipe blog is created for users to view and share recipes, with various cuisine options to chose from as well as a calorie count per meal, all users can search and create a daily meal plan using Yummy Blog. Owners of recipes can also edit and delete their own recipes and update their profile account with a bio and photograph.

This program is developed to demonstrate competency in python, django and sql and is purely for educational purposes.


## User Experience


### Project Goals


As the site owner, I want the program to:

* Provide information on recipes.

* Be easy to navigate.

* Allow a user to create a log in and profile.

* Allow signed in users to create, update and delete recipes.

* Allow the user to search for a recipe by keyword.


### User Stories


All user stories are available to view [here](https://github.com/users/DaniCarmo/projects/2) on Github.

(https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/user-stories.png?raw=true)


(https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/kanban.png?raw=true)


### Database Schema


Basic ERD for the site and how user interacts with pages:

![screenshot of ERD](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/ERD.png?raw=true)


### Wireframes


Desktop:

(https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/pc-home.png?raw=true)

(https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/pc-recipes.png?raw=true)


Tablet:

(https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/tablet-home.png?raw=true)

(https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/tablet-recipes.png?raw=true)


Mobile:

(https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/mobile-home.png?raw=true)

(https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/mobile-recipes.png?raw=true)


### Color Scheme & Typography


## Features


### Existing Features


#### The Main Menu


#### The Search Bar


#### User Login


#### Meal Planner


#### Recipe Updates


### Future Features


Features to be implemented may include:

* Allowing logged in users to leave a comment under recipes and vice versa allow recipe/blog owners to respond to or delete comments on their recipes.

*Make it possible for users to upload step-by-step videos of creating their meals.


## Technologies used


* [Bootstrap](https://www.bootstrapcdn.com/)

   *For adding responsive styling to the site.

* [Python](https://www.python.org/)

   * Used to provide functionality to the site.

* [Visual Studios](https://visualstudio.microsoft.com/vs/community/)

   * Used to create the code and content for the repository.

* [Github](https://github.com/)

   * Used to host the repository.

* [Wireframe.cc](https://wireframe.cc/).

   * To create the wireframes and design at planning stage.

* [Quickbase](https://www.quickbase.com/).

   * Used to create a database schema during planning stage.


## Testing


The site pages have been tested on various screen sizes to ensure that the content is responsive and all screenshots can be viewed [here](https://github.com/DaniCarmo/Yummy-Blog-p4/tree/main/static/responsive)

The code has been tested using:

1. W3 HTML validator(https://validator.w3.org/)

![html test](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/testing/html.check.png?raw=true)


2. W3 CSS validator(https://jigsaw.w3.org/css-validator/)

![css test](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/testing/css.check.png?raw=true)


3. [jshint](https://jshint.com/)

![javascript test](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/testing/js.check.png?raw=true)
 

4. [Code Institute CI Python Linter (Pep8)](https://pep8ci.herokuapp.com/) and no errors found.

![python test](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/testing/python.check.png?raw=true)


The code was also checked throughout the project where errors showed up on Visual Studios regarding lines too long and white space trailing, and these were fixed as they arose. 


### Manual Testing


Ran each test mentioned in the table below multiple times and each action executes as intended, providing confirmation of successful user story requirements and actions. 


### Automated Testing
 

### Unfixed Bugs


There are no unfixed bugs recorded.


## Deployment


### Forking The Repository


This can be done to create a copy of the repository. The copy can be viewed and edited without affecting the original repository.

To fork the repository through GitHub, take the following steps:

1. In the relevant github repository, click on the "fork" tab in the top right corner.

2. Click on "create fork" to fork the repository.


### Cloning The Repository  

To clone the repository through GitHub:

1. In the repository, select the "code" tab located just above the list of files and next to the GitHub button.

2. Ensure HTTPS is selected in the dropdown menu.

3. Copy the URL under HTTPS.

4. Open Git Bash in your IDE of choice.

5. Change the current working directory to the location where you want the cloned directory to be created.

6. Type "git clone" and paste the URL that was copied from the repository.

7. Press the "enter" key to create the clone.


### Heroku


To deploy the project through Heroku I followed these steps: 

Create a Heroku account.

Sign up with a student account for credits. (optional)

Once logged in, select create a new app.

Select an app name and region EU.

Select deployment method as connect to github.

Find the desired repo from your github.

Enable automatic deploys and select the main branch.

In the settings tab select reveal config vars and Input the required hidden variables.

Select nodejs and python as the buildpack.

Deploy and once built you will see a notice on Heroku that build was successful and you click on “Open App” to view the live site.


## Credits


* I used a Django playlist on YouTube[this video series](https://www.youtube.com/watch?v=sBjbty691eI&list=PLXuTq6OsqZjbCSfiLNb2f1FOs8viArjWy) from a Code Institute alumni to get an idea of how to implement the CRUD functionality for a recipe blog.

* Followed tips and troubleshooting throughout the project on Stackoverflow [stackoverflow](https://stackoverflow.blog/) and Python.org [python-org](https://www.python.org/).

* Got the recipes from [BBC Good Food](https://www.bbcgoodfood.com) and [Simply Recipes](https://www.simplyrecipes.com).

* I used ChatGBT [chat-gbt](https://chat.openai.com/) to assist with coming up with intro text on the home page and chef quotes.