# Branching
Think of branching as alternative to timeline in a project that enables to create separate context without interference with others unless they are merged.

## To create branch
  >  git branch branchName

## To delete branch
  >  git branch -d branchnName
  >  git branch -D branchName

*D* force delete the branch even when it contains commited files.

## Rename branch
First, switch to the branch you wanna rename.
  >  git branch -m branchName

## Moving into branch
  >  git switch branchName
  >  git checkout branchName 

*Git checkout is the old way of switching branches.* **It does matter where you branch from kindly take note.**

## Create branch and move to it
  >  git switch -c branchName
*-c* stands for create.

## To list branches created
  >  git branch
  >  git branch -v 
*To see the last commit in the branch , include flag -v*

# HEAD

It is referencing the tip of current branch we switch to. If switched to the main branch, the HEAD ref 



