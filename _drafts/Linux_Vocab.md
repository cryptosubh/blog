---
layout: post
title: Linux Vocab
---
Most of the definitions come from *The Linux Command Line* by William E. Shotts Jr.

####Chapter 1: What is the Shell?  
* **shell**  
A program that takes keyboard commands and passes them to the operating system to carry out.  Almost all Linux distributions supply a shell program from the GNU Project called **bash**.
* **bash**  
Stands for "Bourne Again Shell".  An enhanced replacement for sh, the original Unix shell program written by Steve Bourne.
* **terminal emulator**  
Gives you access to interact with the shell.  Examples: konsole, gnome-terminal
* **superuser**  
A special user account used for system administration.  On Unix-like systems, for example, the user with a user identifier (UID) of zero is the superuser.   Root is the conventional name of the user who has all rights or permissions (to all files and programs) in all modes.


####Chapter 2: Navigation  
* **heirarchical directory structure**  
Linux organizes its files in a tree-like pattern of directories (ie, folders) which may contain files and other directories
* **root directory**  
The first directory in the file system
* **pathname**  
The route we take along the branches of the tree to get to the directory we want  
  - *absolute pathname*:
  begin with the root, represented by a leading slash /
  - *relative pathname*:
  begin with the working directory, represented by ./ or just implied!
  
####Chapter 3: Exploring the System
* **pagers**  
A class of programs that allow for easy viewing of long text documents in a page-by-page manner. Example: *less*
* **Linux Filesystem Heirarchy Standard**  
Defines the directory structure and directory contents in Unix-like operating systems
* **symbolic link** or **soft link** or **symlink**  
The nickname for any file that contains a reference to another file or directory in the form of an absolute or relative path and that affects pathname resolution

####Chapter 4: Manipulating Files & Directories
* **wildcard**  
A symbol that can stand for one or more characters
* **globbing**  
The process of expanding a non-specific file name containing a wildcard character into a set of specific file names that exist in storage on a computer, server, or network
* **hard link**  
A directory entry that associates a name with a file on a file system. Cannot reference a directory, only a file.
* **inode**  
A data structure in a Unix-style file system which describes a filesystem object such as a file or a directory. Each inode stores the attributes and disk block location(s) of the object's data. Filesystem object attributes may include metadata (times of last change, access, modification), as well as owner and permission data.  Everything except its name and its actual data!


####Chapter 5: Working with Commands
* **alias**  
A command we can define ourself, built from other commands
* **shell builtins**  
A command built into the shell itself
* **shell functions**  
Mini shell scripts incorporated into the environment
* **environment**  

####Chapter 6: Redirection
* **standard output, input and error**  
Special files where programs such as *ls* send their results and receive their arguments.  By default, standard output & error are linked to the screen and not saved in a file, and standard input is attached to the keeyboard.
* **file descriptor**  

####Chapter 7: Seeing the World as the Shell Sees It
* **expansion**  
s
  * *pathname expansion*  
  * *arithmetic expansion*  
  * *brace expansion*
  * *parameter expansion*  
* **word splitting**
* **quoting**
