# JAVASCRIPT TRIVIA

## Difference between a 'let' and a 'var':

**'let' has a block scope, doesn't get hoisted, and was introduced to Java in ES6 (2015)**
**'var' has a function scope, gets hoisted, and was in JS from the beginning**

## Difference between '==' and '===':

\*While both are comparison operators...
**'==' compares values**
**'===' compares values and types**

## Difference between 'let' and 'const':

**'let' can be reassigned**
**'const' can not be reassigned**

## Difference between 'undefined' and 'null':

**'undefined' is a value that is given to an intitialized variable without a value. Also, 'undefined' is simply recognized as an 'undefined' element**
**'null' is used when cleaning up a value. The developer will know it was set intentionally. Also, 'null' is recognized as an object**

## How can you improve a web page's performance?

**Optimise images - compression, minimize, both for better utility**
**Lazy load images - images take their time to load**
**Lazy load components - components take their time to load**
**Minify HTML, CSS, and JavaScript**
**Improve API response time**
**Utilise concurrent HTTP requests with Promise.all**

## What is 'this'

**'this' keyword is used to refer to the object that owns it**
**When alone, 'this' refers to the global object**
**In a function, 'this' refers to the global object as well, but in STRICT MODE, 'this' is undefined**

## Difference between Arrow and Regular functions:

**Arrow functions do not have their own 'this'**
**Arrow functions do not have the arguments object**

## Difference between function declaration and function expression

**Function Declaration: Starts with "function" then the function name (funcD), can be hoisted (declared before being called)**
**Function Expression: Anonymous function stored in a variable (funcE),behaves like a variable**

## What happens in a code block (setTimeout())?

**The event loop explains the layout of each event, line by line, and recognizes callbacks if it utilizes setTimeout()**
**The task queue sections cannot be pushed to the stack if anything is in the stack of the event loop**
**The web api section of the event loop must utilize the timer in the setTimeout() before pushing to the task queue, which will only be pushed to the stack of the event loop when all other commands are exectued**

