# Command Line Cheat Sheet

## The Basics

Print a string to the command line:
- `echo "Hello World"`

Print a strong to the command line with a line break:
- `echo -e "Hello\nWorld"`

Display the current directory:
- `pwd`

Change the directory:
- `cd [path]`
- `cd ~`
- `cd ..`

Listing contents:
- `ls`
- `ls -a` (All entries including hidden files)
- `ls -r` (Reverse order while sorting)
- `ls -t` (Sort by modification time, newest first)

Executing multiple commnands:
- `command1, command2, ... commandn`
- `echo 'Hello '; echo 'World' `

## Installing and Updating Software

Refresh the list of available packages on the system:
- `apt update`

Upgrade existing packages and installs dependencies:
- `apt upgrade`

Upgrade existing packages, install dependencies, removes redundant packages
- `apt full-upgrade`

Install Software
- `apt install [package]`

Remove Software
- `apt remove [package]`

Remove packages that are no longer needed
- `apt autoremove`

## File Management
Create a new file or update the timestamp on an existing file
- `touch file.txt`
- `touch file1.txt file2.txt`

Create a new directory
- `mkdir directoryname`

Delete a file
- `rm file.txt`
- `rm file1.txt file2.txt`

Delete a directory
- `rmdir directoryname`
- `rmdir dir1 dir2`


## User Management