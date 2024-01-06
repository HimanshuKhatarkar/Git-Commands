### `git blame <file>` : 
Show who last modified each line of the specified file.

#### Flags and Options :
1. `git blame -L <start>,<end> <file>` : Blame only the specified range of lines in a file.
2. `git blame -C <file>` : Show who last modified each line and also detect copies and renames.
3. `git blame -M <file>` : Detect line movements within a file.


#### Example Usage:

* git blame index.html
* git blame -L 10,20 index.html
* git blame -C index.js
* git blame -M app.js
