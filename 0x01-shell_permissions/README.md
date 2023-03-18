Shell permissions project
0 su betty changes the user to betty
1 whoami prints the effective username of the current user
2 groups prints all the groups the current user is part of
3 chmod betty hello changes ownership of the file hello from current owner to betty
4 touch hello creates an empty file called hello
5 chmod u+x hello gives the owner of the file hello execute permissions
6 chmod +144 hello adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
7 chmod +x hello adds execution permissions to owner, groups and others, to the file hello
8 chmod 007 hello restricts all permissions to owner and group and gives all permssions to others, to the file hello
9 chmod 753 hello changes the file hello mode to -rwxr-x-wx
10 chmod --reference=olleh hello sets the mode of the file hello the same as olleh’s mode
11 chmod -R ugo+X* adds execute permission to all subdirectories of the current directory for the owner, 
   the group owner and all other users. Regular files should not be changed
12 mkdir -m 751 my_dir creates a directory called my_dir with permissions 751 in the working directory
13 chown :school hello changes the group owner to school for the file hello


