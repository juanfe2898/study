# study
# Linux Basics
A partition is a logical part of the disk.  
A filesystem is a method of storing/finding files on a hard disk.  
By dividing the hard disk into partitions, data can be grouped and separated as needed. When a failure or mistake occurs, only the data in the affected partition will be damaged, while the data on the other partitions will likely survive.  
The boot process has multiple steps, starting with BIOS, which triggers the boot loader to start up the Linux kernel. From there, the initramfs filesystem is invoked, which triggers the init program to complete the startup process.  
Determining the appropriate distribution to deploy requires that you match your specific system needs to the capabilities of the different distributions.  

## The Boot Process
The Linux boot process is the procedure for initializing the system. It consists of everything that happens from when the computer power is first switched on until the user interface is fully operational.
![image](https://github.com/user-attachments/assets/3d4b94d9-b535-4cb8-bdc4-3f092e323b9e)

## The Filesystem Hierarchy Standard
![image](https://github.com/user-attachments/assets/cf69d6eb-2faf-4796-ad08-ca684dce3dc0)

## Choosing a Linux Distribution
![image](https://github.com/user-attachments/assets/d6c3e10a-b256-431f-af69-051a932c8a59)

## Some Basic Utilities
There are some basic command line utilities that are used constantly, and it would be impossible to proceed further without using some of them in simple form before we discuss them in more detail. A short list has to include:  
**cat:** used to type out a file (or combine files).  
**head:** used to show the first few lines of a file.  
**tail:** used to show the last few lines of a file.  
**man:** used to view documentation.  

## Navigating Through Directory History
For remembering more than just the last directory visited, use pushd to change the directory instead of cd; this pushes your starting directory onto a list. Using popd will then send you back to those directories, walking in reverse order (the most recent directory will be the first one retrieved with popd). The list of directories is displayed with the dirs command.

## Viewing Files
cat -n show the lines
mkdir is used to create a directory:
mkdir sampdir 
Removing a directory is done with rmdir
rm -rf.
![image](https://github.com/user-attachments/assets/77bf71ae-af17-42b0-a6c0-65c15451981e)
![image](https://github.com/user-attachments/assets/a677d290-6ec1-4820-a218-93ad015d2541)
![image](https://github.com/user-attachments/assets/b7d4d8b2-4abe-4ddc-b887-5ce811f0ae79)

- Virtual terminals (VT) in Linux are consoles, or command line terminals that use the connected monitor and keyboard.
- Different Linux distributions start and stop the graphical desktop in different ways.
- A terminal emulator program on the graphical desktop works by emulating a terminal within a window on the desktop.
- The Linux system allows you to either log in via text terminal or remotely via the console.
- When typing your password, nothing is printed to the terminal, not even a generic symbol to indicate that you typed.
- The preferred method to shut down or reboot the system is to use the shutdown command.
- There are two types of pathnames: absolute and relative.
- An absolute pathname begins with the root directory and follows the tree, branch by branch, until it reaches the desired directory or file.
- A relative pathname starts from the present working directory.
- Using hard and soft (symbolic) links is extremely useful in Linux.
- cd remembers where you were last, and lets you get back there with cd -.
- locate performs a database search to find all file names that match a given pattern.
- find locates files recursively from a given directory or set of directories.
- find is able to run commands on the files that it lists, when used with the -exec option.
- touch is used to set the access, change, and edit times of files, as well as to create empty files.
- The Advanced Packaging Tool (apt) package management system is used to manage installed software on Debian-based systems.
- You can use the dnf command-line package management utility for the RPM-based Red Hat Family Linux distributions.
- The zypper package management system is based on RPM and used for openSUSE.

# Finding Linux Documentation
The main sources of Linux documentation are the man pages, GNU info, the help options and command, and a rich variety of online documentation sources. 
The man utility searches, formats, and displays man pages.
The man pages provide in-depth documentation about programs and other topics about the system, including configuration files, system calls, library routines, and the kernel.
The GNU Info System was created by the GNU project as its standard documentation. It is robust and is accessible via command line, web, and graphical tools using info.
Short descriptions for commands are usually displayed with the -h or --help argument.
You can type help at the command line to display a synopsis of built-in commands.
There are many other help resources both on your system and on the Internet.
