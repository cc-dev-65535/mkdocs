---
title: Making Code Snippets
---
1. Go to settings->configure user snippets 
2. code snippets can be scoped by language so search for your desired language in the search bar, or you can make your snippet global for use in all languages by making a global snippet file. 
3. Fill out your code snippets in this format (see pic). prefix is the typing that will trigger the intellisense shortcut menu. body is what will be inserted if the user desires this snippet. description is to guide the user as to the purpose of the snippet. 
4. Fill out prefix with your desired trigger words for the snippet. They must be an array of strings. 
5. Fill out body with the code snippet that will actually be inserted. 
6. Use place holder values of $2, $1, $1 so that users can tab through places in the snippet where they can enter values upon insertion. colons after these placeholder values show the default value if the user does not enter a value.
7. Fill out an interesting description that will be displayed in intellisense shortcut menu. 

