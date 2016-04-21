cd #Return to home directory

clear #clears all text from screen. actually it just wraps the text up. you can still see previous output by scrolling up.

file <file path> #gives you information about the contents of a file

stat <file path> #give you metadata on the file path

history | grep <search term> #search previous commands for a given term. this is really, really, helpful. 

readlink -f <symbolic link> # follows symbolic link chains to the real file

ps aux | grep <program or user name> #search list of current processes

find <path> -type f -iname "*<term>*" # recursively search from <path> to fine all files with <term> in name. For example: find . -type f -iname "*vacation*"

sudo apt install -y <package name> # install package

sudo apt search <search term> # search repos for packages containing search term

sudo fdisk -l # list conventional disks attached

