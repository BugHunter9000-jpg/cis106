# Notes 8 for Chapter 8 

## Defenition 
`awk`- is a scripting language used for processing and displaying text. Awk can work with a text file or form standard output. There are several implementations of Awk: nawk, mawk, gawk, and bsuybox. Awk performs operations line by line. 

`sed` - is a stream editor that perform operations on standard output. It can search, find, replace, insert, and delete. Using `sed` you can edit files without opening them

`less` - is used to show a files contents one screen at a time.

`>` - when we use `>` on a file it is used for identifying open files on a given session using positive intergers. 

`>>` - this command append the content of the file instead of displaying it on the screen 

`|` - the pipe allows you to redirect the standard output of a command to the standard input of another. 

## Usage 

For `awk` - `awk + options + {awk command} + file + file to save`

`Sed` - `sed options + sed script + file`

`>` - `command output + > + file`

`|` - `command_1 | command_2 | command_3 | .... | command_N`


## Examples of Awk

`awk '{print $1}' ~/Documents/Csv/cars.csv`
`awk -F: '{print $1}' /etc/passwd`
`awk -F: '{print $NF}' /etc/passwd`

## Examples of `sed` 

` sed 's/pizza/rice/' shopping-list.lst`
` sed '3 s/pizza/rice/' shopping-list.lst`
` sed '1,3 s/pizza/rice/' shopping-list.lst` 

## Examples of `>` 

`ls -lA ~ > all-files-in-home.txt`
`ls -lA downloads/ 2> /dev/null`
`ls -lA downloads/ 2> error-of-ls`

## Examples of `|` 

`man ls | grep "human-readable"`
`man ls | grep "^[[:space:]]*[[:punct:]]"`
`head -2 file.lst | tail -1`

## Example of `less` 

`less ~/Documents/Books/dracula.txt`