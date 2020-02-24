# 08-lab: CSS animation and transition

- HTML: [validate your code](https://validator.w3.org/) every few changes

## Introduction

This week’s lab follows on from the lecture material covering animations. The [example repository](https://github.com/CTEC3905/08-lab) has a CSS keyframes animation example, and a branch with an image caption transition that fades up on hover.

## Task 1 - run the code and inspect it

Navigate to the folder where you store your CTEC3905 work, then:  
`git clone https://github.com/CTEC3905/08-lab.git`  
and change directory into the repo folder:  
`cd 08-lab`.

Create a new repository on your own GitHub account and copy its remote URL (from the green "Clone or Download" button) then on your command-line, change the remote to your new repo with

`git remote set-url origin YOUR_NEW_REPO` and check it with `git remote -v`.

You can then experiment with the code, make changes, and push your version to *your own account*.

## Task 2 - create your own animation

Create a simple animation of your own, using the advised properties (see the readme) and run it. You can make slideshows and other features using just CSS animations—next week some further examples will be made available.

## Task 3 - Checkout the other branch

**NOTE:** as explained last week, you may need to **quit Atom** before checking out a branch!

Make sure you have added and committed any changes you've made to your master branch.

Enter `git branch -a` to see the list of available branches.

Now enter `git checkout css-transition` to change to the othe3r branch.

Note how the **files in your local repository have changed**. Inspect the new code and run it in the browser. Use the guide in the readme file for this branch, and follow the links to get a Flickr API key, etc.

## 08 Lab learning outcomes

- understand processor load and animation
- understand the difference between animation and transition
- learn that animation on mobile devices needs thoughtful management
- create a CSS keyframes animation