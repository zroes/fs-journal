# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, const, and var
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
"A function is a reusable set of statements to perform a task or calculate a value. Functions can be passed one or more values and can return a value at the end of their execution."
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
SOLID is an acronym that stands for five key design principles: single responsibility principle, open-closed principle, Liskov substitution principle, interface segregation principle, and dependency inversion principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
2, because array indexing starts at 0 and increments by 1
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if (this) {
  do that
}
```
**7.** In the `for loop` below, what is the name of the piece that belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {}
  //...
```
<!-- enter you answer in the space below -->
```
it can be called the final expression, or the iterator.
i++ or ++i would both work to increment by 1. 
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document object model, HTML
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Language syntax (parsing rules, keywords, control flow, object literal initialization, ...)
Error handling mechanisms (throw, try...catch, ability to create user-defined Error types)
Types (boolean, number, string, function, object, ...)
A prototype-based inheritance mechanism
Built-in objects and functions, including JSON, Math, Array methods, parseInt, decodeURI, etc.
Strict mode
A module system
Basic memory model
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are used when creating a function, while arugments are what actually get passed into the function.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
primitive values are simple data types that hold a single value, such as "a string" or 5. 
A reference value is more advanced, something like and Object or an Array that is a container
for multiple values (either primitve or reference)
```