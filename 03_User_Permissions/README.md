# User Permission Management

## Objective

This lab focuses on creating Linux users and groups, assigning users to specific groups, and managing file ownership and permissions to control access effectively.

## Environment

- Operating System: Ubuntu Linux
- Version Control: Git and GitHub

## Commands Practiced

| Command | Description                              |
|----------|-----------------------------------------|
| useradd  | Creates a new user                      |
| groupadd | Creates a new group                     |
| usermod  | Modifies a user account                 |
| groups   | Displays the groups a user belongs to   |
| chown    | Changes file ownership                  |
| chmod    | Changes file permissions                |
| ls -l    | Displays file permissions and ownership |

## Tasks Completed

### 1. Created Users

I created two practice users:

- 
- 

Their accounts were then verified using:

```bash
cat /etc/passwd | tail
```

### 2. Created a Group

A new group was created for the practice users:

```

```

Both users were then added to the same group using:

```bash
sudo usermod -aG sysadmins 
sudo usermod -aG sysadmins 
```

Group membership was verified with:

```bash
groups 
groups 
```

### 3. File Ownership

A sample file was created and its ownership was changed to:

- Owner: 
- Group: 

using:

```bash
sudo chown :
```

### 4. File Permissions

The following permissions were assigned:

```text
640
```

This configuration means:

- Owner: Read and Write
- Group: Read only
- Others: No access

### Permission Assignments
- Read - 4
- Write - 2
- Execute - 1