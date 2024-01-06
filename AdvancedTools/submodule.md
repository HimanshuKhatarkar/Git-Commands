### `git submodule add <URL>` : 
Add a submodule to the repository.

#### Flags and Options :
1. git submodule init: Initialize submodules recorded in the repository configuration.
2. git submodule update: Clone and checkout submodules to the recorded commit.
3. git submodule foreach <command>: Run a command in each submodule.

#### Example Usage:

* git submodule add https://github.com/example/repo.git
* git submodule init
* git submodule update
* git submodule foreach git pull origin master
