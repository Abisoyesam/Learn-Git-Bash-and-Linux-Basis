# Git Commands

## To initialize a git repository or directory.

  >  git init 

A repository is a workspace which tracks or manages file or folder in it.

### To specify the init branch

  >  git init -b main

*Before initializing a repo, make sure it hasn't been initialized before. Verify with : *
  >  git status 

## To add a file

It is used to stage files in the working directory.
  >  git add <filename>
  >  git add . 
to add multiple files at once.

## Commiting a file

Commiting a file or folder is like adding a checkpoint to the repo.
  >  git commit -m "commit message"
*-m* means message flag.

  >  git commit --amend
To change one step previous commit. To include file you forgot or correct typo in commit message.

## To configure default editor

  >  config --global core.editor "code --wait"

## To see logs of commits

  >  git log
  >  git log --oneline

**N.B: Keep each commit focused on a single thing. It makes it easier to undo changes and review code.**

## Gitignore

To uncommit some files, Api keys, folders, create a *.gitignore* file in the root of repository and add the folder.

  >  foldername/
  >  *.log
  >  .DS_Store