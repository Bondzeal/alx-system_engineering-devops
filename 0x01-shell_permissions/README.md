__Shell Permission__
* 0-iam_betty file contains a script that switches the current user to the user "betty".
* 1-who_am_i file consists of a script that prints the effective username of the current user.
* 2-groups file contains a script that prints all the groups the current user is part of.
* 3-new_owner consists of a script that changes the owner of the file "hello" to the user "betty".
* 4-empty contains a script that creates an empty file called "hello".
* 5-execute file adds execute permission to the owner of the file "hello".
* 6-multiple_permissions consits of a script that executes permission to the owner and the group owner, and read permission to other users, to the file "hello".
* 7-everybody consists of a script that adds execution permission to all users to the file "hello".
* 8-James_Bond consists of a script that has set owner to no permission at all, group owners to no permission and other users have all permissions.
* 9-John_Doe sets mode of file to -rwxr-x-wx.
* 10-mirror_permissions sets mode of "hello" file same as "olleh" mode.
* 11-directories_permissions adds execute permission to all subdirectories of current directory for all.
* 12-directory_permissions creates a directory called "my_dir" with permission 751.
* 13-change_group consists of a script that changes the group owner.
* 100-change_owner_and_group changes owner and group owner
* 101-symbolic_link_permissions changes the owner and the group owner of "_hello" to "vincent" and "staff" respectively.
* 102-if_only changes the owner of the file "hello" to "betty" only if is owned by the user "guillaume".
* 103-Star_Wars consists of a script that plays StarWarsIV episode in the terminal. 
