Return to home directory:
```bash
cd
```

Clears all text from screen. actually it just wraps the text up. you can still see previous output by scrolling up:
```bash
clear 
```

Gives you information about the contents of a file
```bash
file <file path> 
```

```bash
stat <file path> #give you metadata on the file path
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
