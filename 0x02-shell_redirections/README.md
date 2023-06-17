Readme file for 0x02 Shell redirections tasks
=============================================

>  Special notations we can redirect the output of many commands to files, devices, and even to the input of other commands

**task 0** *echo* : prints the text in the output

**task 1** *echo with backslach "\"* : prints with escape characters

**task 2** *cat* : print content of file 

**task 3** same as task 2 but with two files at once

**task 4** *tail* : show and print the last lines from a file 10 lines par default

**task 5** *head* : show first 10 lines of a file 

**task 6** *head* | tail : filtering one line by piping output of first command as input of second command

**task 7** *echo* with escape characters 

**task 8** *ls > file* : overwrite output of the command to a file as a text

**task 9** *tail -n 1 file  >> file* : duplicating last line in files by apeending output of command to the file

**task 10** *find - type f -delete* : find a file type in path given and delete

**task 11** *find -mindepth 1 -type d | wc -l* : find with subdirectories level and not in level of the directory itself and put the output as input of wc command to count the lines 
