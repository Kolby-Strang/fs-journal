# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > abstraction, encapsulation, inheritance, and polymorphism

02. How does `export` differ from `export default`?
  
  > While export can export classes and multiple values, export default exports one value

03. What is Encapsulation?
  
  > Encapsulation is when data/methods are wrapped behind different files and classes to protect and manage that data

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > Proxy objects can capture requests to get or set its objects properties and refuse/mutate them or give valuable debug data

05. What the difference between a `class` and an instance of a `class`?
  
  > a class is a type of object that can be created and lays the groundwork for how that object will operate, and an instance of that class is an actual implementation of the class

06. What is a computed Property?
  
  > A property that has to be computed like a getter method

07. What is the purpose of the `MVC` pattern?
  
  > To keep data the user should not have access to behind multiple layers of controller and service files so that nothing can access sensitive info but the program you write. Also to make code more readable and organized

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > The controller communicates user input to services and also updates the view

09. What is the job of the `Service` in `MVC`?
  
  > the service changes data in the model

10. What is the job of the `Model` in `MVC`?
  
  > To hold any data the program will use
