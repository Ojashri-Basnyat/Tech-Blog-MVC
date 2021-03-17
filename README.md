## Tech-Blog-MVC
My solution to Week 14 Challenge

## Deployed Heroku Link
https://tech-blog-mvc-ojashri.herokuapp.com


## User story

A CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other deevelopers' posts as well.

This site can publish articles, blog posts, and opinions.

GIVEN a CMS-style blog site
WHEN a developer or user, visit the site for the first time, THEN the developer or user is presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in.

WHEN the developer or user click on the homepage option, THEN the developer or user is taken to the homepage.

WHEN the developer or user click on any other links in the navigation, THEN the developer or user is prompted to either sign up or sign in.

WHEN the developer or user choose to sign up, THEN the developer or user is prompted to create a username and password.

WHEN the developer or user click on the sign-up button, THEN the developer or user credentials are saved and I am logged into the site.

WHEN the developer or user revisit the site at a later time and choose to sign in, THEN the developer or user is prompted to enter username and password.

WHEN the developer or user am signed in to the site, THEN the developer or user see navigation links for the homepage, the dashboard, and the option to log out.

WHEN the developer or user click on the homepage option in the navigation, THEN the developer or user is taken to the homepage and presented with existing blog posts that include the post title and the date created.

WHEN the developer or user click on an existing blog post, THEN the developer or user is presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment.

WHEN the developer or user enter a comment and click on the submit button while signed in, THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created.

WHEN the developer or user click on the dashboard option in the navigation, THEN the developer or user is taken to the dashboard and presented with any blog posts already created and the option to add a new blog post.

WHEN the developer or user click on the button to add a new blog post, THEN the developer or user is prompted to enter both a title and contents for my blog post.

WHEN the developer or user click on the button to create a new blog post, THEN the title and contents of the post are saved and the developer or user is taken back to an updated dashboard with new blog post.

WHEN the developer or user click on one of existing posts in the dashboard, THEN the developer or user is able to delete or update post and taken back to an updated dashboard.

WHEN the developer or user click on the logout option in the navigation, THEN the developer or user is signed out of the site.

WHEN the developer or user idle on the page for more than a set time, THEN the developer or user is automatically signed out of the site.  

## Installation
npm init
npm install

## Usage

Run the following command at the root of your project & answer the prompted questions:
mysql -u root -p
Enter password when prompted
source db/schema.sql
quit
npm run seed
npm start
npm run watch