---
title: Setting Custom Key Bindings
---
There are two methods for setting custom key bindings, the first method is more convenient but does not work for all possible key bindings. In those case, you should use method 2, which allows for maximum customization. 
### Method 1
1. From the file, go to preferences and then keyboard shortcuts to get to the keyboard shortcut editor. 
![image](images/Capture3.PNG)
2. Search for your desired key command by entering text into the search bar. You can also click the record keys button on the right hand side of the search bar to record your key strokes typed into the search bar. 
3. Press pencil to edit the key binding for the entered key command. 
4. Enter your desired key binding in the popup and click enter. The entered key is now bound to the key command you searched for. 

### Method 2
1. This method allows you to edit the key bindings directly from a JSON file that is loaded by VS Code. Click the “Open Keyboard Shortcuts(JSON)” icon from the very top right of the shortcut editor page. 
2. Write your key command bindings in this JSON format (see picture below). In the object, “key” will take the key you want to bind, “command” will take the command that the key triggers, “when” sets the scope of the key binding while in VS Code and is optional. 
3. Use this picture as reference for common "key", "command", and "when" values to enter when filling in the JSON object values in the above step. 
4. The "when" value restricts when the key binding is available within VS Code, since the keybinding is globally available anywhere in the editor by default. The when clause must evaluate to a boolean.
