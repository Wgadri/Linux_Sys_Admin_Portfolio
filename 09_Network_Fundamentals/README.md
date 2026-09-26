# Network Fundamentals in Linux

## Objective

The goal of this lab is to learn the basics of networking commands in Linux used for troubleshooting connectivity, identifying network services and network configurations.

# Environment
- Operating System: Ubuntu Linux
- Version Control: Git and GitHub

## Commands

| Command | Purpose |
|---------|---------|
| ip addr | Display network interfaces and IP addresses |
| hostname -I | Display system IP address |
| ping | Test network connectivity |
| nslookup | Check DNS resolution |
| ip route | Display routing table |
| ss -tuln | Display listening network ports |



###  Viewed Network Interfaces

This command is used to identify network interfaces and assigned IP addresses.

```bash
ip addr
```


###  Checked IP Address
This command is used as a quick way to display the machine's IP address.
```bash
    hostname -I
```



### Tested Connectivity
This command is used to verify whether the system could communicate with an external host.
```bash
    ping google.com
```



###  Checked DNS Resolution
This command is used to confirm that domain names can be translated into IP addresses.
```bash
   nslookup google.com
```



###  Viewed Routing Information
This command is used to view the paths Linux uses to send network traffic.
```bash
   ip route
```



###  Checked Listening Ports
This command used to identify active listening network ports and services.
```bash
   ss -tuln
```

