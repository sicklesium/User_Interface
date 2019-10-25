# User_Interface__Art_App

**Pitch:** As an artist I want to be able to show off my work. I'm a photographer and I have a lot of amazing foodie pics I'd like to share with potential clients, but I need a site that is more professional than Instagram in order to do so.

**MVP:** User can visit site and see artists photos laid out in a grid , artist can create, read update photos. No ability to upload one's own photos.
MVP Features Breakdown:

This app contains two user types. An artist (who has the ability to log in) and a single user (no need to log in so no need for user data to be persisted on this user type) who can view an artist's portfolio.

* Login Page - After a user logs in, they'll be directed their portfolio page where they can create a "post". Each post needs to have an image, description and and upvote section to it. (Think instagram for artists).
* Navigation - Navigation is present on all pages, Users should know what page is active by clicking on a nav link and activating their tab.
* Create Post Page - Allows a user to come in and create a post of their artwork (no need to upload photos for MVP). Stretch goals will include image uploading and the use of Cloudinary API etc.
* Edit Post Page - User can edit their post descriptions.
* Home Page for non-logged in users - Navigating to the home page Users can view posts of different artists laid out in a single format. Users can click on a single post to read more of the description etc.

**Stretch Goal:** Build an image uploader into the site to allow users the ability to upload their own assets. (This will require some work with a package called Drop Zone and a service called cloudinary).
