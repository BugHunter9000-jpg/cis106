# Notes 5 


### Mkdir - is used for creating a single directory or multiple directories 

#### Usage `mkdir` + `option` + `name of directories`

#### Examples 
* Creat multiple directories 
  * (`mkdir`+`wallpapers/cars`+`wallpapers/cities`+`wallpapers/forest`)
* Creat a directory in a different directory using relative path
  * (`mkdir`+`wallpapers/ocean`)
* Create a directory in the presnt working directory 
  * (`mkdir wallpaper`)


### Touch - Is used for creating files 

#### Usage - `touch` + `name of the file`

#### Examples 
* To create a file called list 
  * (`touch` + `List`)
* To create serveral files 
  * (`touch list_of_cars.txt script.py names.csv`)
* To create a file using absolute path 
  * (`touch ~/Downloads/games.txt`)
 
### Rm - Is used to remove files

#### Usage `rm` +`-r`

#### Example 
* To remove a file 
  * (`rm list`)
* Remove a file and prompt confirmation before removal 
  * (`rm -i list`)
* Remove an empty directory 
  * (`rmdir Downloads/games`)

### Rmdir - is used to remove empty directories 

#### Usage - `rmdir` + `the empty directory`

#### Example - (`rmdir Donloads/games`)

### Mv - moves and renames directories

#### Usage - `mv` + `source` + `destination`

#### Example 
* For renaming files/ directories 
  * (`mv` + `file/directory to rename` + `new name`)
* To move a directory from one directory to another using absolute path and relative path 
  * (`sudo mv ~/Downloads/theme /usr/share/themes`)
* To move multiple directories/files to a different directory 
  * (`mv games/ wallpapers/ rockmusic/ /meida/student/flashdrive/`)

### CP - copies files/directories from a source to a destination

#### Usage - `cp` + `files to copy` + `destination` 

#### Example 
* To copy a file (`cp Downloads/wallpapers.zip Pictures/`)
* To copy a directory with absolute path (`cp -r ~/Downloads/wallpapers ~/Pictures/`)
* To copy multiple files in a single command (`sudo cp -r script.sh program.py home.html assets/ /var/www/html/`)

#### File - Determines the file type of a file

#### Usage - `file` + `filename`

#### Example 
* Display file type without file name 
  * (`file -b filename`)
* Display file name 
  * (` file filename`)
