# Linux Interview Questions and Answers for DevOps Freshers

This document provides common Linux interview questions and answers for DevOps freshers, helping them prepare for their interview.

---

### 1. What is Linux and why is it important in DevOps?

Linux is an open-source operating system that provides a stable, secure, and scalable environment for software development and deployment. It is widely used in DevOps because of its compatibility with a variety of tools, ability to automate tasks via scripts, and its lightweight nature for containerization and virtualization.

---

### 2. What are the basic Linux commands every DevOps engineer should know?

- `ls`: Lists files and directories.
- `cd`: Changes the current directory.
- `pwd`: Prints the current directory path.
- `cp`: Copies files or directories.
- `mv`: Moves or renames files or directories.
- `rm`: Removes files or directories.
- `cat`: Concatenates and displays file content.
- `grep`: Searches for patterns in files.
- `chmod`: Changes file permissions.
- `ps`: Displays running processes.

---

### 3. Explain the difference between `apt` and `yum`.

`apt` (Advanced Packaging Tool) is the package manager for Debian-based distributions like Ubuntu, while `yum` (Yellowdog Updater Modified) is used for RedHat-based distributions like CentOS and Fedora. Both are used to install, update, and manage software packages, but they work with different package formats (`.deb` for `apt` and `.rpm` for `yum`).

---

### 4. What are file permissions in Linux and how do you change them?

File permissions determine who can read, write, or execute a file. There are three types of permissions:
- **Read (r)**: Allows viewing the file content.
- **Write (w)**: Allows modifying the file.
- **Execute (x)**: Allows running the file as a program.

Each file has permissions for three entities:
- **Owner**
- **Group**
- **Others**

Permissions can be changed using the `chmod` command, for example:
```bash
chmod 755 filename
