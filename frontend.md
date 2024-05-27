What does it mean to lint a code?it means to have a set rules of structures to highlight the issues within your code, weather it is syntax or undeclared variables bug, it will handle that for you by pointing at it. 
We have to ways to do that:
1. Passive: done by taking a piece of code, and manually running it through a tool to identify potential issues. Either by running the file using the command line, or copying your code and pasting it in a specific linter tool. Examples for this can be: JSON Formatter to validate a JSON data structure

2. Active: this can be done by running a monitor tool that is constantly checking the file that your working on in order to spot inconsistencies and possible errors. You can achieve this by adding a lint as a plug-in in your favorite code editor! :). 
Examples for an active one can be:
- Pycodestyle for python 
- ESLint for JS 

Now back to learning using asking questions method (Active recall), look at these 3 questions:
### What ES6 is? :
The Seconed major revision of JS, It's ECMAScript 2015 which is also known as ES6 and ECMAScript 6.
### New features introduced in ES6? :
It's supported from various browsers since 2017, however it is not supported in Internet Explorer. 
### The difference between a constant and a variable? :
let makes you declare a variable, const used to declare a constant. However, keep in mind that Constants are similar to let variables, except that the value cannot be changed. 

## Arrow functions
It's a short way to type a JS function, without including return, parenthesis, and the word function. However they have important features you need to keep in mind:
- They're not hoisted: you need to declare the function before using it. 
- They don't have thier own "this" and they're not suitable for dealing with objects methods. 
- You can only omit the return keyword and the curly brackets if the function is a single statement.
 Which is better, const or var? 
Const, because functions expressions always return constant values. 