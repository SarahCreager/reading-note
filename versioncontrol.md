# What is Version Control?
Version Control allows you to access various versions of a file. You can revert a file back to a previous version and track changes. 

### Local Version Control (LVCS)
Local Version Control is one database that stores all the changes made to a file.

### Centralized Version Control (CVCS)
Centralized Version Control allows a team to work on a file by storing all the changes and versions to a single server that can be accessed by multiple people. But, if a CVCS goes down, the team cannot work together on the file or save changes. If a file is lost, it cannot be retrieved unless there are portions saved on local devices. 

### Distributed Version Control (DVCS)
Distributed Version Control accounts for this flaw in CVCS. DVCS allows collaborators to create mirrored repositories, which allows for multiple simultaneous workflows. These backups are placed on the server to replace any lost data. 

# What is Git?
Git is a type of Distributed Version Control System. Every time you save a change to your project or *commit*, Git creates a snapshot of the file and stores a reference of it. Every change to a file is tracked. Git helps detect any file corruption as well as minimizing the risk of losing a file. 

### Files in Git are placed into 3 stages:

**Modified**:
  The file has been changed but not committed.
  
**Staged**:
  The file's changed version is to be committed in the next snapshot.

**Committed**:
  Data is stored in a local database. 
  
#### Example
```
1. Once you edit a file, it gets flagged as modified.
2. The modified file is staged.
3. You then commit the changes that have been staged.
```
  
### Local Git Repository Structure
1. Working Directory: The files reside here.
2. Index: This area is used for staging.
3. Head: The most recent commit. 

### Tracked vs. Untracked
**Tracked**: These files can be modified, unmodified, or staged. They are part of the most recent snapshot.

**Untracked**: These files were not in the latest snapshot. They are not in the staging area. 

[Back to Homepage](README.md)
