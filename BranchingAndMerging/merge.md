### `git merge` : 
Combine multiple sequences of commits into one unified history.


#### Basic Syntax:

`git merge [options] [branch-name]`

1. [branch-name]: Name of the branch whose changes you want to merge into the current branch.

#### Flags and Options:
1. --no-ff: Force a merge commit even if it's a fast-forward.
2. --squash: Merge changes but don't create a commit, allows combining commits.


#### Example Usage :
Merging Changes :
1. git merge branch-name         # Merge changes from a specified branch
2. git merge --squash branch-name    # Merge changes without committing

