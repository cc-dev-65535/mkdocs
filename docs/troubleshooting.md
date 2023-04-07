---
title: Troubleshooting Common Issues
---
## I set the wrong key binding and want to revert it
From the keyboard shortcut editor you can filter all key bindings by user-defined bindings to list all the key bindings that you have personally set. *Click* the **...** icon in the top right of the shortcut editor and then click **Show User Keybindings** from the dropdown menu to see the list. From this list you can *right click* on any user-defined key binding and then remove or reset it. Alternatively, you can edit the JSON file with key bindings directly following *method 2* of the *Setting Custom Key Bindings* section.

## I want to remove a code snippet as it is no longer useful
Follow the steps in the *Making Code Snippets* section to open the snippet file for your desired programming language and simply delete the snippet (a JSON object) you added from this file.

## I can't find my desired key binding through the keyboard shortcut editor
If the search function in the keyboard shortcut editor is not helpful for finding a key binding then you should refer to *method 2* of the *Setting Custom Key Bindings* section. This method will work for all possible key bindings in VS Code provided you know what command identifiers to enter into the *command* clause.

## I accidentally imported the wrong profile
You can always reset your current profile to the VS Code default profile through the same menu that you use for importing and exporting profiles.

## I set a key binding but it doesn't work
Ensure that your key binding does not conflict with a system-default key binding. If this is the case then using *method 2* of the *Setting Custom Key Bindings* section would allow you to override this default.
