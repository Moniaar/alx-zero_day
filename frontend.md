What does it mean to lint a code?it means to have a set rules of structures to highlight the issues within your code, weather it is syntax or undeclared variables bug, it will handle that for you by pointing at it. 
We have to ways to do that:
1. Passive: done by taking a piece of code, and manually running it through a tool to identify potential issues. Either by running the file using the command line, or copying your code and pasting it in a specific linter tool. Examples for this can be: JSON Formatter to validate a JSON data structure

2. Active: this can be done by running a monitor tool that is constantly checking the file that your working on in order to spot inconsistencies and possible errors. You can achieve this by adding a lint as a plug-in in your favorite code editor! :). 
Examples for an active one can be:
- Pycodestyle for python 
- ESLint for JS 
