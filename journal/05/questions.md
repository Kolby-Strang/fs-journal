# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > Create Read Update Destroy

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > create = post, read = get, update = put, destroy = delete

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > | ANSWER HERE |

04. Which two `HTTP` request types include a body?

  > put post

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > synchronous, asynchronous

06. What are the three types of data relationships? Provide an example of each.

  > one to one, where one strip of data is tied to one other strip of data and that is all, an example is an address where a street and city have a one to one relationship. One to many, where one strip of data is associated with many strips of data like comments on a youtube video. Many to many, where either strip of data could apply to many other things, like authors and books, many authors can write one book and many books may be written by one author

07. What is middleware?

  > Smaller programs that deal with functionality that the larger program should not have to deal with, conversion from json to object/error handling/authorization

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > Request, Response

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > add ?tag=winter to the end of the url and that value will be stored in request.query.tag = 'winter' if you need to pass and array use ?tag=winter&tag=anotherValue and this will be stored as request.query.tag = ['winter', 'anotherValue']

10. What is a ***virtual property***?

  > A virtual property is a property that is retrieved from other collections within the db, useful for pulling information from an property that only contains an id
