The 0-iam_betty script switches the current user to the user betty.
The 1-who_am_i script  prints the effective username of the current user.
The 2-groups script prints all the groups the current user is part of.
The 3-new_owner script  changes the owner of the file hello to the user betty.
The 4-empty script  creates an empty file called hello.
The 5-execute script adds execute permission to the owner of the file hello.
The 6-multiple_permissions adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
The 7-everybody script adds execution permission to the owner, the group owner and the other users, to the file hello.
The 8-James_Bond script sets the permission to the file hello as follows:
Owner: no permission at all

Group: no permission at all

Other users: all the permissions
The 9-John_Doe script  sets the mode of the file hello to this:-rwxr-x-wx 
The 10-mirror_permissions sets the mode of the file hello the same as olleh’s mode.
The 11-directories_permissions adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
The 12-directory_permissions creates a directory called my_dir with permissions 751 in the working directory.
The 13-change_group script changes the group owner to school for the file hello.
The 100-change_owner_and_group script  changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
The 101-symbolic_link_permissions changes the owner and the group owner of _hello to vincent and staff respectively.
The 102-if_only changes the owner of the file hello to betty only if it is owned by the user guillaume.
The 103-Star_Wars script plays the StarWars IV episode in the terminal.
