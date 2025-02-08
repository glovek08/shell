0-iam_betty: changes the current user to "betty".
1-who_am_i: display username of the current user.
2-groups: display current user groups.
3-new_owner: changes the owner of the file hello to betty.
4-empty: creates an empty hello file.
5-execute: gives execute permissoins to the file owner of 'hello'.
6-multiple_permissions: script that adds execute permission to the owner and group owner and read for users for the file 'hello'.
7-everybody: gives all permissions to everybody.
8-James_Bond: sets all permissions only for other users for the 'hello' file.
9-John_Doe: sets the mode of the file 'hello' to -rwxr-x-wx.
10-mirror_permissions: copies the mode of hello to olleh.
11-directories_permissions: adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files remain unchanged.
12-directory_permissions: script that creates a directory called /my_dir with permissions 751 in the working directory.
13-change_group: script that changes the group owner to school for the file 'hello'.
14-change_owner_and_group: script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
15-symbolic_link_permissions: script that changes the owner and the group owner of _hello to vincent and staff respectively.
16-if_only: changes the owner of the file hello to vincent only if it is owned by the user 'guillaume'.
