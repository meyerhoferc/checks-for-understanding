## Week Four - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

* What's the purpose of a project management tool?

  * allows developers and other team members to communicate their progress without constantly communicating
  * single place for canon of stories
  * good reference for project documentation

* What are the stages of a card when using Pivotal Tracker?

Unstarted -> Start -> Finish -> Deliver -> Accepted / Rejected

* What are the four types of cards available in Pivotal Tracker?

Feature, Bug, Chore, Release

* What's your favorite project management tool?

I like Pivotal Tracker because of all of the customization options and ability to import stories from a CSV. While I like how Waffle integrates with GitHub issues, I find PT to be more flexible.

* Why do we create staging environments?

Using staging environments allows us to test out what production will look/feel like and if the build renders appropriately from the static files to the database.

* What are the characteristics of a good README (in your opinion)?

  * describes purpose of appilcation / library
  * has code snippets
  * thorough instructions for install / run / config in different environments
  * has tips on errors / debugging common problems

* What's one main improvement you're going to make to your code regarding accessibility issues?
* What are some basic security concerns to be aware of when building applications?

  * user authentication / authorization
    * how passwords are stored
    * the steps for password changing / changing roles (from standard user to admin)
    * salting and hashing
    * permissions for multitenant appilcations
    
  * XSS
    * use a frameowrk that implements CORS well
    
  * mass assignment
    * use strong params
    * can even use GPG to sign params
    
  * SQL injection
    * use the `?` everywhere possible
    * don't do string interpolation in SQL queries

* Why is continuous integration helpful/important?

Allows us to check build and run tests in a variety of environments

* What are some continuous integration tools?

Travis, Jenkins, Puppet, Chef

#### Review  

* What are some characteristics of "good" git workflow?
* What are the four fundamental concepts of object oriented programming?
* What's a module in Ruby and what's the difference between a class and a module?
