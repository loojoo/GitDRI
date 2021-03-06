# Configure Git

First, we're going to configure Git using the command line.  
_Make sure *Git* and is *Sublime Text 3* are installed on your computer. If not, click the following link for our [install instructions](https://github.com/GCDigitalFellows/installdri.github.io/blob/master/core.md)._  

####Open your terminal/bash.

Mac: press the space bar and the command key at the same time and type in "terminal."
Windows: launch the command prompt from the run window. 

####Type `git`.  
If you get a nice list of things, you're good to go. If not, click on the following link and install as per the directions: [http://git-scm.com/downloads](http://git-scm.com/downloads)

## Configuring Git on your computer

Type the following into your command line, filling in the sections for your username and email. These must correspond to the name and email you used to sign up for GitHub.

`git config --global user.name "John Doe"`

`git config --global user.email johndoe@example.com`

`git config --global core.editor "subl -n -w"`

You don't have to use Sublime as your text editor, but for simplicity and consistency, we are asking everyone to use Sublime as your editor this week. The `-n` prompts Sublime to open in a new window, and the `-w` prompts it to wait for the application to close.

If Sublime is not coming up as your defaul text editor and you are using a **Mac,** follow the instructions from our [install core] (https://github.com/GCDigitalFellows/installdri.github.io/blob/master/core.md).  
If you are using **Windows,** follow these instructions to [open Sublime Text from the command line using subl.exe](https://scotch.io/tutorials/open-sublime-text-from-the-command-line-using-subl-exe-windows).

To check your set-up, use:  
`git config --list`

You'll get something that looks like this:

`user.name=Superstar Git User`  
`user.email=gitsuperstar@gmail.com.`  
`color.ui=auto`  
`core.editor=subl -n -w`

___  
For more reading on `git config`, check out this [Git-SCM](https://git-scm.com/book/en/v2/
Getting-Started-First-Time-Git-Setup) tutorial, which was a helpful reference in the making of this resource.  

[<<<Conceptual overview](concept.md) - [Initialize Git>>>](gitinit.md)  
[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)
