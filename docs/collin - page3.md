---
title: Setting Custom Key Bindings
---
There are two methods for setting custom key bindings, the first method is more convenient but does not work for all possible key bindings. In those case, you should use method 2, which allows for maximum customization.

### Method 1
1. From the file, go to preferences and then keyboard shortcuts to get to the keyboard shortcut editor. 
2. Search for your desired key command by entering text into the search bar. You can also click the record keys button on the right hand side of the search bar to record your key strokes typed into the search bar.
3. Press pencil to edit the key binding for the entered key command. 
4. Enter your desired key binding in the popup and click enter. The entered key is now bound to the key command you searched for.

### Method 2
5. This method allows you to edit the key bindings directly from a JSON file that is loaded by VS Code. Click the “Open Keyboard Shortcuts(JSON)” icon from the very top right of the shortcut editor page. 
6. Write your key command bindings in this format (see pictur below).  “Key” will take the key you want to bind, “Command” will take the command that the key triggers, “When” is optional. 
7. use this picture as reference for what to enter when entering the “command” and “key” values in the above step. 
8. use the when clause to restrict when the key bindings is available within vs code, since the keybinding is globally available anywhere in the editor by default. The when clause must evaluate to a boolean, use this reference picture for some common when clause context references.

