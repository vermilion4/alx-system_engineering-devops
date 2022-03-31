# SHELL PERMISSIONS SCRIPTS AND USAGE
## 0-iam\_betty
A script that switches the current user to the user betty.
## 1-who\_am\_i
A script that prints the effective username of the current user.
## 2-groups
A script that prints all the groups the current user is part of.
## 3-new\_owner
A script that changes the owner of the file hello to the user betty.
## 4-empty
A script that creates an empty file called hello.
## 5-execute
A script that adds execute permission to the owner of the file hello.
## 6-multiple\_permissions
A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
## 7-everybody
A script that adds execution permission to the owner, the group owner and the other users, to the file hello.
## 8-James\_Bond
A script that sets the permission to the file hello as follows:
- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions.
## 9-John\_Doe
A script that sets the permission to the file hello as follows:            
- Owner: all the permissions                                              
- Group: read and execute permissions only                                
- Other users: write and execute permissions only.
## 10-mirror\_permissions
A script that sets the mode of the file hello the same as olleh’s mode.
## 11-directories\_permissions
A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files are be changed.
## 12-directory\_permissions
A script that creates a directory called my\_dir with permissions 751 in the working directory.                                              
