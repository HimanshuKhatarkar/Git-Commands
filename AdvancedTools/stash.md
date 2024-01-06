### `git stash` : 
Temporarily store changes that are not ready to be committed.

#### Flags and Options :
1. `git stash save "stash_message"` : Save changes to a stash with a descriptive message.
2. `git stash list` : List all stashes.
3. `git stash apply` : Apply the most recent stash without removing it from the stash list.
4. `git stash pop` : Apply the most recent stash and remove it from the stash list.
5. `git stash drop`: Discard a specific stash.
6. `git stash clear` : Clear all stashes.


#### Example Usage:

* git stash
* git stash save "Work in progress"
* git stash list
* git stash apply
* git stash pop
* git stash drop stash@{2}
* git stash clear
