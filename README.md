# Yummy Blog


View the live site [here](https://yummy-blog-b6c8aefad68f.herokuapp.com/)


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

      * [Homepage](#homepage)

      * [Search Bar](#search-bar)

      * [Collapsing Nav Bar](#nav-bar)

      * [User login](#user-login)

      * [Meal Planner](#meal-planner)

   * [Future Features](#future-features)

* [Technologies Used](#technologies-used)

* [Testing](#testing)

     * [Responsiveness](#responsiveness)

     * [Lighthouse Results](#lighthouse-results)

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

This program is developed to demonstrate CRUD implementation paired with competency in python and django, and is purely for educational purposes.


## User Experience


### Project Goals


As the site owner, I want the program to:

* Provide information on recipes.

* Be easy to navigate.

* Allow a user to create a log in and profile.

* Allow signed in users to create, update and delete recipes.

* Allow the user to search for a recipe by keyword.


### User Stories


All user stories are available to view [here](https://github.com/users/DaniCarmo/projects/2) on Github. This project was developed following agile principles. Employing the agile methodology enabled me to meticulously map out the website's features by crafting user stories, each of which came with defined acceptance criteria and tasks.

![screenshot of user stories](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/user-stories.png?raw=true)

The project employed the "MoSCoW" technique to effectively categorize and prioritize its features and requirements based on their importance. "MoSCoW" stands for "Must have, Should have, Could have, and Won't have," with each category contributing to the organization and prioritization of features. This approach acts as a guiding principle for the development process, ensuring that the most crucial elements are addressed as a top priority.

![screenshot of kanban](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/kanban.png?raw=true)


### Database Schema


Basic ERD for the site and how user interacts with pages:

![screenshot of ERD](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/ERD.png?raw=true)


### Wireframes


Desktop:
![screenshot pc home](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/pc-home.png?raw=true)

![screenshot pc recipes](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/pc-recipes.png?raw=true)


Tablet:

![screenshot tablet home](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/tablet-home.png?raw=true)

![screenshot tablet recipes](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/tablet-recipes.png?raw=true)


Mobile:

![screenshot mobile home](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/mobile-home.png?raw=true)

![screenshot mobile recipes](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/design/mobile-recipes.png?raw=true)


### Color Scheme & Typography

Throughout the website the main color themes are black and white which provide a sophisticated and modern look, and this is then paired with soft pastel pinks and lilac purple. These soft, pastel hues introduce a touch of femininity and warmth to the design. They offer a delicate contrast to the starkness of black, evoking feelings of fun and charm. The combination of black with pastel pink and purple creates a striking contrast that immediately grabs attention. This stark juxtaposition adds depth and visual interest to the design, ensuring that key elements stand out while maintaining an overall harmonious balance.

![colors](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/screenshots/colors.png?raw=true)

The black and white backdrop of food is repeated and this creates a funky and fresh vibe to the site as it provides a fun backdrop to the simplicity of the rest of the site.

![background](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/images/background2.png?raw=true)

Protest Riot: This edgy and unconventional typeface is chosen for headings and the logo to inject a sense of fun and creativity into the design. Its unique strokes and angles stand out, making a bold statement and grabbing the viewer's attention instantly.

Roboto: For all other text, I opted for Roboto for its clean and modern appearance. Its simplicity ensures readability while maintaining a cohesive look with Protest Riot. Roboto's versatility allows it to complement the design without overshadowing the distinctive elements of Protest Riot.

![fonts](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/responsive/ipad.mini.png?raw=true)

## Features


### Existing Features


#### Homepage


The Main Menu serves as the navigational hub of our website, offering users easy access to various sections and features some of the latest recipes uplaoded. From here, users can explore different categories, access their profile settings, or navigate to specific pages within the site. It provides a centralized and intuitive way for users to move around the platform and find what they're looking for efficiently.

![screenshot homepage](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/responsive/ipad.air.png?raw=true)


#### Search Bar


The Search Bar is a powerful and convenient tool designed to help users quickly find specific recipes within the website, enhancing the user experience. It's a contributive feature that promotes discoverability and encourages users to explore the content available on the platform.

![screenshot search bar](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/screenshots/search%20bar.png?raw=true)

For example:

![screenshot search results](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/screenshots/search%20results.png?raw=true)


#### Collapsing Navbar


Yummy Blog features a collapsible navigation bar to ensure optimal user experience across various devices and screen sizes. When viewed on smaller screens, such as mobile devices or tablets, the navigation bar automatically collapses to conserve space and maintain usability.

![screenshot nav bar](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/screenshots/navbar.png?raw=true)

![screenshot nav bar collapsed](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/screenshots/navbar-collapse.png?raw=true)


#### User Login


User Login is a crucial component that enables users to access personalized features and content on our website. By logging in, users can add, delete and update recipes, create meal plans, and view other recipes uplaoded by other users. This enhances the overall user experience by providing a seamless and tailored interaction tailored to each individual user.

![screenshot login](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/screenshots/sign.in.png?raw=true)

![screenshot sign up](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/screenshots/register.png?raw=true)

![screenshot add](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/screenshots/add-new.png?raw=true)

Non users or those who do not own the recipes, do not have the options to edit or delete recipes, but they can still view and search for recipes. There are no Edit or Delete buttons as shown below:

Non user or a user who did not upload this recipe:

![non user](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/screenshots/non%20user.png?raw=true)

A user logged in and who uploaded this recipe:

![user](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/screenshots/user%20admin.png?raw=true)


#### Meal Planner


The Meal Planner is a valuable tool designed to simplify the meal planning process for users. Users can create personalized meal plans based on their dietary preferences, nutritional goals, and schedule. It offers a convenient way to organize meals for the week and enhances user engagement.

![screenshot meal planner](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/screenshots/planner-meals.png?raw=true)


### Future Features


Features to be implemented may include:

* Allowing logged in users to leave a comment under recipes and vice versa allow recipe/blog owners to respond to or delete comments on their recipes.

* Make it possible for users to upload step-by-step videos of creating their meals.


## Technologies used


* [Bootstrap](https://www.bootstrapcdn.com/)

   * For adding responsive styling to the site.

* [Python](https://www.python.org/)

   * Used to provide functionality to the site.

* [Django](https://www.djangoproject.com/)

   * For user-friendly features and allowed me to build a blog website from scratch.

* [Visual Studios](https://visualstudio.microsoft.com/vs/community/)

   * Used to create the code and content for the repository.

* [Github](https://github.com/)

   * Used to host the repository.

* [Wireframe.cc](https://wireframe.cc/).

   * To create the wireframes and design at planning stage.

* [Quickbase](https://www.quickbase.com/).

   * Used to create a database schema during planning stage.

* [Cloudinary](https://cloudinary.com/).

   * Used to store static files and images.

* [Heroku](https://dashboard.heroku.com/apps).

   * The hosting provider used.

* [Cloudinary](https://cloudinary.com/).

   * Used to store static files and images.

## Testing


### Responsiveness


The site pages have been tested on various screen sizes to ensure that the content is responsive and all screenshots can be viewed [here](https://github.com/DaniCarmo/Yummy-Blog-p4/tree/main/static/responsive)

The code has been tested using:

1. [W3 HTML validator](https://validator.w3.org/)

![html test](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/testing/html.check.png?raw=true)


2. [W3 CSS validator](https://jigsaw.w3.org/css-validator/)

![css test](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/testing/css.check.png?raw=true)


3. [jshint](https://jshint.com/)

![javascript test](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/testing/js.check.png?raw=true)
 

4. [CI Python Linter](https://pep8ci.herokuapp.com/)

![python test](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/testing/python.check.png?raw=true)


The code was also checked throughout the project where errors showed up on Visual Studios regarding lines too long and white space trailing, and these were fixed as they arose. 


### Lighthouse Results

* Home page:

![lighthouse home](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/testing/home.png?raw=true)

* Recipes page:

![lighthouse recipes](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/testing/recipes.png?raw=true)

* Sign in page:

![lighthouse sign in](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/testing/new.png?raw=true)

* Profile page:

![lighthouse profile](https://github.com/DaniCarmo/Yummy-Blog-p4/blob/main/static/testing/profile.png?raw=true)


### Manual Testing


Ran each test mentioned in the table below multiple times and each action executes as intended, providing confirmation of successful user story requirements and actions. 

| Test                                                          | Action                                                                                                                                                                                                     | Expectation                                                                                                                                                                                             | Result     |
| ------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| Navigate to the website's homepage                            | Click on logo or on Home on navbar                                                                                                                                                                         | User is directed to home page                                                                                                                                                                           | Successful |
| Navigate to recipes page                                      | Click on Recipes on navbar                                                                                                                                                                                 | User is directed to recipes page                                                                                                                                                                        | Successful |
| Navigate to profile page                                      | Only logged in users can see their profile page and a Profile option on nav bar; click on Profile on the nav bar.                                                                                          | Logged in users are brough to their profile page, and user is brought to their profile page with bio and uploaded recipes                                                                               | Successful |
| Sign-up/Register                                              | Click on Register on nav bar                                                                                                                                                                               | User is directed to sign-up page                                                                                                                                                                        | Successful |
| Login                                                         | Click on Login on nav bar                                                                                                                                                                                  | User is directed to sign-in/login page                                                                                                                                                                  | Successful |
| Edit or Delete a recipe - user/owner                          | As a logged in user on my own recipe - I click on the edit button and the edit page pops up for me to edit and save or I can click on Dlete button and a warning shows to confirm deletion before I commit | Logged in users can edit their own recipes                                                                                                                                                              | Successful |
| Edit or Delete a recipe - logged in user but not recipe owner | As a logged in user on someone else's recipe - I click on a recipe card                                                                                                                                    | No option to edit or delete recipe - only logged in users can edit their own recipes                                                                                                                    | Successful |
| Edit or Delete a recipe - non user                            | View a recipe not logged in - I click on a recipe card for more info                                                                                                                                       | No option to edit or delete recipe - only logged in users can edit their own recipes                                                                                                                    | Successful |
| Logout                                                        | As a logged in user I click on Logout on the nav bar and then confirm sign out                                                                                                                             | Logout option appears when clicked on nav bar and warning shows to confirm if user wants to log out or not, user then proceeds and is logged out of their account                                       | Successful |
| Recipe Cards                                                  | Click on recipe card on home page or recipe page                                                                                                                                                           | Full recipe page is brought up with all recipe details to view                                                                                                                                          | Successful |
| Search Bar                                                    | Add "Asian" to search bar and click search.                                                                                                                                                                | All recipes under cuisine "Asian" appear for me to view                                                                                                                                                 | Successful |
| Search Bar                                                    | Add "beef" to search bar and click search.                                                                                                                                                                 | All recipes with "beef" appear for me to view                                                                                                                                                           | Successful |
| Menu Planner view                                             | As a logged in user I navigate to my profile, click on Meals and then click on my chosen day of the week and add meals                                                                                     | User is brought to their monthly meal planner with days of the week and dates for the current month, user can click on any day to view daily planner                                                    | Successful |
| Menu Planner add                                              | As a logged in user I navigate to my profile, click on Meals and then click on my chosen day of the week and add meals                                                                                     | Within the meal planner user is presented with options for "light bites", "dinner" and "dessert" that will appear as suggestions as well as the search bar so user can search and add meals to that day | Successful |
| Add a recipe - logged in                                      | Click on New on nav bar                                                                                                                                                                                    | As a logged in user I am brough to the Add New page and can enter details and click save, recipe is now available to view by all on site                                                                | Successful |
| Add a recipe - not loggin in                                  | Click on New on nav bar                                                                                                                                                                                    | As a non-logged in user I am brought to Register/Sign-up page                                                                                                                                           | Successful |


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

1. Create a Heroku account.

2. Sign up with a student account for credits. (optional)

3. Once logged in, select create a new app.

4. Select an app name and region EU.

5. Select deployment method as connect to github.

6. Find the desired repo from your github.

7. Enable automatic deploys and select the main branch.

8. In the settings tab select reveal config vars and Input the required hidden variables.

9. Select nodejs and python as the buildpack.

10. Deploy and once built you will see a notice on Heroku that build was successful and you click on Open App to view the live site.


## Credits


* I used a Django playlist on YouTube[this video series](https://www.youtube.com/watch?v=sBjbty691eI&list=PLXuTq6OsqZjbCSfiLNb2f1FOs8viArjWy) from a Code Institute alumni to get an idea of how to implement the CRUD functionality for a recipe blog.

* Followed tips and troubleshooting throughout the project on Stackoverflow [stackoverflow](https://stackoverflow.blog/) and Python.org [python-org](https://www.python.org/).

* Got the recipes from [BBC Good Food](https://www.bbcgoodfood.com) and [Simply Recipes](https://www.simplyrecipes.com).

* I used ChatGBT [chat-gbt](https://chat.openai.com/) to assist with coming up with intro text on the home page and chef quotes.