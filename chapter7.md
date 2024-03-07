## How to Modify and Fix Your Commits  

### Fix a Commit Mistake with Git Amend

+ Importance of Commits: Commits in Git capture project snapshots at specific points in time.  
+ Commit ID Components: Author, timestamp, commit message, changes made, and preceding commits contribute to the commit ID.  
+ Modifying Commits Locally: Safe if commits are only local and not pushed to a shared repository.  

Use of **git amend** :  

+ Corrects mistakes in the latest commit.
+ Changes the commit message or content.
+ Generates a new commit ID.
+ Git amend is a useful git command to know if you need to quickly change something in your latest commit.  

### Rewrite History with Git Reset  

  Introduction to **Git Reset** :  

+ Offers more robust options for modifying commit history.
+ Provides three options :   
  1. soft  
  2. mixed  
  3. hard  

+ **git reset soft**:
  1. Moves a commit back to the staging area.
  2. Useful for regrouping commits or making alterations before committing.  

+ **git reset mixed**:
   1. Sends changes back to the working directory.
   2. Allows for restaging parts of a commit.  

+ **git reset hard**:
   1. Removes commits from history entirely.
   2. Destructive command, erases changes in staging and working directory.
   3. Requires caution when used.  

### Get Back Deleted History with Git Reflog

Understanding **Git Reflog** :  
+ Tracks movements of the HEAD pointer in local history.
+ Provides a log of recent actions.  
+ We can use the reflog to restore previously committed changes.

Limitations of Reflog:  

+ Local to each user's repository.
+ Retains history for a limited time (default: 90 days).
+ Restoring Commits with git cherry-pick:
+ Copies a commit from the reflog and adds it back into the commit history.
+ Allows retrieval of previously deleted commits.  

