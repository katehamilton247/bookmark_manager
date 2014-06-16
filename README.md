bookmark_manager
================

This bookmark manager is a website which maintains a collection of tagged links. It allows users to save and search useful websites.  Similar products currently on the market are pineapple.io and delicious.com.


Specifications
==============

The website will have the following options:

- Show a list of links from the database 
- Add new links 
- Add tags to the links 
- Filter links by a tag
- Show the list of available tags on the homepage
- Move the form to add a link to its own route
- Add user_id to tags and links, and display who the link or tag was submitted by.
- Allow the user to add a link to favourites (this will be a many-to-many relationship)
- Display how many users favourited the link
- Create a user profile page that will show the links they submitted, tags they created and their favourites.
- Display the link to the user's profile at the top of the page if the user is logged in
- Implement forgotten password functionality
- Redirect the user with a flash message if a logged in user tries to sign up or sign in
- Send a welcome email when the user signs up
- Create validations for all models:
  - email must have the correct format (see an example in Datamapper Validations)
  - email and password must be present
  - link must have a title and a url
  - tag must have some text
- Add a description property to the link.
- Add a username to the User model, so that username instead of an email was shown next to the link.


Experience level on completion
==============================

This project was completed in the sixth week of a coding bootcamp run by Makers Academy, London.  Prior to the course I had no coding experience.


Skills developed
================

- Integration testing
- Capybara
- Relational databases
- Security considerations
- Front-end development
- Sinatra
- Rspec



