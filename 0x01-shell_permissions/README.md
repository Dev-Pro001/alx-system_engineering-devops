# About 0x01. Shell, Permissions 

The Unix-like operating systems, such as Linux differ from other computing systems in that they are not only multitasking but also multi-user.

What exactly does this mean? It means that more than one user can be operating the computer at the same time. While a desktop or laptop computer only has one keyboard and monitor, it can still be used by more than one user. [Learn more...](http://linuxcommand.org/lc3_lts0090.php)

The project presents the basic bash commands related to file permissions 

# Scripts With The Bash Commands 

[0-iam_betty:](./0-iam_betty)
A script that switches the current user to the user betty.

[1-who_am_i:](./1-who_am_i)
A script that prints the effective username of the current user.

[2-groups:](./2-groups)
A script that prints all the groups the current user is part of.

[3-new_owner:](./3-new_owner)
A script that changes the owner of the file hello to the user betty.

[4-empty:](./4-empty)
A script that creates an empty file called hello.

[5-execute:](./5-execute)
A script that adds execute permission to the owner of the file hello.

[6-multiple_permissions:](./6-multiple_permissions)
A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

[7-everybody:](./7-everybody)
A script that adds execution permission to the owner, the group owner and the other users, to the file hello

[8-James_Bond:](./8-James_Bond)
A script that sets the permission to the file hello as follows:

Owner: no permission at all\n
Group: no permission at all\n
Other users: all the permissions\n

[9-John_Doe:](./9-John_Doe)
A script that sets the mode of the file hello

[10-mirror_permissions:](./10-mirror_permissions)
A  script that sets the mode of the file hello the same as olleh’s mode.

[11-directories_permissions:](./11-directories_permissions)
Ascript that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Without changing the regular files.

[12-directory_permissions:](./12-directory_permissions)
A script that creates a directory called my_dir with permissions 751 in the working directory.

[13-change_group:](./13-change_group)
A script that changes the group owner to school for the file hello
