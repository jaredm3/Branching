## Git Branching Practice

## Basic 'git' commands

* 'git init' - create a new local repo
* 'git add .' - add current working directory
* 'git commit -m"message" - commit changes to local repo
* 'git ' - changed to master


## Basic Branching
* 'git branch branchName' - Create local branch named 'branchName'
* 'git checkout branchName' - Move to branch named 'branchName'
* 'git branch' - Display local branches and which you are on
* 'git checkout -b newBranch' - Create and checkout branch 'newBranch'

### Merging
* Add and commit local branch.
* Push local branch to remote.
* Pull 'master' from remote into local branches
  '''git checkout newBranch'''
  '''git pull origin master'''
* resolve merge conflicts
* commit and push local branch

git add .
git commit -m ""
git push origin newBranch

* On Github, create Pull Request
* Teammates merge Pull Request into master
