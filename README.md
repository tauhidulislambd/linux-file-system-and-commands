```markdown
# Linux File System & Essential Commands

## 📌 Overview

Linux uses a hierarchical file system. The top-level directory is `/`, known as the root directory. All files and directories are organized under this root.

## 📂 Linux File System Structure

/
├── bin
├── boot
├── dev
├── etc
├── home
├── lib
├── media
├── mnt
├── opt
├── proc
├── root
├── run
├── sbin
├── srv
├── sys
├── tmp
├── usr
└── var

## 📁 Important Linux Directories

| Directory | Purpose |
|---|---|
| `/` | Root of the Linux filesystem |
| `/home` | Personal directories of normal users |
| `/root` | Home directory of the root user |
| `/etc` | System and application configuration files |
| `/var` | Variable data such as logs and caches |
| `/var/log` | System and application log files |
| `/tmp` | Temporary files |
| `/usr` | User-space programs, libraries and documentation |
| `/usr/bin` | Common user commands and programs |
| `/usr/sbin` | System administration programs |
| `/opt` | Optional or third-party software |
| `/proc` | Virtual filesystem containing process and kernel information |
| `/dev` | Device files |
| `/boot` | Files required for system boot |
| `/sys` | Kernel and device information |

## 🔐 Directories Useful for Cybersecurity Practice

The following directories are useful when learning Linux and cybersecurity in an authorized lab environment:

- `/etc` — Configuration files and security-related settings
- `/var/log` — System and application logs
- `/home` — Users, files and permissions
- `/root` — Privileged-user environment
- `/tmp` — Temporary files and permissions
- `/usr/bin` — Common command-line tools
- `/usr/sbin` — System administration tools
- `/opt` — Optional and third-party applications
- `/proc` — Processes and system information
- `/dev` — Linux device files

> **Note:** Security testing should only be performed on systems you own or are explicitly authorized to test.

## 🐧 Essential Linux Commands

### Navigation

- `pwd` — Show current directory
- `ls` — List files and directories
- `cd` — Change directory

### File and Directory Management

- `mkdir` — Create a directory
- `touch` — Create an empty file
- `cp` — Copy files or directories
- `mv` — Move or rename files
- `rm` — Remove files or directories

### Viewing Files

- `cat` — Display file contents
- `less` — View file contents page by page
- `head` — Display the beginning of a file
- `tail` — Display the end of a file

### Searching

- `find` — Search for files and directories
- `grep` — Search for text patterns

### Permissions and Ownership

- `ls -l` — View file permissions
- `chmod` — Change file permissions
- `chown` — Change file ownership

### System Information

- `whoami` — Display the current username
- `id` — Display user and group information
- `hostname` — Display the system hostname
- `uname -a` — Display system information

### Disk and Storage

- `df -h` — Display disk space usage
- `du -sh` — Display directory size
- `lsblk` — Display block devices

### Processes

- `ps` — Display running processes
- `top` — Monitor running processes

## 🧪 Examples

### Check the Current Directory

`pwd`

### List the Root Directory

`ls -l /`

### Move to the `/etc` Directory

`cd /etc`

### Find Text Files in the Home Directory

`find /home -name "*.txt"`

### Search for an Error in a Log File

`grep "error" logfile.txt`

### Check File Permissions

`ls -l filename.txt`

## 🎯 Learning Objective

The purpose of this repository is to document my Linux learning journey and provide a simple reference for Linux file system concepts and essential commands used in cybersecurity and ethical hacking practice.

## 👨‍💻 Author

**Md Tauhidul Islam**

Admin & Operations Professional | ISPS & Shipping Security | Cyber Security & Ethical Hacking Learner
