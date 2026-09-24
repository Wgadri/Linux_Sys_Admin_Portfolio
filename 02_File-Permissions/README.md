# File Permission in Linux

## Objective
This lab focuses on understanding how Linux manages file permissions and ownership, and how those settings affect access to files and directories.

## Environment
- Operating System: Ubuntu Linux
- Version Control: Git and GitHub

## Commands Practiced

| Command | Description                             |
|---------|-----------------------------------------|
| ls -l   | Displays file permissions and ownership |
| chmod   | Modifies file permissions               |
| chown   | Changes the owner of a file or directory|
| chgrp   | Changes the group ownership of a file   |

### Tasks Completed

## 1. Created Practice Files
I created the following file for practice:
- practice.txt


## 2. Viewed File Permissions
I checked the default permission settings for the practice files using:
```bash
ls -l
```

### 3. Applied Numeric Permissions

The file was assigned the following permission values:

-  chmod 755 practice.txt
-  chmod 600 practice.txt
-  chmod 640 practice.txt

These commands were used to practice how permissions can be adjusted for the owner, group, and other users.


