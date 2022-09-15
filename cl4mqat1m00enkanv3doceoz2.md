## Javascript Naming Convention for Beginners

## Introduction

![thinking](https://giphy.com/gifs/sesame-street-fma-elmo-8acGIeFnqLA7S)

Programming languages may have different naming conventions in declaring variables, classes, or file names. Typically, you would see Python programs use snake case when declaring variables while JavaScript programs use camel case. If you are fairly new to Javascript, this article may serve as a guideline in terms of naming your variables, classes, and even file names. 

Here are some things you might need to know before proceeding:

- JavaScript variables are case-sensitive. Meaning having a variable name called *firstName* and *firstname* are two different variables.
- Difference between functions and methods: Functions are independent while methods belong to a class or object.

- Different case styles:
> Pascal case (e.g. FirstName) <br>
> Camel case (e.g. firstName) <br>
> Snake case (e.g. first_name) <br>
> Kebab case (e.g. first-name)

## Variables
Variables are the most common things you may see when writing a program in JavaScript and they are written in **camelCase**.

```javascript
let firstName = "Juan"
let age = 18
let isWorking = true
let studentInfo = {
  firstName: "Juan"
}
let fruits = ["Orange", "Apple"]
```

## Boolean
Booleans are data types that can be stored in a variable and they are written in **camelCase** as well. It is a good practice to add keywords such as *is*, *are*, and *has* to distinguish boolean variables.
 
```javascript
let isEnabled = true
let hasName = false
let areAvailable = true
```

## Class
Classes in JavaScript use the pascal case naming convention.

```javascript
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }
}
```

## Functions and Methods
Functions and methods follow the camel case style too but it is a good practice to use verbs when naming them to indicate what they do.

```javascript
function getFullName() { 
  return "Juan Carlo"
}

// method
class Person {
  saySomething() { 
    console.log("Something") 
  }
}
```

## Constants
Constants are normally written in uppercase and use snake case when you need to separate words. 
```javascript
const NAME = "Juan";
const FIRST_NAME = "Juan";
const FULL_NAME = {
  firstName: "Juan",
  lastName: "Carlo"
}
```

## Global Variables
Global variables normally use uppercase for **immutable** variables and camel case **mutable** variables. 
```javascript
const INITIAL_STATE = {
  isLoading: false,
  error: null
  items: []
}
const context = {}
```

> A mutable object is an object whose state can be modified after it is created.

>Immutables are the objects whose state cannot be changed once the object is created.

>%[https://developer.mozilla.org/en-US/docs/Glossary/Mutable]

## File Names
While other naming conventions in JavaScript primarily use the camel case, it is recommended to use the snake case or kebab case when naming files. Just remember to be consistent throughout the entire project when you pick one. 
```javascript
main-file.js
home-page-component.js
```

## Conclusion

Remember, these are just guidelines to help you have a cleaner and more readable code. You may still do whatever you want when naming variables but it is recommended to stick to a strict coding style so others may read your code easier. 

Thank you for reading and happy coding!
