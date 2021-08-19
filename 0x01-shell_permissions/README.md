0) su betty => switches the current user to betty.

1) whoami => prints the effective username of the current user.

2) groups => lists all the groups a current user is part of.

3) chown betty hello => changes user of hello to betty.

4) touch hello => creates an empty file called hello.

5) chmod u+x hello => adds execute permission to the owner of file hello.

6) chmod ug+x,o+r hello => gives execute permission to owner and group owner, and read permission to the user.

7) chmod a+x hello => gives execute permission to owner, group owner and users.

8) chmod 007 hello => removes all permissions for owner and grouo owner and gives all permissions to the user.

9) chmod 753 hello sets the mode of the file to -rwxr-x-wx.

10) chmod --reference=olleh hello sets same permissions olleh has to hello.

11) chmod -R+X. executes permissions to all subdirectories of current directory for owner, group ownerad user, regular files are not changed.