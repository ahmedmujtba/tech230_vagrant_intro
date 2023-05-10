# An Intro to Vagrant

In this repo, you will learn how to setup a Virtual Machine using Vagrant & Virtual Box and how to deploy an nginx web server.


## Linux/GitBash Command Cheat Sheet

This is a Linux / Git Bash Command Cheat Sheet containing all the possible commands you may need whilst running a virtual machine.


### To change directory
cd directory-name

### To go to root directory
cd /

### To go up one folder
cd ..

### To print working directory
pwd

### To run a command in super user mode (admin mode)
sudo examplecommandname

### To write to a file within terminal
sudo nano example.txt

### To create a file if doesn't exit already
sudo nano example.jpeg

### To create a new file
touch example.txt

### To delete an existing file
rm example.txt

### To  view contents of a file
cat example.txt

### To copy and rename a file
cp example.txt new-example.txt

### To copy a file to a different directory
cp example.txt directoryname

### To create a new directory
mkdir directoryname

### To create a hidden directory
mkdir .hidden-directory-name

### To remove a directory
rm -rf directoryname

### To rename a file
mv old-filename new-filename

### To view a list of files/directories in current working directory
ls

### To view all files (including hidden files)
ls -a

### To view files of a specific type
ls *.txt (shows all text files)

### To view a list of files/directories in long list format
ls -l (shows permissions, number of links, owner name, owner group, file size, time last modified)

### To modify user access
chmod u+x filename (grants permission for current user to execute filename)
chmod g+w filename (grants permission for everyone within current group to modify filename)

u = user
g = group
o = other

d= directory (if element is a directory)
l = link (if element is a file links)
r= read (read permissions)
w = write (write permissions)
x = execute (for scripts and programs)