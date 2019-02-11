# Working Directory
- Area where all of our files and directories and changes are living all the time

# Staging Area
- Files and directories that we explicitly add to the staging area

# Git Repository
- Where all our snapshots are stored

# Adding multiple files of a certain type
- git add *.(format) - * acts as a wildcard

# Adding all files in directory (including hidden)
- git add -A

# Removing files
- git reset HEAD <file>...

# Ignoring files
- inside a .gitignore file, type in the files you want git to ignore. Then, add and commit that file to git.

# Git Branches

-Listing all branches
% git branch
-Adding a branch
% git checkout -b <branch_name>
-Changing branches
% git checkout <branch_name>
-Merging a branch
% git merge <branch_name>
-Removing a branch