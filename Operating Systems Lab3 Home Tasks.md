


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
# Task 1
## Using Ubuntu Utilities to perform Tasks
### 1. Create a file named “19f-XXXX.txt”. File must contain at least 10 lines.
- A new file is created using *touch* command.
- Content is added to newly created file using *nano* command.
- To view the contents of file *cat* command is used.

![[Screenshot from 2024-02-21 00-25-58.png|500]]

![[Screenshot from 2024-02-21 00-28-08.png|500]]

### 2. Create another file named “your name.txt”. File must contain at least 10 lines.
Same above procedure can be repeated.
- A new file is created using *touch* command.
- Content is added to newly created file using *nano* command.
- To view the contents of file *cat* command is used.


![[Screenshot from 2024-02-21 00-30-51.png|500]]


### 3. Merge the data of both files.
To merge the data of both files, *cat* command is used.

![[Screenshot from 2024-02-21 00-31-47.png|500]]

### 4. Redirect the output to a new file.
Redirecting operator (>) is used to direct the output of command *ls* (in this case) to a newly created fie.

![[Screenshot from 2024-02-21 00-39-20.png|500]]

![[Screenshot from 2024-02-21 00-39-59.png|500]]

### 5. Display the first two lines of first file.
To display first two lines of first file, *head* command with *option: 2* is used.

![[Screenshot from 2024-02-21 00-40-56.png|500]]

### 6. Display the last two lines of second file.
To display last two lines of second file, *tail* command with *option: 2* is used.

![[Screenshot from 2024-02-21 00-41-22.png|500]]

### 7. Finds the string (your roll#) from the first file.
To find string in a file *grep* command is used.

![[Screenshot from 2024-02-21 00-44-37.png|500]]

### 8. Grant the execute permission of the second file to the group.
To change the permission for a group to only execute the file, use **chmod  [octal code] filename.txt** or another syntax **chmod  g+x  filename.txt** can be used.

![[Screenshot from 2024-02-21 00-48-47 1.png|500]]

### 9. Remove the write permission for the owner.
To remove the writing access to a file for owner , use **chmod  [octal code] filename.txt** or another syntax **chmod  u-w  filename.txt** can be used.

![[Screenshot from 2024-02-21 00-50-23.png|500]]

### 10.Now Mr. Tom suddenly lost the track of his current location. Help him find his location.
*pwd command is used to show the path.

![[Screenshot from 2024-02-21 00-50-53.png|500]]

### 11.He wants the list of all files present on Desktop directory.
To list all files present on desktop *ls* command with *option* can be used.

![[Screenshot from 2024-02-21 00-52-17.png|500]]

### 12.Now he wanted to create a folder of his personal files and pictures named as your roll#.
*mkdir* command can be used to create new directory.

![[Screenshot from 2024-02-21 00-52-49.png|500]]

### 13.Display the current time.
*Date +%r* will show the current time.

![[Screenshot from 2024-02-21 00-53-44.png|500]]

### 14.He is done with the task and he is happy with your work. He want to display a thankyou message.
To display a message, *echo* command is used.

![[Screenshot from 2024-02-21 00-54-38.png|500]]

---
# Task 2
## Basic Commands and Granting Permissions

### 1. Create a file named “19f-XXXX_OS-lab_rules.txt” using linux commands. The file must contain all lab rules covered in first lab.
Steps for file Creation:
- A new file is created using *touch* command.
- Content is added to newly created file using *nano* command.
- To view the contents of file *cat* command is used.

![[Screenshot from 2024-02-21 00-56-55.png|500]]

![[Screenshot from 2024-02-21 00-59-19.png|500]]

### 2. You want to set the rights of created file to this (- rwx r-x r--). For these rights, you are required to convert the given rights in numeric format using binary number system procedure covered in lecture. Show complete working.

The permissions -rwxr-xr-- can be represented in numeric format as 754. Each permission has a corresponding numeric value:
- r (read) = 4
- w (write) = 2
- x (execute) = 1
So, rwx is 4 + 2 + 1 = 7, r-x is 4 + 0 + 1 = 5, and r-- is 4 + 0 + 0 = 4.

### 3. Now use the derived number to change the permission of a file using chmod command.
Using the above derived code (754) to change the permissions.

![[Screenshot from 2024-02-21 01-02-07.png|500]]

### 4. Append the output of ls command to created file.
To append the output of the ls command to the file,  >> operator  can be used.

![[Screenshot from 2024-02-21 01-04-16.png|500]]

---
