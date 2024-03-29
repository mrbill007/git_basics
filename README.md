# Working Directory

- The area where all of our files and directories and changes are living all the time.

# Staging Area

- Files and directories that we explicitly add to the staging area.

# Git Repository

- Where all our snapshots are stored.

# Commands

- mkdir <project_name>: create a new project directory
- cd <project_name>: change into your project directory
- git init: use to initialize a new repo.
- touch main.py index.html style.css: create project files.
- git status: use to see what's going on, i.e. what's being tracked, what's being staged, etc.
- git add <filename>: your file has been added to the staging area.
- git commit -m "Message goes here. Use a present tense verb.": file has been added to github.
- git log: inspect history of commits

---

# Adding multiple files of a certain type

- git add \*.html

# Add all files and folder in the current directory (including hidden)

- git add -A
- git status

# Removing files

- git reset HEAD <filename>: remove a file from the staging area

# Ignoring files

- git .gitignore: create a directory called .gitignore and add files you want to ignore

# Git Branches

- git branch: view all branches
- git checkout -b <branch_name>: add a new branch
- git checkout <branch_name>: checkout a branch
