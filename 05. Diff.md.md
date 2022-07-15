# Git Diff

It is used to view changes between commits, branches, files, and working directory. To picture a repo and how it has changed overtime.

Git difference is best noticed in the Git GUI software. Added files or changes represented with *green* color while removed files in *red* color. 

  >  git diff HEAD HEAD~1

HEAD~1 is a short syntax of parent commit of HEAD.

 1. **Git diff** without additional option will list all the change in working directory that are NOT staged for next commit.
 2. **Git diff HEAD** list all changes in the working directory since the last commit.
 3. **Git diff staged** list the changes between staging area and last commit.
  > git diff --staged
  >  git diff --cached
 4.  To get difference in specific file.
  >  git diff HEAD filename

## Comparing two branch

  >  git diff branch1..branch2

## Comparing two commits

  >  git diff commit1_Hash..commit2_Hash