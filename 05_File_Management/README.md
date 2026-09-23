File Management in Linux

## Objective
This goal of this lab is to learn how to determine, create and manage files in Linux.

## Tools
- Operating System: Ubuntu Linux
- Version Control: Git and GitHub

## Commands

| Command |            Purpose                                       |
|---------|----------------------------------------------------------|
| file    | Shows the file type                                      |
| touch   | Creates an empty file                                    |
| touch -t | Set properties while creating empty file                |
| rm      | Delete a file                                            |
| rm -i   | Deletes a file with interactive confirmation              |
| rm -rf  | Delete an non-empty directory by force                    |
| cp      | Copy a file and directories                              |
| cp -i   | Copying a file with interactive confirmation to prevent overwriting |
| mv     | Rename a file or move the file to another directory       |
| mv -i  | Interactive confirmation to overwrite an existing file    |

### Command Practice

### To view type of file
To determine the type of file :
```bash
   file /etc/passwd
```

### To create an empty file
To create an empty file :
``` bash
  touch file32.txt
```

### To create an empty file with properties
To create an empty file with some properties :
``` bash
  touch -t 200505050000 fileChamp.txt
```

### To delete a file
To delete a file :
``` bash
  rm file32.txt
```

### To delete a file with confirmation
To delete a file with an interactive confirmation to prevent accidental file removal :
``` bash
  rm -i file12.txt
```

### To delete a directory by force
To delete a non-empty directory by force :
``` bash
  rm -rf test
```

### To copy  file
To duplicate an existing file and directory:
``` bash
  cp fileChamp.txt fileFun.txt
  cp test1
```

### To copy file with interactive confirmation
Copying a file with interactive confirmation to prevent overwriting existing files :
``` bash
  cp -i fileChamp.txt fileChamp12.txt
```

### To rename a file
Renaming a file or moving the file to another directory :
``` bash
  mv fileChamp12.txt funFact3.txt
```

### To rename a file with interactive confirmation
Renaming a file with interactive confirmation to ask permission to overwrite an existing file:
``` bash
  mv -i myFile22.txt funFact3.txt
```

### ScreenShot