---
layout: post
title: Linux Commands
---

Normally I write notes like these out longhand, but since I'll only ever be typing commands, it seemed like a defensible (and quicker) choice to type them out instead.  

### Part I: Learning the Shell

#### Chapter 1: What is the Shell?
* **date**
* **cal**
* **df** disk filesystem summary
* **free** view free memory

#### Chapter 2: Navigation
* **pwd** print working directory
* **cd** change directory

#### Chapter 3: Exploring the System
* **ls** list directory contents
* **file** determine file type
* **less** view file contents

#### Chapter 4: Manipulating Files & Directories
* **cp** copy
* **mv** move
* **mkdir** make directory
* **rm** remove
* **ln** create hard and symbolic links

#### Chapter 5: Working with Commands
* **type** indicate how a command is interpreted - builtin, alias, or saved executable
* **which** display the location of an executable program.  doesn't work on builtins or aliases.
* **man** display a command's manual page
* **info** display a command's info entry
* **whatis** display a very brief description of a command
* **alias** create an alias for a command

#### Chapter 6: Redirection
* **cat** read one or more files, concatenate them, and copy them to standard output
* **sort** sort lines of text
* **uniq** report or omit repreated lines. takes a sorted list of data as input - often used in conjunction with *sort*
* **wc** print newline, word, and byte counts for each file
* **grep** print lines matching a pattern
* **head** output the first part of a file
* **tail** output the last part of a file
* **tee** read from standard input and write to *both* standard output and files

#### Chapter 7: Seeing the World as the Shell Sees It
* **echo** display a line of text

#### Chapter 8: Advanced Keyboard Tricks
* **clear** clear the screen
* **history** display the contents of the history list
* **script**  

#### Chapter 9: Permissions
* **id** display user identity
* **chmod** change a files' mode (permissions)
* **umask** set the default file permissions
* **su** run a shell as another user
* **sudo** execute a command as another user
* **chown** change a file's owner
* **chgrp** change a file's group ownership
* **passwd** change a user's password

#### Chapter 10: Processes
* **ps** report a snapshot of current processes
* **top** display tasks
* **jobs** list active jobs
* **bg** place a job in the background
* **fg** place a job in the foreground
* **kill** send a signal to a process
* **killall** kill processes by name
* **shutdown** shut down or reboot the system

### Part II: Configuration & The Environment

#### Chapter 11: The Environment
* **printenv** print all or part of the environment
* **set** set shell options
* **export** export environment to subsequently executed programs
* **nano**

#### Chapter 12: A Gentle Introduction to vi


#### Chapter 13: Customizing the Prompt

### Part III: Common Tasks & Essential Tools
#### Chapter 14: Package Management

#### Chapter 15: Storage Media
#### Chapter 16: Networking
#### Chapter 17: Searching for Files
#### Chapter 18: Archiving & Backup
#### Chapter 19: Regular Expressions
#### Chapter 20: Text Processing
#### Chapter 21: Formatting Output
#### Chapter 22: Printing
#### Chapter 23: Compiling Programs
