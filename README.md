## Git and Git Branching Cheat Sheet
Categories of git commands and practice with branching.
Practice with merging and merge conflicts.
### Basic commands
### Info commands
* `git status` - shows status of current working directory
* `git log` -list commit history
* `git log --online` -list commit history (compacted)
* `git config -l` -list local git configuration settings


### Branch commands
* `git branch` -list local branches, highlight current branch
* `git branchName` - create branch `branchName`
* `git branchName` - switch to branch `branchName`
* `git checkout -b otherBranch` - switch to branch `otherBranch` creating it if it doesn't exist

### Remote commands
* `git remote add origin someUrl` - connect local repo to remote repo url as `origin`
* `git push origin branchName` - push local commits to remote repo into branch `branchName`
* `git pull origin branchName` -pull remote branch `branchName` into local current branch

### Other commands
* `git help` - list git subcommands and options
* `git config --help` -show options for `git config`
