0x01. Shell, permissions

0-iam_betty has a script switch the user
1-who_am_i has the script to script that prints the effective username of the current user.
3-new_owne has the script that changes the owner of the file hello to the user betty.
4-empty has the script script that creates an empty file called hello.
5-execute has the script script that adds execute permission to the owner of the file hello.
6-multiple_permissions has the script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7-everybody has the script that adds execution permission to the owner, the group owner and the other users, to the file hello
8-James_Bond Write a script that sets the permission to the file hello as follows:

    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions

John Doe Write a script that sets the mode of the file hello to this:

-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

10-mirror_permissions Write a script that sets the mode of the file hello the same as olleh’s mode.
11-directories_permissions Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
12-directory_permissions Create a script that creates a directory called my_dir with permissions 751 in the working directory.
13-change_group Write a script that changes the group owner to school for the file hello


Advanced 


100-change_owner_and_group Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
101-symbolic_link_permissions Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.

    The file _hello is in the working directory
    The file _hello is a symbolic link

102-if_only Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.

    The file hello will be in the working directory

103-Star_Wars Write a script that will play the StarWars IV episode in the terminal.
