# Package Management

## Objective

The goal of this lab is to learn how to download and manage software packages in Linux. Updating packages, installing software and removing packages are also focused in this lab.

## Environment
- Operating System: Ubuntu Linux
- Version Control: Git and GitHub

## Commands

| Command         | Description                  |
|-----------------|------------------------------|
| sudo apt update | Update package lists         |
| apt list --upgradable | View available package updates |
| apt search | Search for packages |
| apt show | Display package information |
| sudo apt install | Install a package |
| apt list --installed | Verify installed packages |
| sudo apt remove | Remove a package |

## Task

## Updated Package List
```bash
   sudo apt update
   ```

   ## Checked for Available Updates
   ```bash
   apt list --upgrade
   ```

   
###  Searched for a Package

```bash
apt search htop
```

Located the `htop` package in the Ubuntu repositories.

###  Viewed Package Details

```bash
apt show htop
```

Displayed version, maintainer, dependencies, and package description.

###  Installed the Package

```bash
sudo apt install htop
```

Installed the `htop` system monitoring utility.

###  Verified Installation

```bash
apt list --installed | grep htop
```

Confirmed that `htop` had been installed successfully.


###  Removed the Package

```bash
sudo apt remove htop
```

Removed the package from the system.