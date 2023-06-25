# Shell, I/O Redirections and Filters - Amateur

## Project Description

This project focuses on shell scripting and introduces concepts related to I/O redirections and filters. The tasks in this project require you to write shell scripts that perform various operations using commands such as `echo`, `cat`, `head`, `tail`, `find`, `wc`, `sort`, `uniq`, `grep`, `tr`, `rev`, and `cut`. You will also learn about special characters and their usage.

The project consists of several tasks, each with its own objective and requirements. You will write scripts to accomplish specific tasks, such as printing messages, displaying file contents, extracting specific lines from files, and manipulating file content. The tasks progressively build upon each other, allowing you to practice and apply the concepts you learn.

## Learning Objectives

By completing this project, you will be able to:

- Explain the concepts of shell scripting and I/O redirections to others
- Understand the purpose and usage of commands such as `head`, `tail`, `find`, `wc`, `sort`, `uniq`, `grep`, `tr`, `rev`, and `cut`
- Redirect standard output to a file
- Get standard input from a file instead of the keyboard
- Send the output from one program to the input of another program
- Combine commands and filters with redirections
- Recognize and use special characters effectively in shell scripts

## Requirements

- Allowed editors: vi, vim, emacs
- All scripts will be tested on Ubuntu 20.04 LTS
- All scripts should consist of exactly two lines (use `wc -l file` to verify)
- All files should end with a new line character
- The first line of all files should be `#!/bin/bash`
- Include a `README.md` file at the root of the project folder, describing each script's purpose
- Do not use backticks (\`), `&&`, `||`, or `;` in your scripts
- All files must be executable (`chmod u+x file`)
- Do not use `sed` or `awk` in your scripts

## Tasks

### Task 0: Hello World

Write a script that prints "Hello, World" to the standard output, followed by a new line.

Example:
$ ./0-hello_world
Hello, World


### Task 1: Confused smiley

Write a script that displays a confused smiley `(Ôo)'`.

Example:
$ ./1-confused_smiley
"(Ôo)'


### Task 2: Let's display a file

Display the content of the `/etc/passwd` file.

Example:
$ ./2-hellofile
<content of /etc/passwd>


### Task 3: What about 2?

Display the content of both the `/etc/passwd` and `/etc/hosts` files.

Example:
$ ./3-twofiles
<content of /etc/passwd>
<content of /etc/hosts>


### Task 4: Last lines of a file

Display the last 10 lines of the `/etc/passwd` file.

Example:
$ ./4-lastlines
<last 10 lines of /etc/passwd>


### Task 5: I'd prefer the first ones actually

Display the first 10 lines of the `/etc/passwd` file.

Example:
$ ./5-firstlines
<first 10 lines of /etc/passwd>



### Task 6: Line #2

Write a script that displays the third line of the file `iacta`.

Example:

$ ./6-third_line
Alea iacta est


### Task 7: It is a good file that cuts iron without making a noise

Write a shell script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School`.

Example:
$ ls
0-hello_world 1-confused_smiley 2-hellofile 3-twofiles 4-lastlines 5-firstlines 6-third_line "7-file_name" README.md
$ cat 7-file_name
Best School


### Task 8: Save current state of directory

Write a script that writes into the file `ls_cwd_content` the result of the command `ls -la`.

Example:
$ ./8-cwd_state
$ cat ls_cwd_content
<output of ls -la>


### Task 9: Duplicate last line

Write a script that duplicates the last line of the file `iacta`.

Example:
$ ./9-duplicate_last_line
$ cat iacta
First line
Second line
Third line
Fourth line
Fifth line
Sixth line
Seventh line
Eighth line
Ninth line
Ninth line
Tenth line


### Task 10: No more javascript

Write a script that deletes all the regular files (not the directories) with a `.js` extension in the current directory and its subfolders.

Example:
$ ls
0-hello_world 1-confused_smiley 2-hellofile 3-twofiles 4-lastlines 5-firstlines 6-third_line 7-file_name 8-cwd_state 9-duplicate_last_line 10-no_more_js
$ find . -type f
./file.js
./subfolder1/file.js
./subfolder2/file.txt
$ ./10-no_more_js
$ ls
0-hello_world 1-confused_smiley 2-hellofile 3-twofiles 4-lastlines 5-firstlines 6-third_line 7-file_name 8-cwd_state 9-duplicate_last_line


### Task 11: Don't just count your directories, make your directories count

Write a script that counts the number of directories and sub-directories in the current directory (including hidden ones).

Example:
$ ./11-directories
4


### Task 12: What’s new

Create a script that displays the 10 newest files in the current directory.

Example:
$ ./12-newest_files
file_1
file_2
file_3
file_4
file_5
file_6
file_7
file_8
file_9
file_10


## Extra Challenges

These challenges are optional and can be attempted after completing all the main tasks. They offer additional opportunities to deepen your understanding and skills.

### Challenge 13: Being unique is better than being perfect

Write a script that takes a list of words as input and prints only words that appear exactly once.

Example:
$ echo "hello bye bye hello hi hi" | ./13-unique
bye


### Challenge 14: It must be in that file

Write a script that displays lines containing the pattern "root" from the file `/etc/passwd`.

Example:
$ ./14-find_pattern_root
root:x:0:0:root:/root:/bin/bash
operator:x:11:0:operator:/root:/sbin/nologin


### Challenge 15: Count that word

Write a script that displays the number of times the word "bin" appears in the file `/etc/passwd`.

Example:
$ ./15-count_bin
15


## Conclusion

Congratulations on completing the Shell, I/O Redirections, and Filters project! This project has provided you with hands-on experience in shell scripting and introduced you to various commands and concepts related to I/O redirections and filters. You have written scripts to perform different tasks, such as printing messages, manipulating file content, and filtering data.

Feel free to explore more about shell scripting and continue practicing to further enhance your skills. Good luck with your future endeavors!

