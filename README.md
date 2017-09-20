# How to Write a Git Commit Message
https://chris.beams.io/posts/git-commit/


# Git commands for merging your local directory with a remote repository

## git init

>First create a local repository

## git remote add origin <urlOfRemoteRepository>

>add remote repository origin to local repository

## git pull origin master

>merge the two repsitories


# Git-commands
Basic Git commands for future reference


### to add ssh key to Github

>Open ~/.ssh/id_rsa.pub and then copy the key from the file. At last add the key in the github ssh keys in settings.


### git config

>git config --global user.name "name"

>git config --global user.email "email"

### git clone (When staring a new remote repository, it's better to use git clone)

>git clone url-of-repository

### git init

>create a git repository

### git diff

>show all the changes made

### git add file-name

>add to the changes you want to track

### git commit -m "message"

>save a version of this repository

### git commit -am "message"

>add + commit

### git status

>shows currentstatus of repository

### git push / git push origin master

>send commited changes to remote repository

### git pull 

>pull the changes made in the remote repository

### git log

>shows history of commits and messages

### git reset --hard #commit

>reset to a previous commit

>git reset --hard origin/master, back to remote repository version

---

## Merge conflicts

```C
int a = 1;
<<<<<<<<<<<< HEAD
int b = 2;
============
int b = 0;
>>>>>>>>>>>> 5428973695827389457345e
int c = 3;
int d = 4;
```

>Keep the line you want to keep and delete everything else in the conflict

---

## Branching

### git branch

>shows all branches

### git branch branch-name

>new branch

### git checkout branch-name

>switch to a branch

### git checkout -b branch-name

>new branch and switch to it

### git merge branch-name

>merges <branch-name> with current branch

### git branch -D branch-name

>delete branch (-d gives a soft delete)

## Merging two separately origined repositories

### git pull origin branchname --allow-unrelated-histories