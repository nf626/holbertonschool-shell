Shell, I/O Redirections and filters Tasks:<br>
0. Hello World - Write a script that prints "Hello, World", followed by a new line to the standard output.<br>
1. Confused smiley - Write a script that displays a confused smiley.<br>
2. Let's display a file - Display the content of the /etc/passwd file.<br>
3. What about 2? - Display the content of /etc/passwd and /etc/hosts.<br>
4. Last lines of a file - Display the last 10 lines of /etc/passwd.<br>
5. I'd prefer the first ones actually - Display the first 10 lines of /etc/passwd.<br>
6. Line #2 - Write a script that displays the third line of the file iacta.<br>
7. It is a good file that cuts iron without making a noise - Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.<br>
8. Save current state of directory - Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.<br>
9. Duplicate last line - Write a script that duplicates the last line of the file iacta.<br>
10. No more javascript - Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.<br>
11. Don't just count your directories, make your directories count - Write a script that counts the number of directories and sub-directories in the current directory.<br>
The current and parent directories should not be taken into account.<br>
Hidden directories should be counted.<br>
12.What's new - Create a script that displays the 10 newest files in the current directory.<br>
Requirements:<br>
One file per line.<br>
Sorted from the newest to the oldest.<br>
13. Being unique is better than being perfect - Create a script that takes a list of words as input and prints only words that appear exactly once.<br>
Input format: One line, one word.<br>
Output format: One line, one word.<br>
Words should be sorted.
14. It must be in that file - Display lines containing the pattern "root" from the file /etc/passwd.<br>
15. Count that word - Display the number of lines that contain the pattern "bin" in the file /etc/passwd.<br>
16. What's next? - Display lines containing the pattern "root" and 3 lines after them in the file /etc/passwd.<br>
17. I hate bins - Display all the lines in the file /etc/passwd that do not contain the pattern "bin".<br>
18. Letters only please - Display all lines of the file /etc/ssh/sshd_config starting with a letter.<br>
Include capital letters as well.<br>
19. A to Z - Replace all characters A and c from input to Z and e respectively.<br>
20. Without C, you would live in hiago - Create a script that removes all letters c and C from input.<br>
21. esreveR - Write a script that reverse its input.<br>
22. DJ Cut Killer - Write a script that displays all users and their home directories, sorted by users.<br>
Based on the the /etc/passwd file.<br>
23. Empty casks make the most noise - Write a command that finds all empty files and directories in the current directory and all sub-directories.<br>
Only the names of the files and directories should be displayed (not the entire path).<br>
Hidden files should be listed.<br>
One file name per line.<br>
The listing should end with a new line.<br>
You are not allowed to use basename, grep, egrep, fgrep or rgrep.<br>
24. A gif is worth ten thousand words - Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories.<br>
Hidden files should be listed.<br>
Only regular files (not directories) should be listed.<br>
The names of the files should be displayed without their extensions.<br>
The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)<br>
One file name per line.<br>
The listing should end with a new line.<br>
25. Acrostic - Create a script that decodes acrostics that use the first letter of each line.<br>
The 'decoded' message has to end with a new line.<br>
