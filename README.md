# 🐧 Linux Server Configuration

> **Complete Guide to Linux Server Administration - From Basics to Enterprise Services**

[![Stars](https://img.shields.io/github/stars/Taymid/Linux-Server-Configuration)](https://github.com/Taymid/Linux-Server-Configuration/stargazers)
[![Forks](https://img.shields.io/github/forks/Taymmid/Linux-Server-Configuration)](https://github.com/Taymid/Linux-Server-Configuration/network/members)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-20.04+-orange.svg)](https://ubuntu.com)

---

## 📋 Table of Contents

- [About This Repository](#about-this-repository)
- [What You'll Learn](#what-youll-learn)
- [Chapters Overview](#chapters-overview)
- [How to Use This Repository](#how-to-use-this-repository)
- [Quick Commands Reference](#quick-commands-reference)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 About This Repository

This repository provides a **comprehensive guide to Linux server configuration**, covering everything from basic command-line operations to setting up enterprise-grade services.

### 🎯 Why This Repository?

- **Complete Coverage** - From basic commands to advanced server services
- **Hands-On Examples** - Real configuration files and practical examples
- **Ubuntu Focus** - Based on the most popular Linux distribution
- **Production Ready** - Security-focused configurations
- **Troubleshooting Guide** - Common issues and solutions

### 🛠️ Services Covered

| Service | Purpose |
|---------|---------|
| Samba | File & Print Server |
| NFS | Network File System |
| FTP | File Transfer Protocol |
| DHCP | Dynamic Host Configuration |
| Squid | Proxy Server |
| DNS | Domain Name System |
| Apache2 | Web Server |
| MySQL | Database Server |
| Postfix | Mail Server |

---

## 🎓 What You'll Learn

### 🏁 Fundamentals
- Linux command line basics
- File and directory management
- Process management
- Software installation

### 🔧 System Administration
- User and group management
- File permissions and ownership
- Filesystem mounting
- Compressing and archiving

### 🌐 Network Services
- Samba File Server
- NFS
- FTP Server
- DHCP Server
- Squid Proxy
- DNS Server

### 🚀 Web & Database
- Apache2 Web Server
- MySQL Database
- Postfix Mail Server

---

## 📚 Chapters Overview

### Chapter 1: Introduction to UNIX and Linux
- What is Linux?
- History and distributions
- Linux command line basics
- Shell commands

**[View Chapter →](01-Introduction-Linux/)**

### Chapter 2: Files and Directories
- Listing files (`ls`)
- Changing directories (`cd`)
- Creating directories (`mkdir`)
- Working with files (`cat`, `rm`, `cp`, `mv`, `grep`)

**[View Chapter →](02-Files-Directories/)**

### Chapter 3: Process Management
- Process monitoring (`ps`, `pstree`, `top`)
- Signaling processes (`kill`)
- Process priorities (`nice`, `renice`)

**[View Chapter →](03-Process-Management/)**

### Chapter 4: Software Installation
- Using `apt-get`
- Configuring `sources.list`
- Installing `.deb`, `.rpm`, `.bin` files

**[View Chapter →](04-Software-Installation/)**

### Chapter 5: Compressing and Archiving
- `bzip2` / `bunzip2`
- `gzip` / `gunzip`
- `tar` archiving

**[View Chapter →](05-Compressing-Archiving/)**

### Chapter 6: File Ownership and Permissions
- Users and groups
- The superuser (root)
- `chown`, `chgrp`, `chmod`
- Special permissions (sticky, setgid)

**[View Chapter →](06-File-Ownership-Permissions/)**

### Chapter 7: Filesystem Mounting
- `mount` command
- `umount` command
- `/etc/fstab` configuration

**[View Chapter →](07-Filesystem-Mounting/)**

### Chapter 8: User Accounts
- Creating users (`adduser`)
- Changing passwords (`passwd`)
- Group management (`groupadd`, `groupdel`)

**[View Chapter →](08-User-Accounts/)**

### Chapter 9: Samba File Server
- Installation
- Configuration (`smb.conf`)
- Security settings
- Group permissions

**[View Chapter →](09-Samba-File-Server/)**

### Chapter 10: Network File System (NFS)
- Installation
- Server configuration
- Client configuration

**[View Chapter →](10-NFS/)**

### Chapter 11: FTP Server
- vsftpd installation
- Anonymous FTP
- Authenticated FTP
- Security configuration
- FTPS (SSL/TLS)

**[View Chapter →](11-FTP-Server/)**

### Chapter 12: DHCP Server
- Installation
- Configuration
- IP address pools
- MAC address reservations

**[View Chapter →](12-DHCP-Server/)**

### Chapter 13: Squid Proxy Server
- Installation
- Configuration
- Access control
- ACL and time-based rules

**[View Chapter →](13-Squid-Proxy/)**

### Chapter 14: DNS Server
- BIND9 installation
- Caching nameserver
- Primary master
- Secondary master
- Forward/Reverse zones

**[View Chapter →](14-DNS-Server/)**

### Chapter 15: Apache2 Web Server
- Installation
- Basic configuration
- Virtual Hosts
- Modules
- HTTPS/SSL configuration

**[View Chapter →](15-Apache2-Web-Server/)**

### Chapter 16: MySQL
- Installation
- Configuration
- Security setup

**[View Chapter →](16-MySQL/)**

### Chapter 17: Postfix Mail Server
- Installation
- Basic configuration
- SMTP-AUTH
- TLS/SSL
- Troubleshooting

**[View Chapter →](17-Postfix-Mail-Server/)**

---

## 🚀 How to Use This Repository

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/Linux-Server-Configuration.git
cd Linux-Server-Configuration
