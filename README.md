## Git Cheat Sheet and Branching Practice

<<<<<<< HEAD
<<<<<<< HEAD
### General Commands
* 'git init' -initialize local git repo in current working directory
* 'git add filename' - stage 'filename' for commit
* 'git commit -m msg' - commit staged files into local repo
* 'git clone url' --close remote repo 'url' to local directory


### Information Commands
* 'git status' - show status of local repo
* 'git log' - list commit history of current branch
* 'git log --oneline' --list commit history (compact format)
*'git config --list' - list local repo config settings
### Branching commands
* 'git branch' - list local branches
* 'git branch branchName' - create local branch 'branchName'
* 'git checkout branchName' - switch to branch 'branchName'
* 'git checkout -b branchName' - create and switch to branch 'branchName'


## Workflow:
1. Pull latest remote main into local main

	'git pull origin main'

1. Branch from updated local main

	'git checkout -b myBranch'

1. Work in local branch, commiting frequently 
1. When ready to merge, pull remote 'main' into local branch (must commit first)

	'git pull origin main'

	* Fix any merge conflicts, then commit

1. Push to remote branch
	
	'git oush origin myBranch'

1. Create pull request
1. Merge pull request	

