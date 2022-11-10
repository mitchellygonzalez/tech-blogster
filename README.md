# tech-blogster


#### Github link:  https://github.com/mitchellygonzalez/tech-blogster

## Table of Contents
* [Description](#description)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Installation](#installation)
* [Usage](#usage)
* [Contributors](#contributors)
* [Technology Used](#technology-used)
* [Questions](#questions)
 
## Description
Tech-Blogster is a Model-View-Controller based application that is deployed onto heroku. Users can create an account, publish their blog posts, and comment on other blog post 
as well. Similar to a Wordpress site, developers can use it to cover topics that are popular or may be of interest to other developers.


## User Story
AS A developer who writes about tech

I WANT a CMS-style blog site

SO THAT I can publish articles, blog posts, and my thoughts and opinions


## Acceptance Criteria
GIVEN a CMS-style blog site

WHEN I visit the site for the first time

THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in

WHEN I click on the homepage option

THEN I am taken to the homepage

WHEN I click on any other links in the navigation

THEN I am prompted to either sign up or sign in

WHEN I choose to sign up

THEN I am prompted to create a username and password

WHEN I click on the sign-up button

THEN my user credentials are saved and I am logged into the site

WHEN I revisit the site at a later time and choose to sign in

THEN I am prompted to enter my username and password

WHEN I am signed in to the site

THEN I see navigation links for the homepage, the dashboard, and the option to log out

WHEN I click on the homepage option in the navigation

THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created

WHEN I click on an existing blog post

THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment

WHEN I enter a comment and click on the submit button while signed in

THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created

WHEN I click on the dashboard option in the navigation

THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post

WHEN I click on the button to add a new blog post

THEN I am prompted to enter both a title and contents for my blog post

WHEN I click on the button to create a new blog post

THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post

WHEN I click on one of my existing posts in the dashboard

THEN I am able to delete or update my post and taken back to an updated dashboard

WHEN I click on the logout option in the navigation

THEN I am signed out of the site

WHEN I am idle on the site for more than a set time

THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments

## Installation
1. Clone this code onto a local repository
2. Create a heroku account and add JawsDB
3. Install Express.js 
4. JawsDB was used as a database. It can be used to run your heroku app by following the steps on this website: 
  - https://coding-boot-camp.github.io/full-stack/heroku/deploy-with-heroku-and-mysql
  


## Usage
1. To get MySQL started, run the following on your terminal and enter your login credentials: mysql -u root -p
2. Create an "env" file in the root of the project, and in it enter the following inside the quotation marks. Remember to add this "env" file into your .gitignore file so that your credentials do not get uploaded onto a public network. 
  - DB_NAME = ecommerce_db
  - DB_USER = 'root'
  - DB_PW = 'your MySQL password'
3. You can install Express.js by running the following on your terminal: npm install express --save
4. You should hide the following in your .gitignore if you're planning to push to github: node_mudules, DS_Store, .env
5. Before heading to the website, run one the following in your terminal to start the project: npm start
6. Now that you have the site running, you may now create an account to login, create a post, comment on a post, and edit it or delete it. You may also comment as well. 


## Contributors
To contribute, you may clone this repo, and create a new branch to add your code. 

## Technology Used
- Handlebars.js
- Sequelize
- MySQL
- JawsDB
- Express.js
- express-session
- connect-session-sequelize
- Heroku
- JS
- JSON

## Questions
Any questions, contact me via email: mitchellygonzalez@gmail.com
