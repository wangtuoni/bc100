18:22

# Lesson Outline

## Overview and Why Version Control?

## Terminology/Acronym helpers
* Repo: repository, a designated folder for Git version control
* Local: on your computer
* Remote: on another computer (e.g. Github server)

## Install:
* Terminal Pick Your Theme and Font Size
* Terminal Oh My ZSH
* Brew
* Node, NPM and NVM
* Git

## Create a Local Repo from our Lesson
1. Initialize our local repo
```
git init
```
2. Stage our lesson files so we can commit them to version history
```
git add -A
```
3. Commit our staged files, and write a message so we know what happened.
```
git commit -m "My first commit."
```

## Connect our Local Repo to a Shared Remote Repo (Github)
1. Create a Git Repo on Github (remote)
2. Connect local repo (Lesson) to remote repo (Github)\
Copy and paste commands from Github after creating new repo (option 2)
3. Push our code
```
git push origin master
```

## Git Standard Workflow for Versioning and Sharing
1. Make changes and save to our local
2. Add those changes to the Git commit history (period means ALL)
```
git add -A
```

3. Write a commit message so we know what happened
The flag -m gives you the ability to write a brief message inline
Without it you enter Vi great for longer, more detailed messages.
```
git commit -m "Your Commit Message Goes here."
```

4.  Push our changes to remote shared repo (in this case Github)
origin is our local reference to our remote repo
master is the branch are working on.
    All repos default to master, and this is the assumed master branch
    As we dig deeper, we can create branches from master to work on features of our project (feature branch)
```
git push origin master
```
5. Rinse and Repeat
