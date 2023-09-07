# Shell, permissions


The files listed down bellow are scripts done during **Software Engineering** course with **ALX Africa**. 

They aim to learn how to use the `chmod`, `sudo`, `su`, `chown`, `chgrp` , `id` , `groups` , `whoami` , `adduser` and `addgroup` commands to represent and change Linux file permissions and change users in the Shell.

## Technologies
* Scripts written in Bash
* Tested on Ubuntu 20.04 LTS

## Files

| Filename | Description |
| -------- | ----------- |
| [0-iam_betty](./0-iam_betty) | Switche the current user to the user `betty`. |
| [1-who_am_i](./1-who_am_i) |  Print the effective username of the current user. |
| [2-groups](./2-groups) | Print all the groups the current user is part of. |
| [3-new_owner](./3-new_owner) | Change the owner of the file `hello` to the user `betty`. |
| [4-empty](./4-empty) | Create an empty file called `hello`. |
| [5-execute](./5-execute) | Add execute permission to the owner of the file `hello`. |
| [6-multiple_permissions](./6-multiple_permissions) | Add execute permission to the owner and the group owner, and read permission to other users, to the file `hello`. |
| [7-everybody](./7-everybody) | Add execution permission to the owner, the group owner and the other users, to the file `hello`. |
| [8-James_Bond](./8-James_Bond) | Set the permission to the file `hello` ; Owner: no permission at all, Group: no permission at all and Other users: all the permissions. |
| [9-John_Doe](./9-John_Doe) | Set the `-rwxr-x-wx` permission to the file `hello` |
| [10-mirror_permissions](./10-mirror_permissions) | Set the mode of the file `hello` the same as `olleh`'s mode |
| [11-directories_permissions](./11-directories_permissions) | Add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. |
| [12-directory_permissions](./12-directory_permissions) | Create a directory called `my_dir` with permissions `751` in the working directory. |
| [13-change_group](./13-change_group) | Change the group owner to `school` for the file `hello`. |
| [100-change_owner_and_group](./100-change_owner_and_group) | Change the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory. |
| [101-symbolic_link_permissions](./101-symbolic_link_permissions) | Change the owner and the group owner of `_hello` to `vincent` and `staff` respectively. |
| [102-if_only](./102-if_only) | Change the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`. |
| [103-Star_Wars](./103-Star_Wars) | Play the StarWars IV episode in the terminal. |
