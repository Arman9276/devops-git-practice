# Git Commands Reference

## Setup & Config

### git --version
Checks the installed Git version.

Example:
```bash
git --version

### git diff
Shows unstaged changes in the working directory.

Example:
```bash
git diff

### git status
Shows the current state of the working directory and staging area.

Example:
```bash
git status

### git log --oneline
Shows commit history in a compact one-line format.

Example:
```bash
git log --oneline

# Git Branching Commands

# List branches
git branch

# Create a new branch
git branch feature-1

# Switch to an existing branch
git switch feature-1

# Create and switch to a new branch
git switch -c feature-2

# Switch back to main
git switch main

# View commit history of all branches
git log --oneline --decorate --all

# Check working tree status
git status

# Delete a branch safely
git branch -d feature-2

# Push a branch to GitHub
git push -u origin feature-1

# Push main to GitHub
git push -u origin main

# Fetch changes from remote
git fetch

# Pull changes from remote
git pull
