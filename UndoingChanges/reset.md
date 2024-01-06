
### `git reset <file>` : 
Unstage the specified file but keep the changes.

#### flags and options : 
1. `git reset --soft <commit>`  : Move HEAD to a specific commit, keeping changes staged.
2. `git reset --mixed <commit>` : Move HEAD to a specific commit, unstaging changes.
3. `git reset --hard <commit>`  : Move HEAD to a specific commit, discard all changes in the working directory and staging area.


#### Example Usage:

* git reset file.txt
* git reset --soft HEAD^
* git reset --mixed HEAD~3
* git reset --hard ABC123
