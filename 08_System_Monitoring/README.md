# System Monitoring in Linux

## Objective

The goal of this lab is to learn how to monitor the performance and health of the system. Some processes involve checking memory usage, disk usage, CPU information, system uptime and storage consumption.

## Environment
- Operating System: Ubuntu Linux
- Version Control: Git and GitHub

## Commands

| Command | Purpose |
|---------|---------|
| uptime | Shows system uptime and load average |
| free -h | Displays memory usage in human-readable format |
| df -h | Shows disk space usage |
| who | Displays logged-in users |
| whoami | Shows the current user |
| id | Displays user and group information |
| lscpu | Displays CPU information |
| top | Monitors running processes and system resources |
| du -h | Shows directory sizes |


## Task

###  Checked System Uptime

Command:

```bash
uptime
```

Used to view how long the system has been running and check system load averages.

###  Checked Memory Usage

Command:

```bash
free -h
```

The `-h` option displays memory values in a human-readable format such as MB and GB.

###  Checked Disk Usage

Command:

```bash
df -h
```

Used to check available and used disk space.

###  Checked User Information

Commands:

```bash
whoami
id
```

Used to identify logged-in users and display account information.

###  Checked CPU Information

Command:

```bash
lscpu
```

Used to view processor architecture, cores, threads, and CPU details.

###  Monitored Running Processes

Command:

```bash
top
```

Used for real-time monitoring of CPU, memory, and running processes.

###  Checked Directory Sizes

Command:

```bash
du -h --max-depth=1
```

Used to identify how much storage directories consume.