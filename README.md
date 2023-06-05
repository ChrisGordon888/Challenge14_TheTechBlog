# Challenge14_TheTechBlog

## Description
This is the challenge14 project for UT Austin's Coding Bootcamp. The Tech Blog is a CMS-style blog site where developers can publish articles, blog posts, and share their thoughts and opinions.

## User Story
AS A developer who writes about tech,
I WANT a CMS-style blog site,
SO THAT I can publish articles, blog posts, and my thoughts and opinions.

## Features
- When visiting the site, users are presented with a homepage that includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in.
- On signing up, users are prompted to create a username and password. These user credentials are saved and the user is logged into the site.
- Returning users can choose to sign in by entering their username and password.
- When signed in to the site, users see navigation links for the homepage, the dashboard, and the option to log out.
- Users can click on an existing blog post and are then presented with the post title, contents, post creator’s username, and date created for that post, with the option to leave a comment.
- If users enter a comment and click on the submit button while signed in, the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created.
- In the dashboard, users are presented with any blog posts they have already created and the option to add a new blog post.
- Users can delete or update their existing posts via the dashboard.
- After being idle on the site for more than a set time, users can still view posts and comments but are prompted to log in again before they can add, update, or delete posts.

## Technologies Used

- Node.js
- Express.js
- MySQL
- Sequelize
- Handlebars.js
- Dotenv
- bcrypt
