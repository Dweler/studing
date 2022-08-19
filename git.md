# Описание git

## Рабочие зоны git
1. project's working directory(pwd)
1. staging area(sa) in file .git/index
1. repository(rp) in directory .git 
1. origin(or)
1. upstream(up)

### Commit ID
Commit IDs are unique SHA-1 hashes that are created whenever a new commit is recorded. (Using from first 4 to 40 hex symbols)

### HEAD
In Git, a HEAD is a ref that points to the tip (latest commit) of a branch. You can view your repository's heads in the path . git/refs/heads/ . In this path you will find one file for each branch, and the content in each file will be the commit ID of the tip (most recent commit) of that branch.

## Beginning
Install git
```
git config --global user.name <userName>
git config --global user.email <userEmail>
git config --global core.editor "code --wait"
```
## Create new repository 
```
mkdir <project's working directory>
cd <project's working directory>
git init
```

## Cloning a local or remote repository
```
git clone <url>
```
## Staging
```
git add <filename>
git add -A
git add .
git reset <filename>
```

## Commits
```
git commit -m '...'
```

## Inspecting changes
```
git status
```
This shows the change between HEAD and index (i.e. what will be committed if you say git commit), and between index and working tree files (i.e. what you could stage further before git commit using git add) for each path.
```
git diff
```
This lets you review what will be committed (i.e. between HEAD and index).
```
git log
```
```
git show //?
```
