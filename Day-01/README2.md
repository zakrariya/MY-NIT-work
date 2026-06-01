# NIT Academy - Linux Journey (Day 1)

**Student Name:** Zakariya Hamid
**Date:** 9 May 2026
**Course:** Linux Fundamentals - NIT Academy

---

# Table of Contents

1. Introduction
2. Accessing the Virtual Machine
3. Understanding the Linux Shell
4. First Linux Commands
5. GitHub Account Setup
6. LinkedIn Profile Update
7. Git Bash Installation
8. Visual Studio Code Installation
9. Discord Setup
10. Key Learnings
11. Screenshots
12. Conclusion

---

# Introduction

This document summarizes the activities completed during Day 1 of the NIT Academy Linux training program. The objective was to gain familiarity with Linux environments, virtual machines, command-line interfaces, GitHub, Git Bash, Visual Studio Code, and Discord.

---

# Accessing the Virtual Machine

A Linux virtual machine was accessed through Xen-Orchestra. After successfully logging in, the VM console was explored and basic system configuration commands were executed.

## Commands Executed

```bash
sysctl -w net.ipv6.conf.all.disable_ipv6=1
sysctl -w net.ipv6.conf.default.disable_ipv6=1
```

## Purpose

* Disable IPv6 networking.
* Prepare the virtual machine environment for future networking labs.
* Understand basic system configuration.

---

# Understanding the Linux Shell

The Linux Shell serves as the interface between the user and the operating system.

## Components

### Shell

The environment where commands are entered.

### Interpreter

Translates user commands into instructions understood by the operating system.

### Command Line

The location where commands are typed and executed.

Example:

```bash
whoami
```

---

# First Linux Commands

The following commands were introduced and practiced.

| Command     | Purpose                     |
| ----------- | --------------------------- |
| whoami      | Display current user        |
| pwd         | Show current directory      |
| ls          | List files and directories  |
| date        | Show system date and time   |
| clear       | Clear terminal screen       |
| ip a        | Display network information |
| hostnamectl | Show system details         |
| uptime      | Show system uptime          |
| passwd      | Change password             |
| exit        | Exit shell                  |

## Examples

### Display Current User

```bash
whoami
```

### Display Current Directory

```bash
pwd
```

### List Files

```bash
ls -l
```

### Display System Uptime

```bash
uptime
```

---

# GitHub Account Setup

A GitHub account was created and configured for version control and project management.

## Steps Completed

* Created GitHub account
* Verified email address
* Logged in successfully
* Created first repository
* Added README file

## GitHub Profile

Add your GitHub profile link below:

```text
https://github.com/your-username
```

---

# LinkedIn Profile Update

LinkedIn profile was reviewed and updated to reflect current educational background, technical skills, and career interests.

## Improvements Made

* Updated profile photo
* Added educational information
* Added technical skills
* Updated headline and summary

---

# Git Bash Installation

Git Bash was installed on Windows and configured successfully.

## Verification

```bash
git --version
```

## Git Configuration

```bash
git config --global user.name "Zakariya Hamid"
git config --global user.email "your-email@example.com"
```

## Verify Configuration

```bash
git config --list
```

---

# Visual Studio Code Installation

Visual Studio Code was installed as the primary code editor.

## Benefits

* Syntax highlighting
* Git integration
* Extensions support
* Terminal integration

---

# Discord Setup

Discord was installed and the NIT Academy server was joined successfully.

## Purpose

* Communication with instructors
* Collaboration with fellow learners
* Sharing assignments and resources

---

# Key Learnings

During Day 1, I learned:

* How to access a Linux virtual machine
* The role of the Linux Shell
* Basic Linux commands
* GitHub account creation and repository management
* Git Bash installation and configuration
* Visual Studio Code setup
* Discord setup for communication

---

# Screenshots

## Virtual Machine Login

Insert screenshot here:

```text
screenshots/vm-login.png
```

## Running whoami Command

Insert screenshot here:

```text
screenshots/whoami.png
```

## Running pwd Command

Insert screenshot here:

```text
screenshots/pwd.png
```

## Running ls -l Command

Insert screenshot here:

```text
screenshots/ls-command.png
```

## GitHub Repository

Insert screenshot here:

```text
screenshots/github-repository.png
```

---

# Conclusion

Day 1 provided a strong foundation in Linux fundamentals and essential development tools. The hands-on activities improved my understanding of virtual machines, Linux command-line operations, GitHub, Git Bash, Visual Studio Code, and collaborative communication platforms. These skills will serve as the foundation for future Linux and DevOps learning.
