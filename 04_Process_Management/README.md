# Process Management in Linux

## Objective
This lab focuses on comprehending how Linux manage processes and how to monitor and terminate processes.

# Tools
- Operating System: Ubuntu Linux
- Version Control: Git and GitHub

# Commands Practiced

| Command | Description                                              |
|---------|----------------------------------------------------------|
| ps      | Display running processes                                |
| ps aux  | Display detailed information about all running processes |
| top     | Monitor processes in real time                           |
| sleep   | Create a temporary background process                    |
| pgrep   | Find a process by name                                   |
| kill    | Terminate a running process                              |

## Commands completed

## 1. Viewed Running Processes
 To study the running processes and understand process information like PID, CPU usage , and memory usage:
```bash
  ps
  ps aux | head -20
```

## 2. Monitored Processes
To view the running processes in real time:
```bash
   top
```

### 3. Creating Background Process
To start a background process:
```bash
 sleep 300 &
```

### 4. Located the Process
To identify background process by its process ID:
```bash
  pgrep sleep
```

### 5. Terminating a Process
To kill a process successfully
```bash
   kill <PID>
```

### Screenshot
