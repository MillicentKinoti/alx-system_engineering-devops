## 0x00-SHELL BASICS

Make scripts executable : chmod u+x [name of the file]

<h3>0-current_working directory</h3>
This script prints out the current working directory

<h3> 1-listit </h3>
Displays the contents list of your current directory.

<h3>2-bring_me_home </h3>
Changes the working directory to the user's home directory.

<h3>3-listfiles</h3>
Displays the current directory contents in long format.

<h3>4-listmore-files </h3>
Displays the current directory contents, including hidden files (starting with .) usinf the long format.


<h3>5-listfilesdigitonly </h3>
Display current directory contents inLong format with user and group IDs displayed numerically and hidden files (starting with .)

<h3>6-firstdirectory</h3>
Creates a directory named my_first_directory in the /tmp/ directory.
 
<h3>7-movethatfile</h3>
Moves the file betty from /tmp/ to /tmp/my_first_directory.

<h3>8-firstdelete</h3>
Delete the file betty in /tmp/my_first_directory

<h3>9-firstdirdeletion</h3>
Deletes the directory my_first_directory that is in the /tmp directory.

<h3>10-back</h3>
Changes the working directory to the previous one

<h3>11-lists</h3>
lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

<h3>12-file_type</h3>
Prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when the script runs

<h3>13-symbolic_link</h3>
Creates a symbolic link to /bin/ls, named __ls__ in the current working directory.

<h3>14-copy_html</h3>
Copies all the HTML files from the current working directory to the parent of the working directory, but only copies files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

<h3>100-lets_move</h3>
Moves all files beginning with an uppercase letter to the directory /tmp/u

<h3>101-clean_emacs</h3>
Deletes all files in the current working directory that end with the character ~

<h3>102-tree</h3>
Creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

<h3>103-commas</h3>
lists all the files and directories of the current directory, separated by commas (,).Directory names should end with a slash (/). Files and directories starting with a dot (.) should be listed .The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
<h3>school.mgc</h3>
a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

