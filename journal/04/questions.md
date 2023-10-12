# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > Synchronous code runs line by line never running two lines of code at once while asynchronous code can call functions and continue running the rest of the program while the async functions runs as well

02. What is an event listener?

  > An event listener is code that "listens" for an event to be fired and when it does runs the code assigned to it at initialization

03. What does *REST* stand for, and in simple terms what does it mean??

  > Representational State transfer, just saying that when data is accessed it is a representation of the state of the data in the api

04. What is a callback / higher order function?

  > a higher order function is a function that takes another function within its parameters

05. What is a `promise`? How do you capture an error from a `promise`?

  > A promise is a returned value that is promised to happen at some point, to properly capture these you need to await the function that returns the promise so that the code doesn't leave the network call behind

06. Name three processes used to make requests over `HTTP`?

  > get post put delete

07. What does the `API` acronym stand for?

  > Application Programming Interface

08. What must you do in order to `await` a promise inside of a function?

  > async the parent function

09. What is the purpose of encapsulation in programming?

  > To hide data from malicious users and so make groups of code the belongs together separate from the rest of the program 

10. What is `HTTP` response code for a successful request?

  > 200

11. What is a 400 error?

  > When a request to an api is bad, either returning nothing or accessing data without authorization a 400 type error will return
