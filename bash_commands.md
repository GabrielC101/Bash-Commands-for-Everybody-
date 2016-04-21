```bash
cd #Return to home directory
```
```bash
clear #clears all text from screen. actually it just wraps the text up. you can still see previous output by scrolling up.
```

```bash
file <file path> #gives you information about the contents of a file
```

```bash
stat <file path> #give you metadata on the file path
```

```bash
history | grep <search term> #search previous commands for a given term. this is really, really, helpful. 
```

```bash
readlink -f <symbolic link> # follows symbolic link chains to the real file
```

```bash
ps aux | grep <program or user name> #search list of current processes
```

```bash
find <path> -type f -iname "*<term>*" # recursively search from <path> to fine all files with <term> in name. For example: find . -type f -iname "*vacation*"
```

```bash
sudo apt install -y <package name> # install package
```

```bash
sudo apt search <search term> # search repos for packages containing search term
```

```bash
sudo fdisk -l # list conventional disks attached
```

```bash
sudo blkid # list block device attributes (hard drives and such)
```

```bash
sudo usb-devices # list all devices attached by usb
```
