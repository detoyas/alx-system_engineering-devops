Readme file for Shell permissions Tasks
=======================================
             
*The scripts always has a bash bin as a first line then the builtin command in second line*

0 **su** : switch to user
 
1 **whoami** : prints current user

2 **groups** : prints lis of groups

3 **chown** : change owner of the file

4 **touch** : create new empty file 

5 **chmod u+x** : add excution permission to user

6 **chmod u+x,g+x,o+r** : add specific permission to either user or group or other

7 **chmod a+x** : add excution permission to all 

8 **chmod 007** : set no permission to the user and group and all permissions to others

9 **chmod 753** : set rwx to user , r-x to group , -wx to others 

10 **chmod --reference=** : copy permissions from a reference file to another file

11 **chmod -R a+x** : add excution permission to all , -R option for subdirectories also

12 **mkdir -m** : create a directory with specific permissions

13 **chgrp** : change group owner of a file 
