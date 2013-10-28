idirname
========

Interactive dirname.

If the input is a file, output the directory containing that file. If the input is a directory, keep it unchanged and redirect it to stdout.

### Dependencies
- OS X users will need to install wc. GNU/Linux users probably already have it.

### Installation
- Place idirname in your PATH and make sure it's executable:

```
sudo cp idirname /usr/bin/
sudo chmod +x /usr/bin/idirname
```

### Examples
Example 1:
user@localhost$ idirname /home/user/file.txt

Output:
/home/user

Example 2:
user@localhost$ idirname /home/user/

Output:
/home/user
