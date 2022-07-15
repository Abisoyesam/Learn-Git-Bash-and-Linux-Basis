# Git Stash

Git provide a way of switching from one branch to another without making unnecessary commit.

It helps to save changes you are not ready to commit. You can stash change then come back to it later.

  >  git stash 
or use *git stash save* instead.

  >  git stash save

To remove the most recent stashed changes in your stash and reapply them to your working copy. Use:

  >  git stash pop

To reapply the changes in stashed to multiple file. Use:

  >  git stash apply

**You can stash multiple times though not a good idea.** To check list of stashes, use:

  >  git stash list

To apply stashes from multiples stashes.

  >  git stash apply stash@{2}

To drop particular stash

  >  git stash **drop** stash@{2}

To clear all stashes

  >  git stash clear