## Basic Snapshotting

Snapshotting in Git refers to capturing the current state of your files and saving it as a commit.

### `git add`: Add file contents to the index (staging area) to prepare for a commit.

#### Basic Syntax:
`git add <command / flag> <file/name>` :

1. -A, --all: Add all changes, including untracked and deleted files.
2. -u, --update: Update changes for already tracked files.
3. -p, --patch: Interactively choose changes to add.
4. -N, --intent-to-add: Record only the intent to add the files later.

### Example Usage:
Adding Files to the Staging Area:

1. git add file.txt       ->      Add a specific file to the staging area
2. git add .              ->      Add all changes to the staging area
3. git add -p             ->      Interactively select changes to stage
