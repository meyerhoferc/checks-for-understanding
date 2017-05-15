## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What is Webpack and why is it useful?

  Webpack is a node module that manages what static files are needed for a browser to render a page and creates a single file for the browser to digest. It's useful because it speeds up the browser rendering process and does pre-processing.

2. When do you want to use event delegation?
3. What's one difference between ES5 and ES6?

  Anonymous function syntax is now `() => {}` and automatically binds `this` to the current scope.

4. What's the deal with semi-colons in JavaScript?

  Semi-colons are there for the compiler. They are mostly optional because the compiler will inject them for the developer, but it could be good to insert them yourself for more complete control.

5. How are you using the MVC design pattern in your Quantified Self project?

  I'm using controllers to handle requests, models to interact with the database, and the views are represented as the JSON response sent by the API.

6. How do you execute raw SQL in node?

  Using Knex interface

7. What is CORS?

  CORS stands for Cross-Origin Resource Sharing and allows browsers to enforce same origin policy. This means that the Javascript can download data from an external server if the current page and the data come from the same origin.
  
8. What are some steps to avoid CORS?

  You can setup CORS permissions using an allowed-access header in the request to an external site.

#### Review  

9. Why do people say "HTTP is stateless"?

  HTTP is stateless, meaning that it doesn't track or manage state across the request/response cycle. One way this is managed is through the use of cookies / sessions, at least for small pieces of data we don't want to store in a database.

10. What is a RESTful API?

  A RESTful API means that the API was architected according to REST principles. REST stands for Representational State Transfer and means that the API has routes and controller-actions are made to convention for a resource.

11. What are some main characteristics of a team following an agile workflow?

  Following an agile workflow means that the developer frequently engages in reflection and adjustment of the code, both independently and with others on the team.

12. What are some advantages/disadvantages to using OAuth to authenticate a user?

  Advantages:
    * don't have to manage authentication as closely
    * user has fewer passwords to remember
    
  Disadvantages:
    * user may not have third party account to authenticate with
    * relying on third party service doesn't give developers as much control
  
