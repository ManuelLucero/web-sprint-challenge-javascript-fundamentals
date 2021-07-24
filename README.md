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

Map can be used to return an array that contains the results of calling a specific function on each element of an original array. This is useful when we need to uniformly modify every element in an array or modify a set of values that are common within an array, and then store these new results (such as applying a universal holiday discount on all items in an inventory list and then pushing their respective price changes into a new list for comparison); reduce can be utilized to execute a specific function that collectively acts on the collection of elements in an array as a whole, returning a single value (e.g. to find the sum of a specific numerical property in a data-set (such as all of my debit transactions this month), reduce can add each value within a list and give the final summation); and, filter returns an entirely new array that contains each element of an original array that satisfies a specified condition.

2. Explain the difference between a callback and a higher order function.

A callback is what occurs when a call to a function is nested or otherwise contained in a block where the higher order function is not local, and the solution nonetheless wishes to invoke the function despite being outside of its immediate scope.

3. Explain what a closure is.

A closure is when a nested function calls for access to something within the scope of the outer function which contains it. Essentially, it's the inheritance of the scope of a parent function.

4. Describe the four principles of the 'this' keyword.
 1) Whenever a funtion is global, the value of `this` inside of that function is essentially the entire browser or environment or "window"; 2) whenever a function is called using dot notation, the object before that dot is `this`; 3) when creating a 'constructor' function, `this` is used to refer to the object being created and returned by calling the 'constructor' function; and, 4) whenever .call() or .apply() is called, `this` becomes locally defined.

5. Why do we need super() in an extended class?
    Because super() is required whenever we need to access a parent class (or the 'constructor' of that class, rather) and its properties/methods. It's basically a forcefully logical invocation of inheritance.
    
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

