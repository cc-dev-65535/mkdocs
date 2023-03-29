---
title: Setting Custom Key Bindings
---
Two different ways 
1. go to preferences -> keyboard shortcuts to get keyboard shortcut editor 
2. search for desired key command using search bar 
3. press pencil to edit key binding 
4. enter your desired key binding in the popup and click enter 
5. can’t find your keybinding in the editor? you can edit the keybindings from a json file. Open “open keyboard shortcuts(JSON)” icon from shortcut editor 
6. write your key command bindings in this format (see pic).  “key” will take the key you want to bind, “command” will take the command that the key triggers, “when” is optional. 
7. use this picture as reference for what to enter when entering the “command” and “key” values in the above step. 
8. use the when clause to restrict when the key bindings is available within vs code, since the keybinding is globally available anywhere in the editor by default. The when clause must evaluate to a boolean, use this reference picture for some common when clause context references.

