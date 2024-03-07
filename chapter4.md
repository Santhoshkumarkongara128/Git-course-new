## Working in a Local Repository  

### Adding Git to an Existing Project

+ Initialize **Git** in your project directory using '**git init**'.  
+ Use '**git add**' to start tracking files either individually or with '**git add .**' for all files.  
+ Commit changes with '**git commit -m "commit message"** '.
### Making Changes to Files  

+ Modify files in your working directory.
+ Use '**git add**' to stage changes for commit.  
+ Commit changes with '**git commit -m "commit message"** '.  
### Creating a New Branch  

+ Create a new branch with '**git branch branch_name**'.  
+ Checkout to the new branch with '**git checkout branch_name**'.  
+ Optionally, combine branch creation and checkout to branch with '**git checkout -b branch_name**'.  
### Viewing the Different File Statuses  

+ Check the status of files with '**git status**'.  
+ View changes in the working directory with '**git diff**'.  
+ Compare staged changes with '**git diff --staged**'.  

### Merging a Branch into Another Branch  

+ Checkout to the branch you want to merge into (**git checkout main**).  
+ Merge the other branch into the current branch (**git merge branch**) to merge.  
+ Resolve any merge conflicts if necessary.
### Viewing Your Commit History

+ See a log of commits with '**git log**'.  
+ Use '**git log --oneline**' for a simplified view.  
+ Visualize branch history with '**git log --oneline --graph**'.  
### Deleting a Branch

+ Remove a branch with '**git branch -d branch_name**'.  
+ Confirm deletion with '**git branch -a**'.