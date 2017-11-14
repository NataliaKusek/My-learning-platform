# What is **Git**?

**Git** is a version control system. Git is a tool for keeping changes while creating project.

*Repository* is a data structure where Git keeps information about project and changes in this project. By default, this is a .git file located in the project directory.

Git instalation on OSX:
```
brew install git
```

Procedure to push project from local branch to remote branch:

```
cd folder name (*directory to folder which we want to add to repository*)
git init (*it will initialise repository*)
git add . (*it will add all files with changes to repository*)
git commit -m "message" (*it will confirm changes and add message*)
git remote add origin git@github.com:NataliaKusek/My-learning-platform.git
git push origin master (*it will update changes from local branche to remote branch*)
git pull origin master (*it will take changes from remote branche to the local branche*)
```



