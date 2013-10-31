idirname
========

Interactive dirname.

If the input is a file, output the directory containing that file. If the input is a directory, keep it unchanged and redirect it to stdout.

### Examples
Example 1:
user@localhost$ idirname /home/user/file.txt

Output:
/home/user

Example 2:
user@localhost$ idirname /home/user/

Output:
/home/user

### Dependencies
- OS X users will need to install wc. GNU/Linux users probably already have it.

### Installation
- `git clone https://github.com/Antithesisx/idirname.git`
- Place idirname in your PATH and make sure it's executable:

```
sudo cp idirname /usr/local/bin/
sudo chmod +x /usr/local/bin/idirname
```

