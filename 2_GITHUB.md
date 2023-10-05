# Source
__[Youtube video link](https://youtu.be/mJ-qvsxPHp)__

# Introduction

Definition (github): is a website (like bitbucket and gitlab). All the saved progresses that are on the compuuter (local storage) are transfered to the internet (so that other people can look through the code)

# How to use github

1. create a profile and a repository/folder
2. the site gives you the necessary commands to save your work in the repository

# Git Commands

+ __remote__ command
```shell
git remote add origin <link to the repository>         
# e.g. https://github.com/Raspberry20/gitVideo.git  site
``````

+ __push__ command
```shell
git push -u origin master    
#the locally saved progress has been pushed to the github
```

```shell
git push origin master     
#push changes to github master
```

+ __full list of commands__
```shell
echo "# gitVideo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/jojo0808/gitVideo.git
git push -u origin master
```

```shell
git remote add origin https://github.com/jojo0808/gitVideo.git
git branch -M master
git push -u origin master
```

# Branches

+ **master branch**: the default branch
+ **different branch**: a different folder where we can save a progress that we don't want to save in the master branch for x reasons. One could want to have a branch that trails off a main code for their own personal use

## Git Commands

+ __checkout__ command
```shell
git checkout -b <name of new branch>   
#create a new branch
```

+ __branch__ command
```shell
git branch     
#shows a list of branches #the new branch should appear in this list #using this command, you change branches (form the master branch to the new branch)
```

## Merging branches
You can merge a branch to the master/main branch if you wish. Or you can decide not to merge and leave it as it is.

The branch can be deleted or not. It is irrelevant until it is merged to the main branch.

**Example**: Someone downloads your code on github, creates his own branch and makes changes to your original code. He could come to you and ask if he could merge his branch to the main one. You can decide to accept this proposition if you feel his modifications are helpful.

### how to merge
+ __push__ command
```shell
git push origin new-branch     #push the neww branch to github
```

If someone wishes to merge thei branch to the original/master branch, they file a pull request. The original owner of the repository gets this request and looks it over before deciding to merge or not.


# Sychronize git and github

You want both of them to be synched and up-to-date.

## Save changes from Github to Git (local)

This means that we wish to *pull* the changes from github to our computer

+ __pull__ command
```shell
git pull origin master
```

## Save changes to Github from Git (local)
This means we wish to *push* the changes from our computer to the github site.

+ push command
```shell
git pull origin master
```

# Other commands

+ __status_ command
```shell
git status     #check status of changes
```