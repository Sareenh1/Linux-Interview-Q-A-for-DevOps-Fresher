# Linux Interview Questions and Answers for DevOps Freshers

This document provides a list of common Linux interview questions and answers for DevOps freshers, helping you prepare for your interviews.

---

### 1. What is Linux and why is it important in DevOps?  
Linux is an open-source operating system known for stability, security, and scalability. It's popular in DevOps for compatibility with various tools, scripting, and use in containerization and virtualization.

### 2. Basic Linux Commands Every DevOps Engineer Should Know  
- `ls`: List files/directories  
- `cd`: Change directory  
- `pwd`: Show current path  
- `cp`: Copy files/directories  
- `mv`: Move or rename files/directories  
- `rm`: Remove files/directories  
- `cat`: View file content  
- `grep`: Search for patterns  
- `chmod`: Change file permissions  
- `ps`: Display running processes  

### 3. Difference Between `apt` and `yum`  
- `apt`: Used in Debian-based systems (e.g., Ubuntu).  
- `yum`: Used in RedHat-based systems (e.g., CentOS).  
Both install, update, and manage packages but use different formats (`.deb` vs `.rpm`).

### 4. File Permissions in Linux and How to Change Them  
- **Read (r)**: View file content  
- **Write (w)**: Modify file  
- **Execute (x)**: Run file as a program  
Change permissions using: `chmod 755 filename`

### 5. What is `/etc/passwd`?  
Stores information about all user accounts, including username, UID, GID, home directory, and shell.

### 6. Checking Disk Usage in Linux  
- `df -h`: Show disk space usage  
- `du -h`: Show file/directory usage  

### 7. Process vs Thread  
- **Process**: Independent program with its own memory.  
- **Thread**: Lightweight sub-process sharing memory space.  

### 8. View Running Processes  
- `ps aux`: Shows all processes  
- `top`: Real-time system processes  
- `htop`: Enhanced version of `top` (needs installation)

### 9. Difference Between `cron` and `at`  
- `cron`: Schedule recurring tasks  
- `at`: Schedule one-time tasks  
Example: `0 5 * * * /path/to/script.sh` (Runs at 5 AM daily)

### 10. What is a Shell Script?  
A file with a series of commands. Used for automating tasks like deployments and system monitoring.

### 11. Use of `ssh` in Linux  
Secure remote login and command execution over a network, essential for managing servers.

### 12. Finding Files on Linux  
Use `find`: `find /path/to/search -name "filename"`

### 13. What is a Symbolic Link?  
A shortcut pointing to another file/directory. Created using: `ln -s target linkname`

### 14. Hard Link vs Symbolic Link  
- **Hard Link**: Directly links to file's inode; persists if the original file is deleted.  
- **Symbolic Link**: Points to file's path; becomes invalid if the original is deleted/moved.  

### 15. Handling Package Management  
- `apt` (Debian): `sudo apt update && sudo apt install nginx`  
- `yum` (RedHat): `sudo yum install nginx`

### 16. Purpose of `/var` Directory  
Stores variable files (logs, spools, cache).

### 17. Killing a Process in Linux  
Use `kill <PID>`. Force kill: `kill -9 <PID>`

### 18. What is a Daemon?  
Background process running continuously (e.g., managing services).

### 19. Environment Variables and Setting Them  
Dynamic values affecting running processes. Set using:  
```bash
export MY_VAR="Hello"
echo $MY_VAR
