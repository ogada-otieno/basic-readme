# Simple CLI Command

Below is a list of CLI commands that we'll use occasionally.

## Description

## Working with files and folders

```bash

# Creating a folders
mkdir <folder-name>

# Creating a file
touch <file-name>

# Navigating through folders
cd <folder-name>

# Going one step behind a folder
cd ..

# Navigating back to the root folder
cd ~

# Removing files and folders that have no permissions
rm <folder/file-name>

# Removing files and folders that have permissions
rm -rf <folder-name>

# Opening a folder in vs code 
code <folder/file-name/current dir>

# List all files in within a folder (unhidden)
ls 

# List all files within a folder (hidden)
ls -a 
```

## Basic Git Commands 

```bash
# Initialize a git repository
git init 

# Check status
git status / git status -s 

# Add changes to the pipeline
git add .

# Commit changes 
git commit -m "Appropriate commit message"

# Push changes
git push 
git push origin main

# Create new branch
git branch new-branch-name

# List all branches
git branch -a 

# Switch branch name
git checkout branch-name
git switch branch-name 

# Check details of git configuration
git config -l 

# Clone an online repository
git clone <ssh link>

# Deleting a branch 
git branch -D <branch-name>

```
