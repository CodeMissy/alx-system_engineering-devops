0) alias [-p] [ls="rm *"]   => this command creates an alias giving ls the value of rm *.

1) echo hello $USER => this command prints the word "hello user" replacing user with the current user. ~ is a character that prints user

3) PATH=$PATH:/action => this command adds the directory /action to PATH..

4) echo $PATH | tr ":" "\n" | wc -l => this command finds the number of directories in the path.

5) printenv => lists all environment variables.

6) set => this command lists all variables, both environmental variables, local variables, and functions.

7) export HOLBERTON='Betty' => to create a new local variable with HOLBERTON as the name, and Betty as the value.