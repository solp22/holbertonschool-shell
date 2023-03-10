<h1 align="center">Project: Shell, I/O Redirections and filters</h1>

## Resources
<ul>
  <li>echo</li>
  <li>cat</li>
  <li>head</li>
  <li>tail</li>
  <li>find</li>
  <li>wc</li>
  <li>sort</li>
  <li>uniq</li>
  <li>grep</li>
  <li>tr</li>
  <li>rev</li>
  <li>cut</li>
  <li>passwd</li>
</ul>

## Learning Objectives

### Shell, I/O Redirection
<ul>
  <li>What do the commands head, tail, find, wc, sort, uniq, grep, tr do</li>
  <li>How to redirect standard output to a file</li>
  <li>How to get standard input from a file instead of the keyboard</li>
  <li>How to send the output from one program to the input of another program</li>
  <li>How to combine commands and filters with redirections</li>
</ul>

### Special Characters
<ul>
  <li>What are special characters</li>
  <li>Understand what do the white spaces, single quotes, double quotes, backslash, comment, pipe, command separator, tilde and how and when to use them</li>
</ul>

### Other Man Pages
<ul>
  <li>How to display a line of text</li>
  <li>How to concatenate files and print on the standard output</li>
  <li>How to reverse a string</li>
  <li>How to remove sections from each line of files</li>
  <li>What is the /etc/passwd file and what is its format</li>
  <li>What is the /etc/shadow file and what is its format</li>
</ul>

## Tasks

### 0. Hello World
Write a script that prints “Hello, World”, followed by a new line to the standard output.

### 1. Confused smiley
Write a script that displays a confused smiley "(Ôo)'.

### 2. Let's display a file
Display the content of the /etc/passwd file.

### 3. What about 2?
Display the content of /etc/passwd and /etc/hosts

### 4. Last lines of a file
Display the last 10 lines of /etc/passwd

### 5. I'd prefer the first ones actually
Display the first 10 lines of /etc/passwd

### 6. Line #2
Write a script that displays the third line of the file iacta. You’re not allowed to use sed.

### 7. It is a good file that cuts iron without making a noise
Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

### 8. Save current state of directory
Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

### 9. Duplicate last line
Write a script that duplicates the last line of the file iacta

### 10. No more javascript
Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

### 11. Don't just count your directories, make your directories count
Write a script that counts the number of directories and sub-directories in the current directory.
<ul>
  <li>The current and parent directories should not be taken into account</li>
  <li>Hidden directories should be counted</li>
</ul>

### 12. What’s new
Create a script that displays the 10 newest files in the current directory.
Requirements:
<ul>
  <li>One file per line</li>
  <li>Sorted from the newest to the oldest</li>
</ul>

### 13. Being unique is better than being perfect
Create a script that takes a list of words as input and prints only words that appear exactly once.
<ul>
  <li>Input format: One line, one word</li>
  <li>Output format: One line, one word</li>
  <li>Words should be sorted</li>
</ul>

### 14. It must be in that file
Display lines containing the pattern “root” from the file /etc/passwd

### 15. Count that word
Display the number of lines that contain the pattern “bin” in the file /etc/passwd

### 16. What's next?
Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

### 17. I hate bins
Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

### 18. Letters only please
Display all lines of the file /etc/ssh/sshd_config starting with a letter. Include capital letters as well.

### 19. A to Z
Replace all characters A and c from input to Z and e respectively.

### 20. Without C, you would live in hiago
Create a script that removes all letters c and C from input.

### 21. esreveR
Write a script that reverse its input.

### 22. DJ Cut Killer
Write a script that displays all users and their home directories, sorted by users, based on the the /etc/passwd file.

### 23. Empty casks make the most noise
Write a command that finds all empty files and directories in the current directory and all sub-directories.
<ul>
  <li>Only the names of the files and directories should be displayed (not the entire path)</li>
  <li>Hidden files should be listed</li>
  <li>One file name per line</li>
  <li>The listing should end with a new line</li>
  <li>You are not allowed to use basename, grep, egrep, fgrep or rgrep</li>
</ul>

### 24. A gif is worth ten thousand words
Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories.
<ul>
  <li>Hidden files should be listed</li>
  <li>Only regular files (not directories) should be listed</li>
  <li>The names of the files should be displayed without their extensions</li>
  <li>The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)</li>
  <li>One file name per line</li>
  <li>The listing should end with a new line</li>
  <li>You are not allowed to use basename, grep, egrep, fgrep or rgrep</li>
</ul>

### 25. Acrostic
An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval.

Create a script that decodes acrostics that use the first letter of each line.
<ul>
  <li>The ‘decoded’ message has to end with a new line</li>
  <li>You are not allowed to use grep, egrep, fgrep or rgrep</li>
</ul>

### 26. The biggest fan
Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
<ul>
  <li>Order by number of requests, most active host or IP at the top</li>
  <li>You are not allowed to use grep, egrep, fgrep or rgrep</li>
</ul>
Format:

```
host    When possible, the hostname making the request. Uses the IP address if the hostname was unavailable.
logname Unused, always -
time    In seconds, since 1970
method  HTTP method: GET, HEAD, or POST
url Requested path
response    HTTP response code
bytes   Number of bytes in the reply
```
