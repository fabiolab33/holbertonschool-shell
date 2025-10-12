In this directory we will find various files that contain commands.
Starting with:

0-iam_betty
command: su
This command is for switches the current user to betty.

1-who_am_i
command: whoami
Command whoami shos (print) the current username.

2-groups
command: groups
This command show the ALL current user groups.

3-new_owner
command: chown
With this command you changes the owner of the file.

4-empty
command: touch
This one creates a empty file.

5-execute
command: chmod u+x
Command for create the file execute.

6-multiple_permissions
command: chmod u+x, g+x, o+r
Firts one, execute the file gives permission to the owner. Second one,execute the file and gives group owner permission. Thrid gives read permission fot other users.

7-everybody
command: chmod a+x
Is for specifies the permissions change.

8-James_Bond
command: chmod 007 hello
0= owner with no permissions
0= group no permissions
7= other all the permissions

9-John_Doe
command: chmod 753 hello
They divide into groups of three.
rwx=7
r-x=5
-wx=3

10-mirror_permissions
command: chmod --reference=olleh helo
This copys exactly all permission of the file.

11-directories_permissions
command:find . -type d -exec chmod a+x {} +
This full command is for gives permissions to all subdirectories of the actual owner, the groups owner and all other users.

12-directory_permissions
command: mkdir -m 751 my_dir
I creates a directory with the permissions 751

13-changes_group
command: chgrp
With this command I can change the group owner 'school' to the file 'hello'.

14-change_owner_and_group
command: chown vincent:staff *
This change owner to vincent and group to staff.

15-symbolic_link_permissions
command: 