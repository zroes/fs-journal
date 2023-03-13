# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
abstraction, encapsulation, inheritance, and polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Hiding data and making it private to users, so that we as developers have
better control over how our programs are used
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility principle. Basically, a function should do one thing, 
a class should do one thing, each file should have its "one job" that it does.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is like the general form, for example a person. an Instance of a class
is like an individual.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object allows you to give access to the properties of another object,
but you can control how those properties are accessed and to what extent they
can be changed.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
In keeping with Single Responsibility, MVC divides up the work between different
files, so they are easier to write and debug. If something is wrong with data
in the appState, its likely an issue with the service. If something in the 
HTML isn't drawing right, the controller would be the first place to look.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller manipulates the page, it determines what gets drawn and when
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service controls the data in the appState
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model controls how data is organized, and works with the controller to 
display content on the page.
```
