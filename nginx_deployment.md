# How to deploy nginx

A step  by step guide on deploying nginx, 

### Delete Existing Virtual Machine

In bash terminal, run 'vagrant destroy' (ensure you are in correct working directory)

### Add New Virtual Machine

In bash terminal, run 'vagrant up' to create a new virtual machine (check virtual box to make sure a new virtual machine with appropriate name is added)

### Enter Virtual Machine

In bash terminal, enter 'vagrant ssh'. This will allow you to enter the virtual machine that was just created.
NOTE: working directory in bash terminal will change to vagrant@ubuntu/xenial64 or any other box you have configured for in Vagrantfile.

### Update and Upgrade Virtual Machine

In the new VM terminal, run 'sudo apt-get update'
In the new VM terminal, run 'sudo apt-get upgrade -y'

### Install nginx

In the new VM terminal, run 'sudo apt-get install nginx -y' (to install nginx)

### Start nginx

In the new VM terminal, run 'sudo systemctl start nginx' (to start nginx)
In the new VM terminal, run 'sudo systemctl status nginx' (to check nginx has in fact started)

### Access the nginx web server in web browser

nginx web server can be accessed by entering following IP address in the web browser:
192.168.0.10

### Exit web server

run 'exit'