# git-study

## Git - commands

`git status` - information about our local repository

`git add nameofFile.extension` - add file to the index

`git add .` - add all new files to index

`git stash` - add all modified files to a stack of unfinished changes in active branch

`git stash list` - allow to view the stack of active branch

`git stash apply` - give a chance to return old changes with stack to the working directory

`git stash apply --index` - return old changes with stack to the index or working directory

`git stash clear` - clear all changes of stack

`git stash apply idOfPoint` - returns changes from a specific point(idOfPoint) in stack  

`git stash apply idOfPoint --index` returns changes from a specific point (idOfPoint) including files of index


`git branch -a` - show all local and global branch  

`git branch` - show only local branch

`git branch nameOfNewBranch` - create new local branch

`git branch -d branch_name` - delete local branch

`git push origin --delete branch_name` - delete remote (global) branch on the server

`git push origin nameOfBranch` - send all change to the server

`git pull` - take all changes from the server to the local repositiry

`git chechout nameOfBranch` - change branch

`git init` - initialize a new local repository - as git-repository 

`git merge nameOfBranch` - merge two local branch: branch which is active that which we put either value "nameOfBranch"