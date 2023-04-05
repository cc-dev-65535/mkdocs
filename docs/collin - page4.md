---
title: Making Code Snippets
---
## Overview
Code Snippets are blocks of pre-written code that can be conveniently inserted into code through the IntelliSense shortcut menu. This section will detail how to create your own custom code snippet for any programming language you use in VS Code.  

## Steps
1. Go to settings and then select "configure user snippets".  
2. Code snippets are usually scoped by programming language so search for your desired programming language in the search bar to add a snippet for it. Or optionally, you can make your snippet global for use in all languages by making a entry into a global snippet file.
3. Fill out your code snippets in the following JSON format (see picture below). The "prefix" value is the specific key combination that will trigger the intellisense shortcut menu. The "body" value is what will be inserted if the user clicks the snippet shortcut in the IntelliSense menu. The "description" value is used to describe the purpose of the snippet in IntelliSense. 
4. Fill out the "prefix" value with your desired trigger words for the snippet. This must be an array of strings that will cause the snippet shortcut to be displayed using IntelliSense. 
5. Fill out the "body" value with the code snippet that will be inserted when the snippet shortcut is clicked.
6. Within, the "body" value, use place holder values of $2, $1, $1 so that users can tab through places in the snippet where they can enter values upon snippet insertion. The colons after these placeholder values set the default value if the user chooses not to enter a value.
7. Fill out a snippet description that will be displayed in the IntelliSense shortcut menu when the snippet shortcut is displayed. 

## Conclusion
You have learned how to create your own code snippets in VS Code. Take a look at some of the other instruction guides to further improve your productivity in VS Code.