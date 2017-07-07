# p5demo
## Welcome to the ReadMe for your first p5 demo project!

This gives you the two simple files that will let you test your coding knowledge practically with the associated tutorial series. 

### Goal: Draw cool stuff while learning about JS and Programming in General!

### Milestones: When you get to a stopping point, show me!

Here are some instructions for you as you proceed through the project:


### 0: Dario
  Hey, so here are some special instructions before you being working with this project/tutorial system:

  1: Install Visual Studio Code (VSCode for short)
  https://code.visualstudio.com/download

  2: Open VSCode (you might want to pin this to your task bar, this is going to be your #1 place to write code at least for a while)
  
  3: Hit Ctrl - ~
  You just opened the integrated terminal in VSCode. This is how you will install alot of coding related software and tools. 

  4: Install Git:
  https://git-scm.com/download/win

  5: 'Clone' the repo for the project starter kit that I made onto your machine:
  Side Note: Everything that looks like `this` is to be entered into the terminal.
  To clone the repo onto your machine:
  1: `cd` (this navigates you to your user directory)
  2: `git clone REPOURL` (the repo url in this case is: 
  https://github.com/WilliamTOliver/p5demo)
  3: `git checkout dario` I created a 'branch' or version of the files specifically for you, though all files on your machine now, are yours. This is where I might add things if you come into some trouble and need any help specific to you and not to anyone approaching these files.
  4: Create a GitHub account (github.com) and email me your username so I can add you as a contributor on the project. This will let you commit up and share things, possibly with me, possibly with Lauren.   5: that's all for now.

### 1: When Setting Up
  First clone the files on your machine:
  `git clone REPOURL`
  The URL is located in the URL bar in your browser or in the bar that appears when you click clone/download on the main page of the repo.
  
  For this kind of project (p5JS) that's about it.
  
  All you need to do from there is:
  
  From your file manager, within this project's folder open index.html in Chrome.
  
  It will display whatever you have written in scetch.js. (your first time it should show nothing)

  As we did with the Polymer Project, the process of testing your code is - write, save, reload the browser, repeat...



### 2: When Starting a Project
  So you are sitting down to start a project, here are the steps you should follow:

  Open the project folder in VS Code (open VSCode, file-openfolder, click on the project folder)
  
  Open the integrated terminal: ctrl ~ (FROM HERE ON `txt that looks like this` is meant to be typed in the terminal)
  
  Check which branch you are on: `git checkout`
  
  Switch to the "blank" branch I created for you: `git checkout blank`
  
  Create a branch for your project `git checkout -b BRANCHNAME` 
  
  Push the branch to the repo, so it knows what you are doing and where you are doing things: `git push --set-upstream origin BRANCHNAME`
  
  You are ready to get to work!

### 3: When Finished with a Project:
 
  First check what branch you are on: `git checkout` (change to/create the right branch if you are on the wrong branch)
  
  Second: Commit your code: `git commit -a -m 'YOURMESSAGE'`

  Third: Push your code: `git push`
  
  Fourth: Merge your code to the master branch `git checkout master` & `git push`
  
  Fifth: Get set up for the next project `git checkout blank`

### 4: If you messed up and changed things on the wrong branch:
  First: Breathe!

  Second: switch to the correct branch: `git checkout BRANCHNAME`
  
  Third: commit your changes `git commit -a -m 'YOURMESSAGE'`
  
  Fourth: push `git push`
  
  Fifth: Ensure that the original (WRONG) branch is corrected to its intended state. In VS Code you can (once gitcheckouted back ot the bad branch) see the pending changes on the left in the git pannel (branch looking thing, should have a number-badge if there are uncommitted changes)
  
  Sixth: Problems? Google it or grab me : )
