## Command for Initail Configurations

### git config --global user.name "Your Name"
use to configure the username of the user



### git config --global user.email "your-email@example.com"
use to configure the email of the user


### git config --list
use to show the configurations details list.


### git init
use to initialize the git repository


### echo "My First Project" > README.md
echo use to create a new file with the given message.


### git add README.md
use to add file to the stagging area


### git commit -m "Initial commit: Added README.md"
use to commit the changes to the local system with a given message.


### git status 
use to check the file status of the file at the local system


### git log --oneline --graph --decorate

* **git log** : This command is use to check the commit history of the files.

* **git log --oneline** : This command is use to get the specific commit history fo the files.

* **git log --graph** : This command is used to display a visual representation of the commit history in a Git repository,

* **git log --decorate** : This command used to display the commit history with additional information about references such as branch names, tags, and HEAD pointers.

### git clone http://codinggita.com/example-repo
This command use to clone any repository from the git hub to local system.

### git branch feature-login
This command is use to create a new branch.


### git checkout feature-login
This command is use to switch branch.

### git checkout -b feature-login
This command use to create and switch branch at the same time.

### git checkout main   git merge feature-login
To merge a branch to the main branch, first we have to switch to the main branch and then write the command **git merge [branch name]** to marge that brach to main branch.

### git branch -d [feature-login]
This command use to delete the branch.

### git stash
This command is used to temporarily save changes in your working directory and staging area.

### git stash list 
This command lists all the stashes you've saved

### git stash apply
This applies the most recent stash to your working directory, but does not remove it from the stash list.

### git stash drop 
This command use to delete a added stash

### git cherry-pich {commit-hash}
command is used to apply a specific commit from one branch onto another branch.

### git tag
command is used to create, list, or delete tags in your Git repository.

### git push
This commit use to save the changes of local system to the online git repo.

### git remote add origin {repository-url}
This command use to connect the local repository to the git repository.


### .gitignore file
This file is used in Git to specify which files or directories should not be tracked or committed by Git.