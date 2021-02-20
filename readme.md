# My Git Cheatsheet
<!-- one hashtag = h1, two hashtags = h2 etc.... githib trats this as server treats index html -->

## Creating a Git Repo

In the folder you want to create a repo, do the following command in terminal

<!-- three backticks to make it look like code -->

```
git init
```


**always check that you are not already in a repo by using git status**

## adding files to staging

staging is files that are being tracked to be committed

use git status to see which files are untracked(red) or in staging (green)

```
git status
```

three ways to add files to taging 
- one file at a time `git add <filename>`
- git add all files in the repo `git add -A`
- add files in my current folder with `git add .`

<!-- add sudo before if it says permission denied (overrides) -->

## committing files to our repo

```
git commit -m "some random text, something descriptive"
```

**if you forget the -m, youll end up nnthe vim, to exit the type ";wq"**

## looking at our commit history

```
git log
```

and this one allows you to see it in one line

```
git log --oneline
```


## working with remotes

- to add a remote 'git remote add <name> <url>'

<!-- dont actually <> its just the style of notes
and "name" is what ever you want it to be.. often "origin" -->

- to see list of remotes 'git remote -v'
- to push code "git push <remoteName> <branchName>'
    - to see current branch 'git branch'

<!-- basically name in "remote name" is "name" listed above.... and the "branch name" is what you find when you input "git branch" -->

<!-- steps to commit
1) git add .
2) git commit -m "description"
3) git push <remoteName> <branchName> -->

<!-- USE SUDO!! IF PERMMISSION DENIED -->