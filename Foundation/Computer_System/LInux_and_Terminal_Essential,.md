# Topic 02: Linux and Terminal Essentials

A comprehensive guide to navigating, managing files, controlling processes, and writing basic shell scripts in a Linux environment (Linux Mint).

---

## 1. Navigation & File Management
* `pwd`: Prints the current working directory path.
* `ls -la`: Lists all files (including hidden ones) with detailed permissions.
* `cd <folder>`: Changes the current active directory.

## 2. File Permissions (`chmod`)
* Permissions are divided into **Read (r)**, **Write (w)**, and **Execute (x)** for User, Group, and Others.
* `chmod +x script.sh`: Grants execution permission to a shell script.

## 3. Streams, Redirection & Pipes
* **`>`**: Overwrites output to a file.
* **`>>`**: Appends output to a file.
* **`|` (Pipe):** Sends the output of one command as the input to another (e.g., `ps aux | grep python`).

## 4. Process Inspection & Management
* `top` / `htop`: Real-time view of running processes, CPU, and RAM usage.
* `kill <PID>`: Terminates a running process using its Process ID.

## 5. Environment Variables
* `printenv`: Displays current environment variables.
* `export KEY="value"`: Sets a temporary environment variable for the current session.

## 6. Package Management (APT)
* `sudo apt update`: Refreshes package lists.
* `sudo apt install <package>`: Installs new software packages on Debian/Ubuntu/Linux Mint systems.

## 7. Shell Scripting Basics
* Scripts start with the Shebang line: `#!/bin/bash`.
* Automated sequences of terminal commands saved in a `.sh` file.

## 8. Exit Codes
* `$?`: Returns the exit status of the last executed command.
* `0` indicates success; any non-zero value indicates an error.

## 9. Basic SSH
* Used for secure remote login and communication with servers using public-private key pairs (`ssh user@host`).s