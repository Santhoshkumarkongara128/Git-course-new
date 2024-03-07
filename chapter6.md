## Merge Conflicts : What are they and How can we resolve them  

### Understanding Merge Conflicts  

+ Merge conflicts occur when conflicting changes are made to the same part of a file by different users.
+ Common Situations :  
  1. Multiple people edit the same line in a file.   
  2. One person deletes content, another edits it.  
  3. One person deletes a file, another edits its contents.  
+ Git's Response: Notifies users of conflict, requires manual resolution.  
### Creating a Merge Conflict  

 + Multiple users make changes to the same file.

### Resolving a Merge Conflict  

 + Git informs users of the conflict, specifies conflicted files.  
 + Steps to recover :  
    1. Open conflicted file in text editor.  
    2. Identify and remove conflict markers.  
    3. Choose which changes to keep or discard.  
    4. Save changes, add file to staging area, and commit.
    5. Discuss changes with the team and collabarate with team if needed before resolution.  

### Preventing Merge Conflicts  

+ Enforce consistent formatting rules to avoid conflicts due to formatting differences.  
+ Make smaller, more direct changes and merge them frequently to reduce the likelihood of conflicts.  
+ Keep communication channels open within the team to coordinate changes and avoid conflicts.  
+ Be aware of who is working on what to minimize overlapping edits.