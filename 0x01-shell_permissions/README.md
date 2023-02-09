## Shell Permissions

<h3>0-iam_betty</h3>
This script switches the current user to the user betty

<h3>1-who_am_i</h3>
prints the effective username of the current user.
<h3>2-groups</h3>
prints all the groups the current user is part of.
<h3>3-new_owner</h3>
changes the owner of the file hello to the user betty
<h3>4-empty</h3>
creates an empty file called hello.
<h3>5-execute</h3>
adds execute permission to the owner of the file hello
<h3>6-multiple_permissions</h3>
adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
<h3>7-everybody</h3>
 adds execution permission to the owner, the group owner and the other users, to the file hello
<h3>8-James_Bond</h3>
sets the permission to the file hello as follows:
    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions
<h3>9-John_Doe</h3>
sets the mode of the file hello to -rwxr-x-wx
<h3>10-mirror_permissions</h3>
sets the mode of the file hello the same as olleh’s mode. olleh's mode: -rw-rw-r--
<h3>11-directories_permissions</h3>
adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
<h3></h3>
<h3>12-directory_permissions</h3>
creates a directory called my_dir with permissions 751 in the working directory.
<h3>13-change_group</h3>
changes the group owner to school for the file hello
<h3>100-change_owner_and_group</h3>
changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
<h3>101-symbolic_link_permissions</h3>
changes the owner and the group owner of _hello to vincent and staff respectively.

The file _hello is in the working directory
The file _hello is a symbolic link
<h3>102-if_only</h3>
changes the owner of the file hello to betty only if it is owned by the user guillaume
<h3>103-Star_Wars</h3>
plays the StarWars IV episode in the terminal
