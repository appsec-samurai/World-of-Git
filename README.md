### Useful Git Commands
============

_A list of Git commands_
___
___

### Get Help from Git
| Command | Description |
| ------- | ----------- |
| `git help`| Take help from github help section for different commands and other errors. |


### Set your Git Credentials

| Command | Description |
| ------- | ----------- |
| `git config`| To set the basic configurations on github like your name and email. |
| `git config --global user.name "<username>"`| Sets configuration values for your user name on git. |
| `git config --global user.email <email address>`| Sets configuration values for your user email on git. |


### Create & Clone Project Locally

| Command | Description | Example |
| ------- | ----------- | ------- |
| `git init` | Initialize a local Git repository |
| `git clone` | To clone or make a local copy of the global repository in your system | `https://github.com/appsec-samurai/World-of-Git.git` |


### Basic Commands on Repository

| Command | Description | Example |
| ------- | ----------- | ------- |
| `git status` | To see whats changed since last commit.It shows all the files that have been added and modified and ready to be committed and files which are untracked. | 
| `git add <file-name.extension>` | Add a file to the staging area | `git add Readme.txt` |
| `git add -A` or <br> `git add .` | Add all new and changed files to the staging area |
| `git add --all` | To add all files of current directory to staging area. |
| `git add *.txt` | To add all text files of the current directory to staging area. |
| `git add docs/*.txt` | To add all text files of a particular directory(docs) to staging area. |
| `git add “*.txt”` | To add text files of entire project to staging area. |
| `git commit -m "<commit message>"` | To commit our changes(taking a snapshot) and providing a message to remember for future reference. | `git commit -m “Created a Readme.txt”` |
| `git rm -r <file-name.extension>` | Remove a file (or folder) | `git add Readme.txt` |


### Commands related to Inspection & Comparison on Repository

| Command | Description |
| ------- | ----------- |
| `git log` | To check the history of commits for our reference. |
| `git log --summary` | View changes (detailed) | 
| `git log --oneline` or <br> `git log --pretty=oneline` or<br> `git log --pretty=short` | View changes in one line (briefly) |


### Commands related to Commit

| Command | Description |
| ------- | ----------- |
| `git log --oneline` | List of all commit with commit id and commit message) |
| `git checkout<commit id>` | Return to previous commit <commit id> |
| `git revert <commit id>` | Revert commit <commit id> (undo one particular commit) |
| `git reset --hard <commit id>`| Reset to previous commit <commit id> (remove history of all commit after <commit id> ) | 
| `git rm --cached <file/folder>` | Stop a file being tracked |
| `git checkout <file/to/restore>` | Restore a file to a previous commit|


### Commands related to Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch <branch name>` | Create a new branch | 
| `git checkout -b <branch name>` | Create a new branch and switch to it | 
| `git checkout -b <branch name> origin/<branch name>` | Clone a remote branch and switch to it | 
| `git branch -m <old branch name> <new branch name>` | Rename a local branch | 
| `git checkout <branch name>` | Switch to a branch | 
| `git checkout -` | Switch to the branch last checked out | 
| `git checkout -- <file-name.txt>` | Discard changes to a file | 
| `git branch -d <branch name>` | Delete a branch | 
| `git push origin --delete <branch name>` | Delete a remote branch | 
| `git diff <source branch>  <target branch>` | Preview changes before merging | 
| `git merge <branch name>` | Merge a branch into the active branch | 
| `git merge <source branch> <target branch>` | Merge a branch into a target branch | 
| `git stash` | Stash changes in a dirty working directory | 
| `git stash clear` | Remove all stashed entries | 

### Commands related to Sharing & Updating Projects

| Description | Command |
| ------- | ----------- |
| `git push origin <branch name>` | Push a branch to your remote repository | 
| `git push -u origin <branch name>` | Push changes to remote repository (and remember the branch) | 
| `git push` | Push changes to remote repository (remembered branch) | 
| `git push --all` | Push changes to remote repository all branch | 
| `git push -f` | Push changes to remote repository (Force) | 
| `git push origin --delete <branch name>` | Delete a remote branch | 
| `git pull` | Update local repository to the newest commit | 
| `git pull origin <branch name>` | Pull changes from remote repository | 
| `git remote add origin ssh://git@github.com/<username>/<repository-name>.git` | Add a remote repository | 
| `git remote set-url origin ssh://git@github.com/<username>/<repository-name>.git` | Set a repository's origin branch to SSH |


**[⬆ Back to Top](#Useful Git Commands)**
