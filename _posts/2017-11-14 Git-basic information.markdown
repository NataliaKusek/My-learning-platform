---
layout: post
title:  "Git-basic information"
date:   2017-11-14 14:02:39 +0000
categories: git
---

# What is **Git**?

**Git** is a version control system. Git is a tool for keeping changes while creating project.

*Repository* is a data structure where Git keeps information about project and changes in this project. By default, this is a .git file located in the project directory.

Git instalation on OSX:

```
brew install git
```

Procedure to push project from local branch to remote branch:

```
cd folder name (directory to folder which we want to add to repository)
git init (it will initialise repository)
git add . (it will add all files with changes to repository)
git commit -m "message" (it will confirm changes and add message)
git remote add origin git@github.com:NataliaKusek/My-learning-platform.git
git push origin master (it will update changes from local branch to remote branch)
git pull origin master (it will take changes from remote branch to the local branch)
```

Other helpfull command:

```
git status
git config --global user.name "Natalia"
git config --global user.email natalia@kusek.info
git clone https://github.com/NataliaKusek/My-learning-platform.git
```

You can work on different branches and when you have stable version of your file you can merge branches

```
git branch name (you will create new branch)
git checkout name (you will open new branch and add files to that branch as above)
git checkout master (you will open main branch)
git merge name (you will merge files from branches)
git branch -d name (you will delete branch)
```


If you want to learn more click [here](https://git-scm.com/documentation "Git home page")

