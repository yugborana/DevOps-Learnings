# Resource- 
 - [Apoorv Goyal Linux Masterclass](https://www.youtube.com/watch?v=nRpmRDm-QrQ&list=PL2kSRH_DmWVZp_cu6MMPWkgYh7GZVFS6i)
# Understanding Linux Basics

- What is an OS?
  - Operating System is a software to manage and operate a computing device.
  - Needs of OS-
    - Kernel
    - File System
    - User Interface (GUI or CLI)
    - Should be able to manipulate data based on command.

- Initialization of Operating System
  - A computer starts.
  
  - Checks and Executes the softwares in BIOS (Basic Input Output System) also known as Firmware which is stored in ROM.
  
  - Loads BootLoader (A program which initialize the OS). 
  
- What is File System?
  - A data structure that the OS use to store and retrieve data from memory.
 
 - What is Kernel?  
   - It is a core component of an OS and serves as the main interface between the computer's hardware & processes running on it.
   - It is a bridge between Software and Hardware.

- What is Terminal?
  - A tool where commands are written.
  - `ctrl+alt+t` --> Terminal Shortcut

- What is Shell?
  - A command line interpreter which executes command line by line.
  - Most of the shells use Bash Programming Language. 

# Basic Linux Commands
 
 - `pwd`      --> Print working directory or current directory
 - `cd`       --> Changing the directory/folder
 - `cd -`     --> To go to previous directory
 - `cd ..`    --> To go to parent directory
 - Relative Path:
   - `.`      --> The current directory
   - `..`     --> The previous directory
 - `ls`       --> List all files & folder in a directory
 - `ls /`     --> List all files & folder in root directory
 - `ls -a`    --> List all the hidden files(hidden in GUI) with other files 
 - `ls -l`    --> Showing the file permissions as well
   - `rwxd`   --> Read, write, execute, delete 
 - `ls -al`   --> Combining above two commands (Hidden Files + Details)
 - `clear`    --> To clean the terminal
 - `#<-->`    --> Add a comment
 - `mkdir`    --> To create a new directory
 - `cat<file>`--> To see whats inside a file quickly
 - `history`  --> To see all the previous commands if terminal is cleared
 - `touch`    --> To create a new file
 - `rm`       --> To remove a file
