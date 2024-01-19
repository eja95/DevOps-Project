 # File Manipulation Using Linux

 ## 1. `sudo` command

 Sudo stands for "superuser do" is a popular basic linux command that allows you to perform tasks that require admistrative or root permissions.

Here's the general syntax:

`sudo (command e.g apt upgrade)`

so it becomes

`sudo apt upgrade`

After running that command there, the sudoers file wasnt found

![Alt text](<Images/Screenshot 2024-01-11 2253267.png>)

So I tried switching to the root using 

`su -`

then ran the command

`apt upgrade`

![Alt text](<Images/Screenshot 2024-01-13 075140.png>)

## 2. `pwd` command

`pwd` short for present working directory, displays the name of the current directory you are in. Simply entering pwd will return the full current path starting with a forward slash (e.g.: /home/ubuntu). The pwd command uses the following syntax:

`pwd [option]`

![Alt text](<Images/Screenshot 2024-01-13 091717.png>)

## 3. `cd` command

