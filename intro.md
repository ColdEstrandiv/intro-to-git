

# intro to Git
git is a version control tool. it alllows you to manage your code 
over time. Where multiple versions of the code can exists. And you
can go back to points in time to view what the code was.

## Setting up a new git repo
```powershell
# Make sure you are active in the folder you want to create repo in.
# Run git status to check if there's a repo or not
git status
# should return
# fatal: not a git repository

git init
# you should see
#intialized empty Git repository in <folder location>

# to see the git folder run this
dir -Force

```

***note*** don't nest repos, if you have a git repo don't create 
a new one inside it

## Making a commit
```powershell
git status
# shows what changes are not included

# a commit is a two step process, the first is adding a file for git to keep track of

git add <file>

git commit -m "initial commit: added <file>"
# this takes things added to the stage and commits them with message

git status
# now can see the working tree is clean with nothing new to commit



```