# Ch2.1
# Exercise: Clone a Git Repository and Familiarize Yourself with its Internal Files

## Step 1
The cloned local repository contains a hidden `.git` folder that keeps track of the git repository "internal" files and history.

Investigate the "internal" `.git` repository files and folders using:
```bash
$ cd .git
$ ls -al
```
**NOTE: DO NOT** make any changes to any files in the `.git` folder directly (these files will be altered by git commands you will issue). The purpose of this exercise is to illustrate where git stores the historical information about a repository.
