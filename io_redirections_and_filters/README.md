This directory contains 22 taks. I'm going to give you a little descrition of each one.

0-hello_world
command: echo "Hello, World"
This one is for the print said 'Hello, World'

1-confused_smiley
command: echo '"(Ôo)'\'''
Thats displays a confused smiley.

2-hellofile
command: cat /etc/passwd
This show all the text of that file.

3-twofiles
command: cat etc/passwd /etc/hosts
This show all the text of this two files.

4-lastlines
command: tail /etc/passwd
Shows 10 firt lines of that files.

5-firstlines
command: head /etc/passwd
Shows 10 last lines of the file.

6-third_line
command: head -n 3 iacta | tail -n 1
This command show the third line of the file.

7-file
command:echo "Best School" > '\\\*\\\'"Best School"\'\\\\*\$\?\*\*\*\*\*\:)'
This show the text 'Best School"
8-cwd_state
command: ls -la > ls_cwd_content
Overwritte the file 'ls_cwd_content"

9-duplicate_last_line
command: tail -n 1 iacta >> iacta
This command dublicates the last line of the file.

10-no_more_js
command: find . -type f -name "*.js" -delete
Deletes the files with '.js' extebsion.

11-directories
command: find . -type d ! -name '.' ! -name '..' | wc -l
Counts the numbers of the directories and subdirectories.

12-newest_filters
command: ls -t | head -n 10
Order one file per line and sorted from the newest to the oldest.

13-unique
command: sort | uniq -u
Print files.

14-findthatword
command: