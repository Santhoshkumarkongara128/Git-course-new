# Working with Others in a Shared Repository  
### Git on the Network  

+ **Git** operates locally, changes are shared on a network repository.  
+ Git hosting popular platforms : GitHub, GitLab and BitBucket.  
+ Each has a local copy, can push/pull changes offline.  

### Setting up a Remote Repository on GitHub  
+ **GitHub** popular for collaboration.  
+ Create repository, set options.  
+ Link local repository with '**git remote add**'.
+ Verify connection with '**git remote -v**'.  

### Sending Local Commits to the Network
+ Use '**git push**' to send changes and use '**git push -u**'
for first push on a branch.  
Successful push confirms changes sent.  

### Cloning a Git Repository on the Network
+ Copy **GitHub URL**.  
+ Run '**git clone**' URL.  
+ Creates local copy with remote connection.
Work locally, push changes back.  

### Fetching and Pulling Commits From the Network  
+ **git pull** merges changes from network.
+ **git fetch** retrieves changes for review.
+ Check status with '**git status**'.
+ Compare changes with '**git diff**'.  

### Introduction to Merge Strategies  

+ Fast-forward merge for linear paths.
+ Three-way merge for divergent histories.
+ Git rebase for cleaner, linear history.
+ Rebasing alters history, use cautiously.
+ Merge conflicts occur with conflicting changes, must be resolved.
