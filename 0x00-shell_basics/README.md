1. 0-current_working_directory : A bash script that prints the absolute path name of the current working directory.

2. 1-listit : A bash script that displays the contents list of your current directory.

3. 2-bring_me_home :  A bash script that changes the working directory to the user’s home directory.

4. 3-listfiles : A bash script that displays current directory contents in a long format.

5. 4-listmorefiles : A bash script that displays current directory contents, including hidden files (starting with .). Using the long format.

6. 5-listfilesdigitonly : A bash script that displays current directory contents.
	- In long format
	- With user and group IDs displayed numerically
	- And hidden files (starting with .)

7. 6-firstdirectory : A bash script that creates a directory named my_first_directory in the /tmp/ directory.

8. 7-movethatfile : A bash script that moves a file betty from /tmp/ to /tmp/my_first_directory.

9. 8-firstdelete : A bash script that deletes the file betty from /tmp/my_first_directory.

10. 9-firstdirdeletion : A bash script that deletes the my_first directory in /tmp

11. 10-back : A bash script that changes the working directory to the previous one.

12. 11-lists : A bash script thats lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

13. 12-file_type : A bash script that prints the type of the file named iamafile in /tmp.

14. 13-symbolic_link : A bash script that creates a symbolic link to /bin/ls, named __ls__ in the current working directory.

15. 14-copy_html : A bash script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

16. 100-lets_move : A bash script that moves all files beginning with an uppercase letter to the directory /tmp/u.

17. 101-clean_emacs : A bash script that deletes all files in the current working directory that end with the character ~.

18. 102-tree : A bash script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

19. 103-commas : A bash script that lists all the files and directories of the current directory, separated by commas (,).
	- Directory names will end with a slash (/).
	- Files and directories starting with a dot (.) will be listed.
	- The listing will be alpha ordered, except for the directories . and .. which will be listed at the very beginning.
	- Only digits and letters are used to sort; Digits will come first.
	- All the files are assumed to have at least one letter or one digit.
	- The listing will end with a new line.

20. school.mgc : A magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
