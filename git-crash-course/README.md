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

When we want to commit code we can write git commit which will open up the commit edit message in the editor of choice.
```sh
git commit
```
Set the global editor
```
git config --global core.editor nano
```

Make a commit and commit meessage without op[ening an editor]
```sh
git commit -m "add another message"
```

git add .
```
## BRanches

## Remotes

## Stashing

## Merging

## Add

When we want to stage 
```
git add Readme.md
git add . 
```

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
```
git status
```

## Gitconfig file 
The gitconfig fileis what stores your global configurations such as email, name, editor and more. 
Showing the contents of our .gitconfig file
```
git config --list
```

When you first install Git on a machine you asre suppose to set up your name and email. 
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

## Log
git log will show recent git commits to the git tree
 
## Push

When we want to push a repo to our remote origin

```
git push
```