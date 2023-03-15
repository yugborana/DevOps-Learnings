# Resources
 - [Apoorv Goyal Linux Masterclass](https://www.youtube.com/watch?v=nRpmRDm-QrQ&list=PL2kSRH_DmWVZp_cu6MMPWkgYh7GZVFS6i)
 - [Michael Cade 90DaysOfDevOps](https://github.com/MichaelCade/90DaysOfDevOps/blob/main/2022.md) 
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
 - `echo`     --> Used to display values and variables in a shell
 - `pwd`      --> Print working directory or current directory
 - `cd folder_name/`       --> Changing the directory/folder
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
 - `#<Any Word>`    --> Add a comment
 - `mkdir`    --> To create a new directory
 - `mkdir -p` --> To create a sub-directory in a new directory
 - `rmdir`    --> To remove a directory
 - `cat<file name>`--> To see whats inside a file quickly
 - `history`  --> To see all the previous commands if terminal is cleared
 - `touch`    --> To create a new file
 - `gedit`    --> To open a file
 - `rm`       --> To remove a file
 - `rm -r`    --> Recursively removing the files and then a directory
 - `rm -rv`   --> Removes same as above command but also tells(verbose) about the things removed
 - `mv`       --> To move a file from one to another directory
 - `find ~ .name <File Name>`   --> Give the whole path of the file (Use `*` if extension or name not known)
 - `man <Command Name>`   --> Give information of flags related to the command written
 - `whatis <Command Name> `   --> Give info about the command written
