# About 0x00. Shell, Basics



What is "The Shell"?



Simply put, the shell is a program that takes commands from the keyboard and gives them to the operating system to perform. In the old days, it was the only user interface available on a Unix-like system such as Linux. Nowadays, we have graphical user interfaces (GUIs) in addition to command line interfaces (CLIs) such as the shell. [Learn more...](http://linuxcommand.org/lc3_lts0010.php)



This project presents the basic shell commands and their functionality 


# Scripts With The Shell Commands 

[0-current_working_directory:](./0-current_working_directory)
A script that prints the absolute path name of the current working directory.

[1-listit:](./1-listit)
A script that displays the contents list of your current directory.

[2-bring_me_home:](./2-bring_me_home)
A script that changes the working directory to the user’s home directory.

[3-listfiles:](./3-listfiles)
A script that displays current directory contents in a long format

[4-listmorefiles:](./listmorefiles)
A script that displays current directory contents, including hidden files (starting with .). Use the long format.

[5-listfilesdigitonly:](./5-listfilesdigitonly)
A script that displays current directory contents in long format, with user and group IDs displayed numerically and hidden files (starting with .)

[6-firstdirectory:](./6-firstdirectory)
A script that creates a directory in a specified location

[7-movethatfile:](./7-movethatfile)
A scripts that moves a file from one directory to another

[8-firstdelete:](./8-firstdelete)
A script that deletes a file

[9-firstdirdeletion:](./9-firstdirdeletion)
A script that deletes a directory

[10-back:](./10-back)
A script that changes the working directory to the previous one.

[11-lists:](./11-lists)
A script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

[12-file_type:](./12-file_type)
A script that prints the type of the file named iamafile. The file iamafile is in the /tmp directory when we will run your script.

[13-symbolic_link:](./13-symbolic_link)
A script that creates a symbolic link to /bin/ls, named __ls__ in the current working directory 

[14-copy_html:](./14-copy_html)
A script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
