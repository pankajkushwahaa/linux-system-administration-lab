# Package Management

## Objective

This lab demonstrates package management on Ubuntu and CentOS. It includes updating repositories, installing, upgrading, removing, and searching for software packages using native package managers.

## Topics Covered

- Updating package repositories
- Installing packages
- Removing packages
- Upgrading installed packages
- Searching packages
- Displaying package information
- Listing installed packages

## Environment

- Ubuntu (WSL)
- CentOS (VirtualBox)

## Package Managers

- APT (Ubuntu)
- DNF (CentOS)

## Skills

- Linux
- Package Management
- Ubuntu
- CentOS
- Troubleshooting



## Troubleshooting

### Problem

Package not found.

### Possible Causes

- Repository index is outdated.
- Incorrect package name.
- Network connectivity issue.

### Solution

```bash
sudo apt update
apt search <package-name>
```