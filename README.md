# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

You will notice there are several JavaScript files being brought into the index.html file. Each of those files contain JavaScript problems you need to solve. If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.

_*forEach()* method doesn’t actually return anything (undefined). It simply calls a provided function on each element in your array. This callback is allowed to mutate the calling array._

_*map()* method will also call a provided function on every element in the array. The difference is that map() utilizes return values and actually returns a new Array of the same size._

2. What is the difference between a function and a method?
   _Method : Method is a function when object is associated with it._
   _Function: In JavaScript there is always a default global object. Therefore when global/window object is associated with it, it is function._

3. What is closure?

_A closure is a feature in JavaScript where an inner function has access to the outer (enclosing) function’s variables — a scope chain._
_The closure has three scope chains:_

- _It has access to its own scope — variables defined between its curly brackets_
- _It has access to the outer function’s variables_
- _It has access to the global variables_

4. Describe the four rules of the 'this' keyword.

- _*Implicit Binding* - Implicit binding occurs when dot notation is used to invoke a function. In implicit binding, whatever is to the left of the dot becomes the context for this in the function._

- _*Explicit Binding* - Explicit binding of this occurs when .call(), .apply(), or .bind() are used on a function.We call these explicit because you are explicitly passing in a this context to call() or apply(). _

- _*New Binding* - Whenever we use constructor function, this reffers to a specific instance of the object that is created and returned by the constructor function._

- _*Global/Deafult Binding* - Global binding refers to how this is the global context whenever a function is invoked without any of the other rules mentioned above. If we aren't using a dot and we aren't using call(), apply(), or bind(), our this will be our global object._

5. Why do we need super() in an extended class?
   _The super() is used to access and call functions on an object's parent. When used in a constructor, the super keyword appears alone and must be used before the this keyword is used. _

### Git Set up

- [ ] Fork the project into your GitHub user account
- [ ] Clone the forked project into a directory on your machine
- [ ] Create a pull request before you start working on the project requirements. You will continuously push your updates throughout the project.
- [ ] You are now ready to build this project with your preferred IDE

## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays

Test your knowledge of objects and arrays.

- [ ] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started. Read the instructions carefully!

## Task 2: Functions

This challenge takes a look at callbacks and closures as well as scope.

- [ ] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes

Create constructors, bind methods, and create cuboids in this prototypes challenge.

- [ ] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes

Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.

- [ ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
