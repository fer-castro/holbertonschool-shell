0 su betty - Create a script that switches the current user to the user betty. You should use exactly 8 characters for your command (+1 character for the new line) You can assume that the user betty will exist when we will run your script.

1 id -un - Write a script that prints the effective username of the current user.

2 id -Gn - Write a script that prints all the groups the current user is part of.

3 chown betty hello - Write a script that changes the owner of the file hello to the user betty.

4 touch hello - Write a script that creates an empty file called hello.

5 chmod u+x hello - Write a script that adds execute permission to the owner of the file hello. The file hello will be in the working directory.

6 chmod ug+x,o+r hello - Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello. The file hello will be in the working directory.

7 chmod ugo+x hello - Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello. The file hello will be in the working directory. You are not allowed to use commas for this script.

8 chmod 007 hello - Write a script that sets the permission to the file hello as follows: Owner: no permission at all. Group: no permission at all. Other users: all the permissions The file hello will be in the working directory You are not allowed to use commas for this script.

9 chmod 753 hello - Write a script that sets the mode of the file hello to this: The file hello will be in the working directory. You are not allowed to use commas for this script.

10 chmod --reference=olleh hello - Write a script that sets the mode of the file hello the same as olleh’s mode. The file hello will be in the working directory. The file olleh will be in the working directory.

11 chmod -R +X . - Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

12 mkdir -m 751 my_dir - Create a script that creates a directory called my_dir with permissions 751 in the working directory.

13 chgrp school hello - Write a script that changes the group owner to school for the file hello. The file hello will be in the working directory.

14 chown vincent:staff * - Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

15 chown -h vincent:staff _hello - Write a script that changes the owner and the group owner of _hello to vincent and staff respectively. The file _hello is in the working directory. The file _hello is a symbolic link.

16 chown --from=guillaume vincent hello - Write a script that changes the owner of the file hello to vincent only if it is owned by the user guillaume. The file hello will be in the working directory.
