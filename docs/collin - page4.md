---
title: Making Code Snippets
---
1. Go to settings and then select "configure user snippets". 
2. Code snippets are usually scoped by programming language so search for your desired language in the search bar to add a snippet for it. Or optionally, you can make your snippet global for use in all languages by making a global snippet file.
3. Fill out your code snippets in this JSON format (see picture below). The "prefix" value is the specific key combination that will trigger the intellisense shortcut menu. The "body" value is what will be inserted if the user clicks the snippet shortcut in the intellisense menu. The "description" value is used to describe the purpose of the snippet in intellisense. 
4. Fill out the "prefix" value with your desired trigger words for the snippet. They must be an array of strings. 
5. Fill out the "body" value with the code snippet that will actually be inserted when clicked.
6. Use place holder values of $2, $1, $1 so that users can tab through places in the snippet where they can enter values upon snippet insertion. The colons after these placeholder values set the default value if the user chooses not to enter a value. 
7. Fill out a snippet description that will be displayed in intellisense shortcut menu. 

