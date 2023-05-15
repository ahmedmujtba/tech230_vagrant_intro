# An Intro to Vagrant

In this repo, you will learn how to setup a Virtual Machine using Vagrant & Virtual Box and how to deploy an nginx web server.

## Linux/Bash Command Cheat Sheet

This is a Linux / Git Bash Command Cheat Sheet containing all the possible commands you may need whilst running a virtual machine.

`cd <directoryname>` - To change directory

`cd /` - To go to root directory

`cd ..` - To go up one folder

`pwd` - To print working directory

`sudo <commandname>` - To run a command in super user mode (admin mode)

`sudo nano example.txt` - To write to a file within terminal

`sudo nano example.jpeg` - To create a file if doesn't exit already

`touch example.txt` - To create a new file

`rm example.txt` - To delete an existing file

`cat example.txt` - To view contents of a file

`cp example.txt new-example.txt` - To copy and rename a file

`cp example.txt directoryname` - To copy a file to a different directory

`mkdir directoryname` - To create a directory

`mkdir .hidden-directory-name` - To create a hidden directory

`rm -rf directoryname` - To remove a directory

`mv old-filename new-filename` - To rename a file

`ls` - To view a list of files/directories in current working directory

`ls -a` - To view all files (including hidden files)

`ls \*.txt` - To view files of a specific type (text file in this example)

`ls -l` (shows permissions, number of links, owner name, owner group, file size, time last modified) - To view a list of files/directories in long list format

`chmod u+x filename` - (grants permission for current user to execute filename)
`chmod g+w filename` - (grants permission for everyone within current group to modify filename)

`u` = user
`g` = group
`o` = other

`d` = directory (if element is a directory)
`l` = link (if element is a file links)
`r` = read (read permissions)
`w` = write (write permissions)
`x` = execute (for scripts and programs)

`head -2 example.txt` - This command shows two lines from the top of a specified file. `head` represents the top

`tail -2 example.txt` - This command shows two lines from the bottom of a specific file. `tail` represents the bottom

`sort example.txt` - To sort file contents

`cat example.txt` - To view contents of a file

`al example.txt`

`wc example.txt`

`wc -l example.txt`

`ls | head -1` - To combine two commands, `|` is referred to as pipe. This example returns one file from the top

`cat example.txt | grep hello` - To run all lines with the word `hello`

`top` - Shows what programmes are running

`q` - To quit terminal

`ps` - Shows programmes running

`ps aux` - Detailed overview of what's running. Doesn't lock you in terminal unlike `ps`

`kill <programme>` - Terminates a specific programme e.g. `Kill 2165` will terminate programme 2165

`kill -9 <programme>` - Terminates a programme forcefully
