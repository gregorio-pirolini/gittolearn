# to learn git

## Home

git --version

## Intro

## Git Get Started

### Configure Git

git config --global user.name "w3schools-test"  
git config --global user.email "test@w3schools.com"

### Creating Git Folder

mkdir myproject
cd myproject
git init

## Git New Files

git status

## Git Staging Environment

git add --all  
or  
git add -A

## Git Commit

git commit -m "First release of Hello World"

### Git Commit without Stage

git commit -a -m "Updated index.html with a new line"

**Warning:** Skipping the Staging Environment is not generally recommended.

Skipping the stage step can sometimes make you include unwanted changes.

git status --short

### Git Commit Log

git log

## Git Help

git _command_ -help - See all the available options for the specific command  
git help --all - See all possible commands  
**Warning:** This will display a very long list of commands  
Note: If you find yourself stuck in the list view, SHIFT + G to jump the end of the list, then q to exit the view.

## Git Branch

In Git, a branch is a new/separate version of the main repository.

### New Git Branch

git branch _hello-world-images_  
creates new branch

git branch  
_lists branches_  
git checkout hello-world-images  
moves to hello-world-images branch
