<h1 align="center">Project: Shell, Basics</h1>

## Resources
<ul>
 <li>cd</li>
 <li>ls</li>
 <li>pwd</li>
 <li>less</li>
 <li>file</li>
 <li>ln</li>
 <li>cp</li>
 <li>mv</li>
 <li>rm</li>
 <li>mkdir</li>
 <li>type</li>
 <li>which</li>
 <li>help</li>
 <li>man</li>
</ul>

## Learning Objectives

### Shell
 <ul>
  <li>What is the shell</li>
  <li>What is the difference between a terminal and a shell</li>
  <li>What is the shell prompt</li>
  <li>How to use the history (the basics)</li>
 </ul>
 
 ### Navigation
 <ul>
  <li>What do the commands or built-ins cd, pwd, ls do</li>
  <li>How to navigate the filesystem</li>
  <li>What are the . and .. directories</li>
  <li>What is the working directory, how to print it and how to change it</li>
  <li>What is the root directory</li>
  <li>What is the home directory, and how to go there</li>
  <li>What is the difference between the root directory and the home directory of the user root</li>
  <li>What are the characteristics of hidden files and how to list them</li>
  <li>What does the command cd - do</li>
 </ul>
 
 ### Looking Around
 <ul>
  <li>What do the commands ls, less, file do</li>
  <li>How do you use options and arguments with commands</li>
  <li>Understand the ls long format and how to display it</li>
  <li>What does the ln command do</li>
  <li>What do you find in the most common/important directories</li>
  <li>What is a symbolic link</li>
  <li>What is a hard link</li>
  <li>What is the difference between a hard link and a symbolic link</li>
 </ul>
 
 ### Manipulating Files 
 <ul>
  <li>What do the commands cp, mv, rm, mkdir do</li>
  <li>What are wildcards and how do they work</li>
  <li>How to use wildcards</li>
 </ul>
 
 ### Working with Commands
 <ul>
  <li>What do type, which, help, man commands do</li>
  <li>What are the different kinds of commands</li>
  <li>What is an alias</li>
  <li>When do you use the command help instead of man</li>
 </ul>

## Tasks

### 0. Where am I?
<p> Write a script that prints the absolute path name of the current working directory. </p>

### 1. What’s in there?
<p>Display the contents list of your current directory.</p>

### 2. There is no place like home
<p>Write a script that changes the working directory to the user’s home directory.</p>

### 3. The long format
<p>Display current directory contents in a long format</p>

### 4. Hidden files
<p>Display current directory contents, including hidden files (starting with . ). Use the long format.</p>

### 5. I love numbers
<p>Display current directory contents.</p>

### 6. Welcome
<p>Create a script that creates a directory named my_first_directory in the /tmp/ directory.</p>

### 7. Betty in my first directory
<p>Move the file betty from /tmp/ to /tmp/my_first_directory.</p>

### 8. Bye bye Betty
<p>Delete the file betty. The file betty is in /tmp/my_first_directory.</p>

### 9. Bye bye My first directory
<p>Delete the directory my_first_directory that is in the /tmp directory.</p>

### 10. Back to the future
<p>Write a script that changes the working directory to the previous one.</p>

### 11. Lists
<p>Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.</p>

### 12. File type
<p>Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.</p>

### 13. We are symbols, and inhabit symbols
<p>Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.</p>

### 14. Copy HTML files
<p>Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.</p>

### 15. Let’s move
<p>Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.</p>

### 16. Clean Emacs
<p>Create a script that deletes all files in the current working directory that end with the character ~.</p>

### 17. Tree
<p>Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. You are only allowed to use two spaces (and lines) in your script, not more.</p>
