
# Shell, I/O Redirections and file filters

*This directory contains bash scripts that*:
---
1. `0-hello_world` : Prints “Hello, World”, followed by a new line to the standard output. 

2. `1-confused_smiley` : Displays a confused smiley "(Ôo)'.

3. `2-hellofile` : Displays the content of the /etc/passwd file.

4. `3-twofiles` : Displays the content of /etc/passwd and /etc/hosts.

5. `4-lastlines` : Displays the last 10 lines of /etc/passwd.

6. `5-firstlines` : Displays the first 10 lines of /etc/passwd.

7. `6-third_line` : Displays the third line of the file iacta.

8. `7-file` : Creates a file named with special characters containing the text "Best School" ending by a new line.

9. `8-cwd_state` : Writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

10. `9-duplicate_last_line` : Duplicates the last line of the file iacta.

11. `10-no_more_js` : Deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

12. `11-directories` : Counts the number of directories and sub-directories in the current directory.
	* The current and parent directories will not be taken into account.
	* Hidden directories will be counted.

13. `12-newest_files` : Displays the 10 newest files in the current directory. Sorted from newest to oldest, one file per line.

14. `13-unique` : Takes a list of words as input and prints only words that appear exactly once. Output will be sorted.

15. `14-findthatword` : Displays lines containing the pattern “root” from the file /etc/passwd.

16. `15-countthatword` : Displays the number of lines that contain the pattern “bin” in the file /etc/passwd.

17. `16-whatsnext` : Displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
