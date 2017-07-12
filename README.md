# Git-commands
Basic Git commands for future reference


### to add ssh key to Github:

>Open ~/.ssh/id_rsa.pub and then copy the key from the file. At last add the key in the github ssh keys in settings.


### git config:

>git config --global user.name "name"

>git config --global user.email "email"

### git clone:

>git clone <url-of-repository>

### git diff:

>show all the changes made

### git add <file-name>:

>add to the changes you want to track

### git commit -m "message":

>save a version of this repository

### git commit -am "message":

>add + commit

### git status:

>shows currentstatus of repository

### git push / git push origin master:

>send commited changes to remote repository

### git pull 

>pull the changes made in the remote repository

### git log:

>shows history of commits and messages

### git reset --hard <commit>

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