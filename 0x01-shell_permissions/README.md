0x01. Shell, permissions project
0-iam_betty: switches current user to user betty
1-who_am_i: prints effective username of current user
2-groups: prints all groups current user is part of
3-new_owner: changes owner of file hello to user betty
4-empty: creates an empty file called hello
5-execute: adds execute permission to owner of file hello
6-multiple_permissions: adds execute permission to owner and group owner, and read permission to other users, to file hello
7-everybody: adds execution permission to owner, group owner, and other users, to file hello
8-James_Bond: set owner-no permision at all, set group owner - no permission at all, and set other users - all permissions, to file hello
9-John_Doe: sets mode of file hello to this: -rwxr-x-wx
10-mirror_permissions: sets mode of file hello same as file olleh
11-directories_permissions: adds execute permission to all subdirectories of current directory for owner, group owner, and all other users. regular files not be changed
12-directory_permissions: creates directory called my_dir with permissions 751 in the working directory
13-change_group: changes group owner to school for file hello, file hello is in the working directory
100-change_owner_and_group: changes owner to vincent and group owner to staff for all files and directories in working directory
101-symbolic_link_permissions: changes owner and group owner of _hello to vincent and staff respectively. _hello file is in working directory and it is symbolic link
102-if_only: changes owner of file hello to betty only if it i owned by user guillaume. file hello is in working directory
103-Star_Wars: play StarWars IV episode in the terminal
