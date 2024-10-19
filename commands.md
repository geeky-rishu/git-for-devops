# Git Commands Reference

## Git Basics
- **Initialize a new repository:**  
  `git init`

- **Check the status of the repository:**  
  `git status`

- **Add a file to staging:**  
  `git add <filename>`

- **Commit changes:**  
  `git commit -m "Commit message"`

## File Management
- **Remove a file from staging:**  
  `git rm --cached <filename>`

- **Restore a deleted file:**  
  `git restore <filename>`

## Branching
- **List all branches:**  
  `git branch`

- **Create a new branch:**  
  `git branch <branch-name>`

- **Switch to a branch:**  
  `git checkout <branch-name>`

- **Merge a branch into the current branch:**  
  `git merge <branch-name>`

## Viewing Changes
- **View commit history:**  
  `git log`

- **Show changes between commits:**  
  `git diff`

## Remote Repositories
- **Add a remote repository:**  
  `git remote add origin <repository-url>`

- **Push changes to a remote repository:**  
  `git push origin <branch-name>`

- **Pull changes from a remote repository:**  
  `git pull origin <branch-name>`

## Miscellaneous
- **View the current branch:**  
  `git branch --show-current`

- **Check for untracked files:**  
  `git status -u`

- **Clone a repository:**  
  `git clone <repository-url>`
