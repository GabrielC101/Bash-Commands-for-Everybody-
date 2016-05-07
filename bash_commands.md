##Moving around with bash.

Return to home directory:
```bash
cd
```

Move to new directory using absolute path:
```bash
cd /home/my_name/Videos/
```

Move to new directory using relative path:
```bash
cd new_parent_directory/directory_to_enter/
```

Return to previous directory
```bash
cd -
```

##ls command

List all visible (non-hidden) files.
```bash
ls
```

List all files, including hidden, but excluding virtual files (i.e. "." and "..").
```bash
ls -A
```

Show all files with metadata.
```bash
ls -lh
```
To sort by most recent modified
```bash
ls -lht
```



##Misc Commands

Clears all text from screen. actually it just wraps the text up. you can still see previous output by scrolling up:
```bash
clear 
```

Gives you information about the contents of a file
```bash
file <file path> 
```

Give you metadata on the file path
```bash
stat <file path> 
```

Search previous commands for a given term. this is really, really, helpful. 
```bash
history | grep <search term> 
```

Follows symbolic link chains to the real file
```bash
readlink -f <symbolic link> 
```

Search list of current processes
```bash
ps aux | grep <program or user name> 
```

Recursively search from <path> to fine all files with <term> in name. For example: find . -type f -iname "*vacation*"
```bash
find <path> -type f -iname "*<term>*" 
```

Install package
```bash
sudo apt install -y <package name> 
```

Search repos for packages containing search term
```bash
sudo apt search <search term> 
```

List conventional disks attached
```bash
sudo fdisk -l 
```

List block device attributes (hard drives and such)
```bash
sudo blkid 
```

List all devices attached by usb
```bash
sudo usb-devices 
```

Calculate size of directory:
```bash
du -hs
```
