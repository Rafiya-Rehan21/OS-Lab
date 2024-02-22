# Linux Overview 


![[Pasted image 20240127225321.png|200]]

Session: 2022-2026

### Submitted By:
Rafiya Rehan      2022-CS-182

### Submitted To:
Mr. Nauman Shafi


Department of Computer Science

### University of Engineering and Technology
### Lahore Pakistan
---
# Basic Linux Commands

First, some basic Linux commands are executed.
Below is a brief detail about these commands along with screenshots.

### echo Command
Echo command is used to display text or output to the terminal.

![[Screenshot from 2024-02-10 19-16-22.png|500]]

### pwd Command
The pwd command in Linux stands for "Print Working Directory." It is used to display the current working directory, which is the directory you are currently in within the file system.

![[Screenshot from 2024-02-10 19-17-50.png|500]]

### ls Command
The ls command in Linux is used to list files and directories in the current directory or a specified directory.

![[Screenshot from 2024-02-10 19-18-33.png|500]]

### mkdir Command
Mkdir is used to make directories.

![[Screenshot from 2024-02-10 19-19-32.png|500]]

This command also takes given below syntax.

![[Screenshot from 2024-02-10 19-21-31.png|500]]


### cd Command
The cd command in Linux is used to change the current working directory. It allows you to navigate through the directory structure of the file system.

![[Screenshot from 2024-02-10 19-20-17.png|500]]

---
# Absolute and Relative Paths
In Linux, both absolute and relative paths are ways to specify the location of a file or directory in the file system.
### Absolute Paths
An absolute path provides the complete path from the root directory to the specified file or directory.

![[Screenshot from 2024-02-10 19-27-53.png|500]]

### Relative Paths
A relative path specifies the location of a file or directory relative to the current working directory.
It does not start from the root directory but rather describes the path in relation to the current location.

![[Screenshot from 2024-02-10 19-29-22.png|500]]

---
# Basic Linux Commands: Reading Files

### touch Command
The touch command in Linux is used to create empty files and update the access and modification timestamps of existing files.

![[Screenshot from 2024-02-10 19-32-19.png|500]]

Then text was added to created file using *nano* command

![[Screenshot from 2024-02-10 19-37-47.png|500]]

### cat command
The cat command in Linux is used to concatenate and display the content of files. Its primary purpose is to display the content of one or more files to the terminal.

![[Screenshot from 2024-02-10 19-52-47.png|500]]

### head Command
The head command in Linux is used to display the beginning of a file. By default, it shows the first 10 lines of a file, but you can specify a different number of lines using options.


![[Screenshot from 2024-02-10 19-54-13.png|500]]

![[Screenshot from 2024-02-10 19-57-06.png|500]]

### tail Command
The tail command in Linux is used to display the last part of a file. By default, it shows the last 10 lines of a file, but  you can specify a different number of lines using options.

![[Screenshot from 2024-02-10 19-56-21.png]]

![[Screenshot from 2024-02-10 19-56-41.png|500]]

---
# Basic Linux Commands: Pager

### more Command
The more command in Linux is used to display the contents of a file one screen at a time. It allows you to scroll through the file, viewing it incrementally, and it is particularly useful for examining large files.

![[Screenshot from 2024-02-10 19-59-47.png|500]]

### less Command
The less command in Linux is another pager utility similar to more. It is used for viewing the contents of a file one screen at a time, but less has additional features compared to more.

![[Screenshot from 2024-02-10 20-00-27.png|500]]

---
# More Linux Commands

### ls Command
The ls command in Linux is used to list files and directories in a directory. It provides a way to view the contents of the filesystem

*Listing files with detailed information.*

![[Screenshot from 2024-02-10 20-01-52.png|500]]

*Listing all files, including hidden files.*

![[Screenshot from 2024-02-10 20-02-37.png|500]]

*Sorting files by modification time.*

![[Screenshot from 2024-02-10 20-02-57.png|500]]

*Listing files and directories in the current directory, sorted by modification time with the newest files at the bottom.*

![[Screenshot from 2024-02-10 20-03-22 2.png|500]]

---
# Command Line Help

### whatis Command
The whatis command in Linux is used to display a brief description of a command.

![[Screenshot from 2024-02-10 20-09-28.png|500]]

### man Command
The man command in Linux is used to display the manual pages for a particular command or topic. Manual pages are a form of documentation that provides detailed information about various commands, utilities, system calls, and other aspects of the Linux operating system.

![[Screenshot from 2024-02-10 20-07-54.png|500]]

### help Command
In Linux, the help command is used within the shell environment, specifically in the Bash shell, to display information about built-in shell commands.


![[Screenshot from 2024-02-10 20-10-10.png|500]]

---
# Linux Package Management

## Package Managers

### Working with dpkg

*Installing dpkg package manager*

![[Screenshot from 2024-02-10 21-10-46.png|500]]

*Listing the installed packages*

![[Screenshot from 2024-02-10 21-11-21.png|500]]

*To get the status of telnet package*

![[Screenshot from 2024-02-10 21-11-51.png|500]]

*Uninstalling the package*

![[Screenshot from 2024-02-10 21-17-22.png|500]]

### Working with apt

*Installing telnet package using apt*

![[Screenshot from 2024-02-10 21-20-49.png|500]]

*Searching the package database for packages with names or descriptions that contain the keyword telnet.*

![[Screenshot from 2024-02-10 21-21-25.png|500]]

*Listing all installed and available packages and then uses **grep** to filter lines that contain the keyword telnet.*

![[Screenshot from 2024-02-10 21-22-09.png|500]]

---
# Linux Users and Groups
## id, who, last Commands
- The id command in Linux is used to display information about the user and group of a user.
- The who command shows information about currently logged-in users, including their usernames, terminal, and login time.
- The last command displays a list of last logged-in users, including the time they logged in and out, as well as information about system reboots.


![[Screenshot from 2024-02-10 21-24-05.png|500]]

## sudo Command
The sudo command temporarily elevates privileges allowing users to complete sensitive
tasks without logging in as the root user.

![[Screenshot from 2024-02-10 21-20-49 1.png|500]]

## User and Group Management

*Creates a user named Joe.*

![[Screenshot from 2024-02-10 21-38-30.png|500]]

*This command allows to change password for a specific user.*

![[Screenshot from 2024-02-10 21-41-59.png|500]]

*Creating a group named **developer** .*

![[Screenshot from 2024-02-10 21-42-54.png|500]]

*Deleting the group.*

![[Screenshot from 2024-02-10 21-43-24.png|500]]

## Access Control Files in Linux

*/etc/passwd contains users information.*

![[Screenshot from 2024-02-10 21-50-05.png|500]]

*/etc/shadow contains hashed password.*

![[Screenshot from 2024-02-10 21-51-06.png|500]]

*/etc/group contains group information.*

![[Screenshot from 2024-02-10 21-51-32.png|500]]

---
# File Permissions in Linux

## chmod Command

*Chmod is use to change the permission of the file.*

![[Screenshot from 2024-02-10 21-55-20.png|500]]

*It also has the following form where each digit in octal represents a specific code. The first digit is for owner then groups and last is for others.*

![[Screenshot from 2024-02-10 21-56-18 1.png|500]]

## chown command

*The chown command in Linux is used to change the ownership of files and directories. It allows you to transfer ownership from one user to another user or from one group to another group.*

*Changes owner of the file to Joe.*

![[Screenshot from 2024-02-11 02-18-59.png|500]]

*Changes group for file named test1.txt to andriod.*

![[Screenshot from 2024-02-11 02-19-49.png|500]]