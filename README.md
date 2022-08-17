## Git and Git Branching Cheat Sheet

### Basic commands
* `git init` - initialize current directory w repository
* `git add .` - add all files in current directory to git index, staging them for commit
* `git commit -m` - commit staged changes to local repository

### Info commands
* `git status` - shows status of current working directory
* `git log` -list commit history
* `git log --online` -list commit history (compacted)

### Branch commands
* `git branch` -list local branches, highlight current branch
* `git branchName` - create branch `branchName`
* `git branchName` - switch to branch `branchName`
* `git checkout -b otherBranch` - switch to branch `otherBranch` creating it if it doesn't exist


### Other commands
* `git help` - list git subcommands and options
* `git config --help` -show options for `git config`
