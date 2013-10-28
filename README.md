idirname
========

Interactive dirname.

If the input is a file, output the directory containing that file. If the input is a directory, keep it unchanged and redirect it to stdout.

Example 1:
user@localhost$ idirname /home/user/file.txt

Output:
/home/user

Example 2:
user@localhost$ idirname /home/user/

Output:
/home/user
