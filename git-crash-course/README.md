## Git Hidden Folder

There is a hidden folder called `.git` which tells you that our project is a git repo. 

If we wanted to create a git repo in a new project, we can create the folder and the folder and then initialize that repo using `git init`

```
mkdir  /workspaces/tmp/new-project
cd /workspaces/tmp/new-project
git init
touch Readme.md
code Readme.md
git status
git add Readme.md
# makes changes to readme.md
git commit -a -m "add readme file"
```


## Cloning
We can clone three ways: HTTPS/SSH/CLI

Since we are using GitHub Codespaces we'll create temporary direcotry in our workspace

```sh
mkdir /workspace/tmp
cd /workspace/tmp
```


### HTTPS
```sh
git clone https://github.com/andrew-wc-brown/Github-Examples.git
cd GitHub-Examples
```

### SSH
### CLI

## Commits

## Branches

## Remotes

## Stashing

## Merging

## Reset

Reset allows you to move Staged changes to be unstaged.
This is useful when you revert all files not to be commited. 

```
git add . 
git reset
```
>git reset will revert a git add.  

## Status

Git status shows you what files will or will not be committed. 