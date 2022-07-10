# Merging
The idea of merging is to incorporate the changes in the branches from one branches to another.
  + we merge branches not commits
  + we merge to the current HEAD
 
## Steps to merge branch
 1. Switch to the branch you wan't to merge into.
 2. Use the command:
     > git merge "branchToMerge"
**The above step is used for fast forward merge.**

## Merge Conflict
You need to manually resolve merge conflict. Steps to resolve the conflict:
 1. Open the file with merge conflict.
 2. Edit the file to remove the conflict.
 3. Remove the conflict 'marker' in the file.
 4. Add your changes and make a commit.


