# Git and Github
- Git is a version control system that allows you to manage the history of your code, track changes to your files and to collaborate with others. Version control systems are essential for software development.

## Git and Github are different

Git is a version control system that is used to track changes to your files. It is a free and open-source software that is available for Windows, macOS, and Linux. Remember, GIT is a software and can be installed on your computer.

Github is a web-based hosting service for Git repositories. Github is an online platform that allows you to store and share your code with others.

### Repository
A repository is a collection of files and directories that are stored together.like a folder on your computer, but it is more than just a folder
>git folder is hidden folder 

![alt text](image-1.png)

## Commands
git add . (or filename )
git log 
git log --oneline

## git ignore file : will not save files mentioned in it but git ignore will be tracked.
eg .env file, api keys, payment gateweay for TF =  *.tfstate
*.tfstate.*
*.tfvars
GIT doesnt keep track of empty folder
to track empty folder but needed in future we .gitkeep file 

# Branches
 
git branch - This command lists all the branches in the current repository.
git branch bug-fix - This command creates a new branch called bug-fix.
git switch bug-fix - This command switches to the bug-fix branch.
git log - This command shows the commit history for the current branch.
git switch master - This command switches to the master branch.
git switch -c dark-mode - This command creates a new branch called dark-mode. the -c flag is used to create a new branch.
git checkout orange-mode - This command switches to the orange-mode branch.
Commit before switching to a branch
Go to .git folder and checkout to the HEAD file