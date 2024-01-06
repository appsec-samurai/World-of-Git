Useful Git Commands
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
| `git clone` | To clone or make a local copy of the global repository in your system | `https://github.com/appsec-samurai/World-of-Git.git` 


### Basic Commands on Repository

| Command | Description | Example |
| ------- | ----------- | ------- |
| `git status` | To see whats changed since last commit.It shows all the files that have been added and modified and ready to be committed and files which are untracked. | 
| `git add <file-name.extension>` | Add a file to the staging area | `git add Readme.txt`
| `git add -A` or <br> `git add .` | Add all new and changed files to the staging area | 
| `git commit -m "<commit message>"` | To commit our changes(taking a snapshot) and providing a message to remember for future reference. | `git commit -m “Created a Readme.txt”` |
| `git rm -r <file-name.extension>` | Remove a file (or folder) | `git add Readme.txt` |
