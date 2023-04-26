# Set up new Git repository and create development branch for 'new-project'

Creating a new branch, committing changes, and pushing them to the repository

This guide will walk you through the process of creating a new branch, making changes, committing those changes, and pushing them to the repository using Git.

## Prerequisites

Before starting, you will need the following:

- A local Git installation
- Access to the repository on GitHub

###  Steps

Clone the repository to your local machine using the command: 
```
git clone https://github.com/oleksiihead/new-project
```
Navigate to the directory of the cloned repository
```
cd new-project
```
Create a new branch
```
git branch <branch name>.
```
Switch to the new branch 
```
checkout <branch name>.
```
Make the desired changes to the files in the project directory.

Add the all changes to the staging area
```
git add . 
```
or if you want to add specific files
```
git add <file name> .
```
Commit the changes with a commit message
```
git commit -m "Your commit message here".
```
Push the changes to the remote repository 
```
git push -u origin <branch name>.
```
If you want to merge the changes from your branch to the main branch, create a pull request and merge it through the GitHub interface.
