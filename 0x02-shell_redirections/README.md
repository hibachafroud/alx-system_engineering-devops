# Shell, I/O Redirections and filters


The files listed down bellow are scripts done during **Software Engineering** course with **ALX Africa**. 

They aim to learn how to use `head`, `tail`, `find`, `wc`, `sort` , `uniq`, `grep` , `echo` , `cat` , `cut` , and `tr` commands to redirect standard input and output and combine commands using `|` in the Shell.

## Technologies
* Scripts written in Bash
* Tested on Ubuntu 20.04 LTS

## Files

| Filename | Description |
| -------- | ----------- |
| [0-hello_world](./0-hello_world) |  Print the message `Hello, World`. |
| [1-confused_smiley](./1-confused_smiley) | Display a confused smiley `"(Ôo)'`. |
| [2-hellofile](./2-hellofile) | Display the content of the `/etc/passwd` file. |
| [3-twofiles](./3-twofiles) | Display the content of `/etc/passwd` and `/etc/hosts`. |
| [4-lastlines](./4-lastlines) | Display the last 10 lines of `/etc/passwd`. |
| [5-firstlines](./5-firstlines) | Display the first 10 lines of `/etc/passwd`. |
| [6-third_line](./6-third_line) | Display the third line of the file `iacta`. |
| [7-file](./7-file) | Create a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School`. |
| [8-cwd_state](./8-cwd_state) | Write into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it. |
| [9-duplicate_last_line](./9-duplicate_last_line) | Duplicate the last line of the file `iacta`. |
| [10-no_more_js](./10-no_more_js) | Deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders. |
| [11-directories](./11-directories) | Count the number of directories and sub-directories in the current directory. The current and parent directories should not be taken into account and the hidden directories should be counted. |
| [12-newest_files](./12-newest_files) | Displays the 10 newest files in the current directory ;one file per line ,sorted from the newest to the oldest. |
| [13-unique](./13-unique) | takes a list of words as input(input format: one line, one word) and prints(output format: one line, one word) only words that appear exactly once, words should be sorted. |
| [14-findthatword](./14-findthatword) | Display lines containing the pattern “root” from the file `/etc/passwd`. |
| [15-countthatword](./15-countthatword) | Display the number of lines that contain the pattern “bin” in the file `/etc/passwd`. |
| [16-whatsnext](./16-whatsnext) | Display lines containing the pattern “root” and 3 lines after them in the file `/etc/passwd`. |
| [17-hidethisword](./17-hidethisword) | Display all the lines in the file `/etc/passwd` that do not contain the pattern “bin”. |
| [18-letteronly](./18-letteronly) | Display all lines of the file `/etc/ssh/sshd_config` starting with a letter. |
| [19-AZ](./19-AZ) | Replace all characters A and c from input to Z and e respectively. |
| [20-hiago](./20-hiago) | Remove all letters c and C from input. |
| [21-reverse](./21-reverse) |  Reverse its input. |
| [22-users_and_homes](./22-users_and_homes) | Display all users and their home directories, sorted by users. |
| [100-empty_casks](./100-empty_casks) | Find all empty files and directories in the current directory and all sub-directories. Only the names of the files and directories should be displayed (not the entire path). Hidden files should be listed. One file name per line. |
| [101-gifs](./101-gifs) |  List all the files with a `.gif` extension in the current directory and all its sub-directories.Hidden files should be listed. Only regular files (not directories) should be listed, the names of the files should be displayed without their extensions, the files should be sorted by byte values but case-insensitive (file `aaa` should be listed before file `bbb`, file `.b` should be listed before file `a`, and file `Rona` should be listed after file `jay`) and one file name per line. |
| [102-acrostic](./102-acrostic) | Decode acrostics that use the first letter of each line. |
| [103-the_biggest_fan](./103-the_biggest_fan) | Parse web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.Ordered by number of requests, most active host or IP at the top. |
