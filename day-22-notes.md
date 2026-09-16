# Day 22 Git Notes

## 1. What is the difference between `git add` and `git commit`?

`git add` moves my changes from the working directory into the staging area.

`git commit` takes the staged changes and saves them as a permanent snapshot in the Git repository.

## 2. What does the staging area do? Why doesn't Git just commit directly?

The staging area lets me choose exactly which changes I want to include in the next commit.

Git does not commit everything directly because I may have several changes but only want to save some of them in one commit.

## 3. What information does `git log` show you?

`git log` shows the commit history of the repository.

It can show the commit ID, author, date, commit message, and which commit I am currently on.

## 4. What is the `.git/` folder and what happens if you delete it?

The `.git/` folder contains Git's repository information, including commits, branches, configuration, references, and other Git data.

If I delete `.git/`, the project files remain, but the directory is no longer a Git repository and the previous Git history is lost from that directory.

## 5. What is the difference between a working directory, staging area, and repository?

The working directory contains the files I am currently editing.

The staging area contains the changes I have selected using `git add`.

The repository contains the commits that have been permanently saved.
