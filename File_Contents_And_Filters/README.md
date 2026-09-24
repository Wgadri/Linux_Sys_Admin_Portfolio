File Content and Filters in Linux

## Objective
This goal of this lab is to learn how to determine, create and manage files in Linux.

## Tools
- Operating System: Ubuntu Linux
- Version Control: Git and GitHub

## Commands

| Command   |             Description                      |
|-----------|----------------------------------------------|
| cat       | Display contents in a text file              |
| head      | Displays first ten lines of a file           |
| tail      | Displays last ten lines of a file            |
| tac   | Display contents in a file in a descending order |
|more && less| Displays file content page by page          |
| tee   | Puts the stdin on stdout and on to a a file      |
| grep | Filters lines of text containing a certain string |
| grep -i  | Filters in a case in-sensitive way            |
| grep -v  | Filters output not matching the the string    |
| cut      | Display selected columns of files             |
| tr      | Translate characters in a file                 |
| wc      | Counts words, characters and lines in a file   |
| sort    | Filters words in alphabetical order            |
| uniq    | Removes duplicates from a sorted list          |
| comm    | Compares contents of files in columns          |
| od    | Displays contents of a file in hexadecimal bytes |
| sed      | Performs editing on contents of a file        |

### Commands Performed

### Displaying contents in a file
To display the contents in a file:
```bash
   cat myfile12.txt
```

### Displaying first ten contents in a file
To display the first ten contents in a file:
```bash
   head myfile12.txt
```

### Displaying last ten contents in a file
To display the last ten contents in a file:
```bash
   tail myfile12.txt
```

### Displaying contents in a file in a descending order
To display the contents of a file in a descending order:
```bash
   tac myfile12.txt
```

### Displaying contents in a file page by page
To display contents in a file  page by page:
```bash
   more myfile12.txt
   less myfile12.txt
```

### Displaying from the stdin and stdout in a file
To display the standard input on the standard output and displaying it or putting it in a file:
```bash
   tac myfile12.txt |tee file12.txt | tac
```

### Filtering  contents in a file
To display the filtered contents in a file using a string:
```bash
   cat file12.txt | grep the
```

### Filtering  contents in a file
To display the filtered contents in a file using a string with case in-sensitivity:
```bash
    grep -i the file12.txt
```

### Filtering  contents in a file
To display the filtered contents in a file not matching the preferred string:
```bash
    grep -v the file12.txt
```

### Notes
- grep -A1 one line after the result is also displayed
- grep -B1 one line before the result is also displayed
- grep -C1 (context) one line before and one after are also displayed


### Filtering  contents in a file
To display the contents of a file by selected columns:
```bash
    cut -d: -f1,3 /etc/passwd | tail -4
    cut -d"" -f1 file12.txt
```

### Translating  contents in a file
To translate the contents in a file :
```bash
    cat file12.txt | tr 'e' E
    cat file12.txt | tr 'a-z' 'A-Z'
    cat file12.txt | tr -d a
```

### Counting  contents in a file
To count the contents in a file :
```bash
    wc file12.txt
    wc -l file12.txt
    wc -w file12.txt
    wc -c file12.txt
```


### Sorting  contents in a file
To sort the contents in a file in alphabetical sorting:
```bash
    sort file12.txt
```

### Removing duplicate from contents in a file
To remove the duplicate contents in a sorted list in a file :
```bash
    sort file12.txt | uniq
    sort file12.txt | uniq -c
```

### Comparing  contents in a file
To compare the contents in a file and output in three columns :
```bash
    comm file12.txt myfile12.txt
```

### Hexadecimal and octal bytes of file contents
To display the contents of a file in hexadecimal and octal bytes:
```bash
    od -t file12.txt
    od -b file12.txt
```

### Editing  contents in a file
To edit the contents in a file using regular expressions:
```bash
    echo level2 | sed 's/2/45/'
    echo level2 | sed 's/level/cap/'
    ```




