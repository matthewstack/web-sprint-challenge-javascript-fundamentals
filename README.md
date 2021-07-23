# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

        .map - This allows you to manipulate data and return in in a new array.  You could use this to calculate population density of each state with using keys for state population and state area.

        .reduce - This allows you to multiply or add values from an array into a single value.  You could use this to add up the population of all the states and return the sum.

        .filter - This allows you to filter data by creating a condition for a key value that's true of false.  You could filter animal by species type and return a specific species of animal. 

2. Explain the difference between a callback and a higher order function.

        A callback function lets you pass a function into another function as an arguement.  Usually you put cb on the end of the function name for the parameter or just use callback. A higher order function is a function that can receive other functions as arguements (callback functions).

3. Explain what a closure is.

        Closure is when a nested function grabs a variable defined out of the nested function's scope.  It can grab this from an outer function, but not a nested inner function.

4. Describe the four principles of the 'this' keyword.

        If there is no context for 'this', it is window binding.  In the global object or the object within the window or browser. If strict mode is used, it will return undefined. 
        
        Implicit binding is only used with object methods.  It is the most common.  'this' refers to the left of the dot when the method is invoked. 

        Explicit binding uses .call, .apply or .bind. to explicitly state what keyword 'this" refers to. 
            .call - Immediately invokes the function and passes arguements one by one
            .apply - Also immediately invokes the function but pases the arguements as an array
            .bind - Passes the arguements one by one but does not invoke it.  It serves as a brand new function that can be invoked later.

        New binding - When a function is invoked with a new keyword inside of it, that function is bound to the new object created. 'This' refers to the newly constructed object.


5. Why do we need super() in an extended class?

        Super is used to call functions on the parent object. It abstracts object.create() and .call. Using extend alone would attach a child to the parent but not give access to anything within it.  

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

