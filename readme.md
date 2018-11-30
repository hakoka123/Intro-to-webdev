# Working Directory
* Area where all of our files and directories and changes are living all the time

# Staging Area
* Files and directories that we explicitly add to the staging area

# Git Repository
* Where all our snapshots are stored

# Add files of certain type
* Adding multiple files of a certain type
    * git add *.html
* Adding all files in directory(including hidden)
    * ls -a >> To show all files including hidden ones
    * git add -A >> Adds everything in your project at one time...
* Removing files
    * git reset HEAD file2.txt >> Removes file2.txt from staging area...
* Ignoring files
    * touch .gitignore >> creates a hidden .gitignore file
    * git will ignore all files thats listed in .gitignore... >> use git status to check...
    * add file2.txt to .gitignore
    * mv fil3.hmtl file3.html >> rename/deletes fil3.html and move it to file3.html

# Git Branches
* Listing all branches
    * git branch
* Adding a branch
    * git checkout -b feature1 >> Switches us to a new branch, named feature1
* Changing branches
    * git checkout master >> switches us back to the master branch
* Merging a branch
    * git merge <branch_name>
* Removing a branch
    * Best to not delete branches... Doesn't take alot of space...
    * git branch -d <branch_name>




