# Thinking in Git  
## What Is Git?
+ Git is a version control system (VCS) that tracks changes in project files over time.
It allows users to revert to previous versions, making it like a "time machine" for project files.Git can manage various file types, not just source code files.

## Types of Version Control Systems

+ Local: Simple and lightweight but lacks collaboration features.
+ Centralized: Relies on a central server, vulnerable to server failures.
+ Distributed (Git): Copies entire project histories to each developer's machine, eliminating dependency on a central server.

## Characteristics of Git

+ Snapshots: Stores complete snapshots of the project at each commit.
+ Optimized for local development: Allows disconnected work with full project history.
+ Explicit: Requires explicit commands for actions, providing control and intentionality.
+ Non-linear development: Supports branching and merging for parallel development paths.

## File Statuses in Git

+ Tracked vs. Untracked files: Git tracks changes only in tracked files.
+ File Statuses: Unmodified, Modified, and Staged.
+ Staging Area: Allows selective inclusion of changes before committing.

## Directories in Git

+ Git directory: Stores metadata and project history.
+ Working directory: Where modifications are made to project files.
+ Staging area (Index or Cache): Holds files ready to be committed.
## Introduction to Common Git Commands 
### Git Basics

1.  git init: Initializes a new Git repository.
1. git add: Moves modified files to the staging area.
1. git status: Shows the status of files in the working directory and staging area.
1. git commit: Records changes in the repository.
1. git config: Sets or reads Git configurations.
1. git log: Displays commit history logs.
### Git Branches

1. git branch: Lists, creates, or deletes branches.
1. git checkout: Switches branches or creates and checks out to a new branch.
1. git merge: Merges changes from one branch into another.
### Remote Repositories

1. git clone: Copies a repository to a local directory.
1. git remote: Shows tracked repositories linked to the local copy.
1. git push: Sends updates from local repository to associated remote repositories.
1. git pull: Retrieves changes from a remote repository and merges into the local repository.
1. git fetch: Retrieves changes from a remote repository without merging.
### Undoing Changes

1. git revert: Safely reverts changes from a previous commit.
1. git reset: Resets file changes in the staging area or working directory, potentially destructive.