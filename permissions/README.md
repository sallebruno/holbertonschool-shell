0-iam betty - switches the current user to the user betty
1-who am i - prints the effective username of the current user.
2-groups - prints all the groups the current user is part of.
3-new owner - changes the owner of the file hello to the user betty.
4-empty - creates an empty file called hello.
5-execute - adds execute permission to the owner of the file hello.
6-multiple permissions - adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7-everybody - adds execution permission to the owner, the group owner and the other users, to the file hello
8-James Bond - sets the permission to the file hello as follows: Owner: no permission at all, Group: no permission at all, Other users: all the permissions
9-John Doe - sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
10-mirror permissions - sets the mode of the file hello the same as olleh’s mode.
11-directories permissions - adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
12-directory permissions - creates a directory called my dir with permissions 751 in the working directory.
13-change group - changes the group owner to school for the file hello
14-change owner and group - changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
15-symbolic link permissions - changes the owner and the group owner of _hello to vincent and staff respectively.
16-if_only - changes the owner of the file hello to vincent only if it is owned by the user guillaume.
