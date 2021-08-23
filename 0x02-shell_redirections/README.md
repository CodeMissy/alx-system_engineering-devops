0) echo "Hello, World" => prints "Hello, World" followed by a new line to the standard output.

1) echo "\"(  )"  displays a confused emoji to the screen.

2) cat /etc/passwd => displays the content of /etc/passwd files.

3) cat /etc/passwd /etc/hosts displays the content of the two files.

4) tail -10 /etc/passwd => displays the last 10 lines of /etc/passwd.

5) head -10 /etc/passwd => displays the first 10 lines of /etc/passwd.

6) head -3 iacta | tail +3 => displays the third line of the file iacta.

7)echo "Best School" > \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) => creates the file including the text Best School.

8) tail -1 iacta >> iacta => duplicates the last line of the file iacta.

10)find -type f -name '*.js' -delete => removes all files ending with a .js extensionn in currentt and sufolders directory.

11) find . -type d -not -name '.'| wc -l => counts the numbers of directories and sub directories in current directory.

12) ls -t1 | head -n 10  => is used to access the newest 10 files in the current directory. this searches out the 10 most recent files but not recently modificated file.

13) sort | uniq -u => takes a list of words and prints only words that appears only once.

14) grep -i "root" /etc/passwd => this displays lines containing the pattern "root" from the file /etc/passwd.

15) grep -c -i "bin" /etc/passwd => this displays the number of lines that contains the pattern "bin" inthe file /etc/passwd.

16) grep -c "root" -A 3 /etc/passwd => this displays lines containing the pattern "root" and 3 lines after them in the file /etc/passwd.

17) grep -i -v "bin" /etc/passwd => this command displays all the lines in the file /etc/passwd that do not contain the pattern bin.