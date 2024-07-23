#Basic Linux Commands
Created: 2024-07-06 11:51

##References
1. how to find human-readable files of the size 1033 bytes and are non executable can be found using the following commands:

- find inhere -size 1033c {
- inhere - this is the name of the folder in which we are doing the search
- find - this is used to search for specific parameters
- c = denotes the type of size being asked for. eg: bytes = c, kilobytes =k and so on}
- because the file is hidden cos is starts with a . you list the content with the command "cat" preceding the path to the hidden file

2. Finding only human-readable files 
- you use the find --*
- then you cat --\\-(filename)

   level 6-7
3.  find / -type f -user bandit7 -group bandit6 -size 33c - - owned by user bandit7
- owned by group bandit6
- 33 bytes in size 
- after this you do "cat /var/lib/dpkg/info/bandit7.password"

file descriptors in linux
0 - stdin
1- stdout
2 - stderror

you can redirect all your errors if you dont want it to dev/null using 2>/dev/null 

grep  is used to find content in a file

"strings" prints the printable characters in a file

"|" using the pipe means i want to use the output  of an action as an input for my next command or action you want to run on the output you get.

little endien - picks from the smallest and pads it with 0 before the actual figure
big endien - picks the big number and pads the rest with 0


file permissions in linux

Absolute
421 = read write execute

symbolic
you use the first letter of each body u=user, g=group, o=other
and you use chmod(change mode of access) to give permission to everyone or remove permissions 

you use the plus sign(+) to add permissions and (-) to remove permissions



