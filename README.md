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

