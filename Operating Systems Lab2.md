# Ubuntu & Compilers Installations


![[Pasted image 20240127225321.png|200]]

Session: 2022-2026

### Submitted By:
Rafiya Rehan

### Submitted To:
Mr. Nauman Shafi


Department of Computer Science

### University of Engineering and Technology
### Lahore Pakistan

---
# Ubuntu Installation using VMWare
## Steps to be Performed
**Step1** Install the latest version of VMWare Workstation Player for your OS(MS Windows in my case).


![[Screenshot (910).png|500]]



**Step2** Download Ubuntu for desktop. Installing the latest version would be the best option but also keep system requirements into consideration.

![[Screenshot (911).png|500]]


**Step3** Run VMWare on your PC. Select "Create a New Virtual Machine " option.

![[Screenshot (899).png|400]]

**Step4**  Give path for your ISO file.

![[Screenshot (900).png|400]]

**Step5** Give some information for Ubuntu installation.

![[Screenshot (901).png|400]]

**Step6**  Give name to your Virtual Machine.

![[Screenshot (902).png|400]]

**Step7**  Allocate disk storage for your Virtual Machine. I have reserved 20 GBs for VM.

![[Screenshot (903).png|400]]

**Step8** A summary of hardware resources will be shown. You can also configure hardware resources from here as well.

![[Screenshot (904).png|400]]

**Step9** Wait for a while till it sets up the installations.

![[Screenshot (906).png|400]]

**Step10**  Install Ubuntu and desktop screen will show up.

![[Screenshot from 2024-01-27 19-07-32.png|400]]

---
# Installing gcc & g++ Compliers

- For **C** language **gcc** complier is used.
- For **C++** language **g++** complier is used.


For installing these compliers, we will use terminal of our virtual machine. 

## Installing gcc Complier

**Command to be given** : sudo apt-get install gcc 

![[Screenshot from 2024-01-27 19-19-00.png]]

## Installing g++ Complier

**Command to be given** : sudo apt-get install g++

![[Screenshot from 2024-01-27 19-45-27.png]]

---
# Testing gcc & g++ Compilers
## gcc Compiler Testing

- To test the **gcc** compiler, first create a **C** file.
- This file can be created using GUI or CLI.
- For creation of C file, I have used CLI.

![[Screenshot from 2024-01-27 19-38-04.png]]

### Output

- The first command tells the compiler (gcc) to take the source code in "test.c", compile it, and produce an executable file named "obj". The -o option is used to specify the name of the output file.
- After running this command, if there are no compilation errors, you will get an executable file named "obj" in the same directory.
- To run the compiled program, "./obj" is used.

![[Screenshot from 2024-01-27 19-49-12.png]]


## g++ Compiler Testing

- To test the **g++** compiler, first create a **Cpp** file.
- This file can be created using GUI or CLI.
- For creation of Cpp file, I have used GUI.

### Output

- The first command tells the compiler (g++) to take the source code in "test.cpp", compile it, and produce an executable file named "obj". The -o option is used to specify the name of the output file.
- After running this command, if there are no compilation errors, you will get an executable file named "obj" in the same directory.
- To run the compiled program, "./obj" is used.


![[Screenshot from 2024-01-27 19-48-20.png]]

---
### GitHub Repository Link

[GitHub Link](https://github.com/Rafiya-Rehan21/OS-Lab)

