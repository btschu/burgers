# burgers_crud_mvc

# This is an example of MVC, not my work

## Objectives:

- Learn about MVC
- Understand the benefits of an MVC design pattern
- Learn how to structure applications

Download burgers here

## MVC

Developers who design frameworks have to make decisions about organizing code. One of the most popular patterns for organizing code is one known as MVC: Model-View-Controller.  Here's a basic breakdown of responsibilities:

## Model	
- May build database tables
- Handles logic that relies on data
- Interfaces with the database
## View	
- HTML page that gets served to the client
- May contain some logic to be handled by a template engine
## Controller	
- Receives incoming requests
- Minimal logic
- Calls on models to aggregate/process data
- Determines appropriate response

## Modularizing Application

Some web development frameworks combine everything into one large, potentially monstrous file. Imagine you're on a team with a dozen other developers—how easy will it be to collaborate in one giant file? Yikes! Using the MVC pattern allows us to outsource the different kinds of tasks to specific file locations. When we begin a Flask project, we will need to created files to play all of the necessary roles in a web application:

- Routes (expected requests)
- Functions associated with those routes (how our server responds)
- Database interaction through our Models (storing, retrieving data from database )
- Templates (what the user interacts with)
