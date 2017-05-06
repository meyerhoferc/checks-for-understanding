## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?

Basic data structures and writing functions in JavaScript. I also really liked the testing part.

2. What are some tools to help debug JavaScript code?

better tests
browser: console.log() or debugger
node: pryjs, console.log()

3. What are some tools you need in order to unit test your JavaScript?

mocha, chai, exporting the function being tested

4. What is the syntax for invoking a function?

`functionName()`

5. What's the difference between `==` and `===` in JavaScript?

`==` does type conversions to check for equality while `===` does not

6. What's the difference between asynchronous and synchronous JavaScript? 

Asynchronous code is executed whenever JavaScript is ready for it. JS may go on to do other things and execute other code while waiting for something like an API call or a function to return. Asynchronous code isn't necessarily always going to execute in the same order without the structure of callbacks or promises. Synchronous JS is executed step-by-step, meaning some piece of code will not execute until the piece before it does.

7. What's a callback function and what are some reasons when we use/need callback functions?

A callback function is a function that takes data given to it and hopefully returns something to the function that called it. It's usually invoked in as a parameter within another function.

8. What's the biggest difference between a promise and a callback?

I'm not sure about this and am finding conflicting information on the Internet. 

9. How do we setup a route when creating an API with Node and Express?



10. What's `npm` and what do we use it for?

Node Package Manager manages packages and the development environment, similar to bundler in Ruby.

#### Review  
11. What's the MVC design pattern? Describe each part of MVC?
12. What is AJAX? What are some benefits of using AJAX?
13. What's a background worker? When would we want to use a background worker?
