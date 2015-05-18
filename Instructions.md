## Welcome to Turing

Rubymine is extremely customizable. Here is some things that we think you should know,
and some settings that we think will be helpful to you.



The following can be accessed by pressing command + ',' (command and comma at the same time)

### Keymap

The default is set to **atom_turing**. There is a cheat sheet in the README to help get you started.
There is also an option for sublime text, and Pivotal Labs IDE. These can be copied and customized if you so choose.
 
The following are from the atom cheat-sheet

##### General
 - Toggle command palette isn't set on Rubymine (not sure if it has a similar feature)
 - Toggle comment works
 - Show auto-completions pops up automatically. This does work, but pops up docs as well
 
##### Find
 - Find in file works
 - Find next works
 - Find in project (pops up find in path) which i think will work
 - Use selection for find works
 
#####  View / window manipulation
 - Toggle sidebar works
 - Toggle fullscreen does not work
 - Split pane works
 - Focus pane works
 
##### File Navigation
 - Toggle file finder doesn't work
 - Go to line works
 - Go to symbol works
 - Previous / next file does not work
 - Set bookmark doesn't work
 - Go to next bookmark doesn't work
 
##### Folding
 - Fold / unfold current code block doesn't work
 - Fold / unfold all doesn't work (opens maintenance)
 - Fold at depth doesn't work
 
##### Word manipulation
 - Transpose characters doesn't work
 - no backspace
 - option + delete (deletes backwards one word)
 
##### Line manipulation
 - indent / outdent works
 - command + enter (opens space after)  **these are backwards**
 - command + shift + enter (opens space after)
 - delete current line works
 - move current line up / down works
 - duplicate current line works
 - join current and next lines works
 
##### Selection
 - select current word works
 - select current line works
 - select to beginning / end of word works
 - select to first / last character of line works
 - select to top / bottom doesn't work (moves to top / bottom only)
 


### Editor

**changelog**

Editor / general

*  enabled - change font-size(zoom) -- pinching your track-pad will make your font bigger
*  enabled - drag and drop in editor
*  enabled - allow placement of caret inside tabs

Editor / tabs

*  enabled - hide file extension in tabs

Editor / colors & fonts

*  enabled - Darcula scheme (other schemes can be chosen here as well)

Editor / code style

*  enabled - scheme pivotal

Editor / code style / ruby

*  enabled - align multiline list items
*  enabled - align right parts of assignments or hashes
*  enabled - spaces around curly braces

Editor / inspections / ruby / naming conventions

*  disabled - instance method naming convention


### Version control

Once you begin to use Github, you can enter your username and password to access information about your project.

### Languages & Frameworks

Here you will find Ruby SDK & gems. 
 **default Ruby set to version 2.2.1**
 
  This is where you will see the installed versions of Ruby on your computer.




#### Changing global / project defaults

When you first start Rubymine you have the option to open a new project, a folder, or to clone something from version control ( github ).

There is also a configure tab on the bottom. **This is where you change global defaults**

Any changes you make when you have a project open will affect that project **only**.

If you want to change your key bindings we would suggest that you first make a copy, and make changes there. This way if there is a problem you can easily switch back and start over.



 
#### The following are some things that you should know about testing.

If you attempt to run a test file from within Rubymine it will not be able to find file that you want to test.
This is because it searches from the directory that the test was ran from. Since you will be using 'require' this won't work. 

To fix this you need to select 'Edit configurations' from the 'Run' menu. You see the path to the **Working Directory** It will look like /Users/your_name/path/to/project/test

You need to delete the /test at the end so that Rubymine runs the tests from the root of the project. After
you run a test, there is also an option to make the tests auto-run when you change a file.

You can also click on the link for the error and it will take you right to the line in question.

Alternatively you can open a console by pressing 'function' + 'option' + F12
Here you can run individual tests, or a Rakefile.














