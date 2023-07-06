# Shell Permissions
this project is about Linux file permissions and how to represent each of the three sets of permissions, additionally how to change the owner of a file.
## Tasks:
0. [My name is Betty](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/0-iam_betty "0") : switches the current user to betty.
1. [Who am I](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/1-who_am_i "1") : prints the effective username of the current user.
2. [Groups](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/2-groups "2") : prints all the groups the current user is part of.
3. [New owner](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/3-new_owner "3") : changes the owner of the file hello to the user betty.
4. [Empty!](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/4-empty "4") : creates an empty file called hello.
5. [Execute](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/5-execute "5") : adds execute permission to the owner of the file hello.
6. [Multiple permissions](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/6-multiple_permissions "6") :  adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7. [Everybody!](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/7-everybody "7") : adds execution permission to the owner, the group owner and the other users, to the file hello.
8. [James Bond](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/8-James_Bond "8") : James Bond.
9. [James Bond](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/9-John_Doe "9") : The Week 753 by John Doe.
10. [Look in the mirror](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/10-mirror_permissions "10") : Write a script that sets the mode of the file `hello` the same as `olleh`’s mode.
11. [Directories](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/11-directories_permissions "11") : adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. `Read the man page the line that start with "The letters rwxXst".`
12. [More directories](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/12-directory_permissions "12") : creates a directory called `my_dird` with permissions 751 in the working directory.
13. [Change group](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/13-change_group "13") : Write a script that changes the group owner to school for the file hello.
14. [Owner and group](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/100-change_owner_and_group "100"): changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
15. [Symbolic links](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/101-symbolic_link_permissions "101") : changes the owner and the group owner of `_hello` to vincent and staff respectively.
16. [If only](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/102-if_only "102") : changes the owner of the file hello to betty only if it is owned by the user guillaume.
17. [Star Wars](https://github.com/sbe4658/alx-system_engineering-devops/blob/master/0x01-shell_permissions/103-Star_Wars "103") : will play the StarWars IV episode in the terminal.
> * it might take a while to run.
> * you'll need to install telnet comand, use:
~~~~
/* you can use sudo if necessary */
apt-get install telnet
apt-get upgrade telnet
~~~~
___
Kimba is watching :lion:. For the flags like `mkdir --mode=751 dir` run the man command to get more info about it `man mkdir`.
