### `git rebase <base>` : 
Reapply commits on top of another base commit.

#### Flag and options:
1. `git rebase -i <base>` : Interactive rebase to squash, edit, or reorder commits interactively.
2. `git rebase --continue` : Continue a rebase after resolving conflicts.
3. `git rebase --abort` : Abort an ongoing rebase.

#### Example Usage:

* git rebase main
* git rebase -i HEAD~3
* git rebase --continue
* git rebase --abort
