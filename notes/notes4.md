# Notes 2: The Linux FS 

* Presentation [https://docs.google.com/presentation/d/e/2PACX-1vRzi-pHAUV4x_mqsbAiiAwTtIGZcXMauEIOUfiBySC4sPr0gszaQmebawSQaj0r2gCIv4r2Dam-fgT4/pub?start=false&loop=false&delayms=3000#slide=id.g1895a62f903_0_6]
*  Article [https://cis106.com/extra/thelinuxfs/]

### Each Command for Navigating the File System 

* pwd command `pwd` - used for displaying the current working directory
* cd command `cd` - used for changing the current working 
  directory. 
  * example `cd ~/Downloads` `cd /home/$USER/Documents` `cd ../` 
* ls command `ls` - used for cdisplaying all the files inside a given directory 
  * Example `ls -a` `ls -a ~Pictures` `ls -t ~/Documents` `la -r ~/Documents`
  
  
### Define the following terms 

    File system -The way files are stored and organized
  
    pathname - Indicated the location of the file in the filesystem (like an address).

    Absolute path - The location of a file starting a root of the file system.

    Relative path - The location of a file starting from the current working directory or a directory that is located inside the current working directory. 

    The difference betwwen your home directory and the home directory - My home directory is my own personal directory where all my files are located. A home directory is the parent directory where all the users home directory are. 

    Parent directory- A directory containing one or more directories and files 
  
    Child directory - Is a directory inside another directory 

    Bash special characters

    * `$USER` - stores the current's user username
    * `$HOME` - stores the absolute path of the current user home directory 
    * `$PWD` - stores the absolute path of the present working directory 
    * `$OLDPWD` - stores the absolute path of the previous current working direcotry. 

    environment variables - stores vaules of a user's environment and can be used in commands in the shell 

    user defined variables - A variable is a place to store data, its like a box with a label. For example, if you have a lot of pens in your desk and you place them in a box a label it pens, now the box stores your pens. 

    Why do we need use $ with variables in bash shell scripting? - We need to use it to be able to access the value stored in a variable 
