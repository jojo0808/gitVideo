# Source

__[link text](https://youtu.be/mJ-qvsxPHp)__

# Introduction
git != github

Definition (git): software, already installed on your computer (macOS/linux) 

Definition (git): a memory card for code. To save your progress as you go. We enter a command to save our progress so we can goback to our saved progress as we wish. The files are saved locally

# Git Commands
+ <code style="background:black;color:white">__init__</code> command

```shell
git init 		
# this is equivalent to putting a memory card in the game console
```

+ __add__ command

```shell
git add <file(s)> 				
# what we want to save. a specific file or all files #e.g git add file or git add. 
# the latter inicates pushing changes on all files in the current directory = add all the files-to-be-saved to the staging area
```

+ __commit__ command

```shell
git commit 			
# commits all files in the staging area into memory (actual saving command)
```


```shell
git commit -m 			
# commit + adds message -> a message that describes the saves(to understand the progress)
```

+ __log__ command

```shell
git log 			
# to check the log of all the saved changes # there is a hash code that allows you to go back to a specific saved progress
```

+ __checkout__ command

```shell
git checkout <commit_hashcode> 			
# to checkout a commit (a previously saved progress) = go back to a specific progress
```

>__NB__: when you go back to a saved progress, you automatical change branches






