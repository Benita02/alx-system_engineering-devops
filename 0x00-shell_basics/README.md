#!/bin/bash
script that prints the absolute path name of the current working directory
2-bring_me_home: a script that changes the working directory to the user’s home directory
4-listmorefiles - Display current directory contents, including hidden files (starting with .). Use the long format.
5-listfilesdigitonly - Display current directory contents in long format, with user and group IDs displayed numerically, and hidded files starting with a fullstop (.)
6-firstdirectory - creates a script that creates a directory named my_first_directory in the tmp directory
7-movethatfile - moves the file betty from the directory tmp to the other directory inside tmp - /tmp/my_first_directory
8-firstdelete - Deletes the file betty form /tmp/my_first_directory
9-firstdirdeletion - deletes the directory my_first_directory that is in the /tmp directory.
10-back - a script that changes the working directory to the previous one
11-lists - Writes a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12-file_type - a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
13-symbolic_link
14-copy_html - creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

You can consider that all HTML files have the extension .html
100-lets_move - Scrpt that moves all files beginning with an uppercase letter to the directory /tmp/u.
101-clean_emacs - creates a script that deletes all files in the current working directory that end with the character ~
102-tree - creates  a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
103-commas -Write a command that lists all the files and directories of the current directory, separated by commas (,).

Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
Creates  a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
