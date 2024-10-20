
# Git Commands Reference

## 1. Repository Setup
- **Create a new directory**: 
  mkdir git-tutorial
- **Change to the directory**: 
  cd git-tutorial
- **Initialize a new Git repository**: 
  git init

## 2. File Management
- **Create new files**: 
  touch a.txt  
  touch b.txt  
  touch c.txt  
  touch d.txt  
  touch e.txt  
- **List files**: 
  ls
- **List all files (including hidden)**: 
  ls -a

## 3. Staging and Committing Changes
- **Check status of the repository**: 
  git status
- **Add files to the staging area**: 
  git add .
- **Commit changes**: 
  git commit -m "commit message"

## 4. Configuration
- **Set global username**: 
  git config --global user.name "your_username"
- **Set global email**: 
  git config --global user.email "your_email@example.com"

## 5. Managing Files
- **Remove a file from the staging area**: 
  git rm --cached filename
- **Restore a file to the last committed state**: 
  git restore filename
- **Delete a file**: 
  rm filename

## 6. Branching
- **Create and switch to a new branch**: 
  git checkout -b branch_name
- **List branches**: 
  git branch
- **Switch to a branch**: 
  git checkout branch_name

## 7. Viewing History
- **View commit history**: 
  git log
- **View commit history in a compact format**: 
  git log --oneline

## 8. Clearing the Terminal
- **Clear the terminal screen**: 
  clear
