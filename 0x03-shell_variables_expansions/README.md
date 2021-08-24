0) alias ls="rm *"   => this command creates an alias giving ls the value of rm *.

1) echo hello $USER => this command prints the word "hello user" replacing user with the current user. ~ is a character that prints user

3) PATH=$PATH:/action => this command adds the directory /action to PATH..

4) echo $PATH | tr ":" "\n" | wc -l => this command finds the number of directories in the path.

5) printenv => lists all environment variables.

6) set => this command lists all variables, both environmental variables, local variables, and functions.

7) export HOLBERTON='Betty' => to create a new local variable with HOLBERTON as the name, and Betty as the value.

8) echo $((128 + TRUEKNOWLEDGE)) => this string performs an addition of 128 with the value stored in environment variable TRUEKNOWLEDGE.

9) echo $(((POWER) / DIVIDE)) => this prints the result of POWER divided by DIVIDE.

10) echo $((BREATH ** LOVE)) => this prints the result of BREATH raised to power of LOVE.

11) echo $((2#BINARY)) => this string converts binary numbers also known as base 2 numbers to base 10 or decimal.

12) echo {a..z}{a..z}|tr " " $'\n'|grep oo -v => this prints all possible combinations of two letter words.

13) printf '%.2f\n' $NUM => this string prints a number to two decimal places.