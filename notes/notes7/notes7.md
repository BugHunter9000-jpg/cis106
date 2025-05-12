# Chapter 7 Notes 

## Definitions 

`cat` - The cat comand is used for displaying the content of a file. 

`tac` - The tac command is used for displaying the content of a file in reverse order. 

`head` - displays the top N number of lines of a given file. By default, it prints the first 10 lines. 

`tail` - displays the last N number of lines of a given file, it prints the last 10 lines. 

`cut` - is used to extraact a specific section of each line of a file and display it to the screen. 

`sort` is used for sorting files. The sort command supports sorting letters in reverse order, by number, and by month. 

`wc` - is used for printing the number of lines, character and bytes in a file.

`tr` - is used for translating or deleting characters from standard output.

`grep` - is used to search text in given file, grep works line by line basis. 

## Usage 

`Usage` - `cat`+`option`+`file(s) to display` 

`Usage` - `tac`+`option`+`file(s) to display` 

`Usage` - `head`+`option`+`file(s)` 


`Usage` -`tail`+`option`+`file` 

`Usage` `cut`+`option`+`files` 

`Usage` `sort`+`option`+`file` 

`Usage` `wc`+`option`+`files` 

`Usage` `Standard output|tr + option + set + set` 

`Usage` `grep`+`option`+`search criteria`+`files` 

Examples `grep 'dracula' ~/Documents/dracula.txt` `grep -v 'war' ~/Documents/books/war-and-peace.txt` `grep -c dracula ~/Documents/Books/dracula.txt`

## Examples 

Examples of cat
* `cat todo.lst` 
* `cat ~/Documents/todo/.lst`
* `cat -n ~/Documents/todo.lst`

Examples of tac 
* `tac todo.md` 
* `tac ~/Documents/totd.md` 

Examples of head 
* `head ~/Documents/book/dracula.txt`
* `head -5 ~/Documents/Books/dracula.txt` 
* `head -n 1 *.csv *.py`

examples of tail 
* `tail ~/Documents/Book/dracula.txt`
* `tail -5 ~/Documents/Book/Dracula.txt` 
* `tail -n 1 *.csv *.py`

Examples of cut 
* `cut -d ':' -f1 /etc/passwd` 
* `cut -d ':' -f1,7 /etc/passwd`
* `cut -b 1-5 usernames.txt`

Examples of sort 
* `sort users.lst` 
* `sort -r user.txt` 
* `sort -n phones.txt`

Examples of wc 
* `wc -m users.txt`
* `wc -l users.txt`
* `wc -w users.txt`

examples of cat 
* `cat file.txt|tr '.'','` 
* `cat program.py|tr "[:space:]" '|t'`

Examples of grep 
* `grep 'dracula' ~/Documents/dracula.txt`
* `grep -v 'war' ~/Documents/books/war-and-peace.txt` 
* `grep -c dracula ~/Documents/Books/dracula.txt`