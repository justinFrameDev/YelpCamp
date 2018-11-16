#YelpCamp v8

#Add Mongoose
* install and configure
* setup campground model
* use model inside of routes

#Show Page
* Review RESTful routes 
* add description to campground model
* show db.collection()
* Add a show route/template


RESTFULL ROUTES

NAME      url       verb  description
==============================================
INDEX     /dogs     GET   DISPLAY a list of dogs
NEW       /dogs/new GET   Displays form to make a new dog
CREATE    /dogs     POST  Add new dog to DB
SHOW      /dogs/:id GET   Shows info about one dog

==============================================
INDEX   /camgrounds
NEW     /campgrounds/new
CREATE  /campgrounds
SHOW    /campgrounds/:id

NEW     /campgrounds/:id/comments/new   GET
Create  /campgrounds/:id/comments       POST


#Add Seeds file
* Add a seeds.js file
* Run the seeds file every time the server starts
* 
#Add the comment model
* Make errors go away!
* display comments on show page
* 
#Comment New/Create
* Discuss nested routes
* Add the new comment and create routes 
* Add the new comment form

##Add User Model
* install all packages needed for auth
* Define User model

##Auth Part 1
* Install Packages
* Define User Model

##Auth Part 2
* Configure passport
* Add register routes
* Add register form

##Auth Part 3
* Add login routes
* Add login form

##Auth Part 4
* Add logout route
* Prevent User from adding a comment if not signed in
* Show/hide auth links correctly

##Auth Part 5
* Show/hide auth links in navbar correctly

#Refactor routes
* Use express to refactor all routes

##Users + Comments
* Associate users + comments
* Save author's name to a comment automatically
* 
##Users + Campgrounds
* prevent an unauthenticated user from creating a campground
* Save username+id to newly created campground

#Deleting Campgrounds
* Add Destroy route
* Add Delete Button

#Authorization
* User can only edit his/her campgrounds
* User can only delete his/her campgrounds
* Hide/Show edit and delete buttons
* 
#Editing Campgrounds
* Add Method-override
* Add edit Route for campgrounds
* Add link to edit page
* Add update route 
* Fix $set problem

#Deleting Cmapgrounds
* Add Destroy Route
* Add Delete Button

#Authorization
* User can only edit his/her campgrounds
* User can only delete his/her campgrounds
* Hide/show edit and delete buttons

#Editing Comments
* Add Edit route for comments
* add edit button 
* Add update route

#Deleting Comments
*Add Destroy route
*Add Destroy button

#Authorization Part 2: Comments
* User can only edit his/her comments
* User can only delete his/her comments
* Hide/Show edit and delete buttons
* Refactor middleware

# Adding Flash!
* Demo working version
* Install and configure
* Add bootstrap alerts to header