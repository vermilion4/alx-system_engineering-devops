# SCRIPTS AND THEIR USAGE
## 0-current\_working\_directory
This script prints the absolute path name of the current working directory.
## 1-listit
This script displays the contents list of your current directory.
## 2-bring\_me\_home
This script changes the working directory to the user’s home directory.<br>
**NB: Run it using source ./2-bring\_me\_home**
## 3-listfiles
This script displays current directory contents in a long format.
## 4-listmorefiles
This script displays current directory contents, including hidden files (starting with .). Uses the long format.
## 5-listfilesdigitonly
Displays current directory contents.
- Long format
- with user and group IDs displayed numerically
- And hidden files (starting with .)
## 6-firstdirectory
This script creates a directory named my\_first\_directory in the /tmp/ directory.
## 7-movethatfile
This script moves the file betty from /tmp/ to /tmp/my\_first\_directory.
## 8-firstdelete
This script deletes the file betty in /tmp/my\_first\_directory.
## 9-firstdirdeletion
This script deletes the directory my\_first\_directory that is in the /tmp directory.
## 10-back
This script changes the working directory to the previous one.
## 11-lists
script that lists all files (even ones with names beginning with a period character, which are normally hidden)
- in the current directory and
- the parent of the working directory and 
- the /boot directory (in this order),
in long format.
## 12-file\_type
This is a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory.
## 13-symbolic\_link
This is a script that creates a symbolic link to /bin/ls, named \_\_ls\_\_ in the current working directory.
## 14-copy\_html
A script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
## 100-lets\_move
This is  a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
## 101-clean\_emacs
This is a script that deletes all files in the current working directory that end with the character ~.
## 102-tree
This is a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
