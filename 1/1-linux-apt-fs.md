##System administrating.

###APT Advanced Packaging Tool    

It is perfoming such function as:

- installation of new software
- removing software
- upgrade and update of existing software
- updating of the package list index
- upgrating entire Ubuntu system


1. Install a Package

    sudo apt-get install mc

*sudo* - because we need the right to create/update files in system directories
*apt-get* - Advanced Packaging Tool command
*install* - what we wana do
*mc* - name of the software <package-name>


2. Remove a package

    sudo apt-get remove <package-name>
    sudo apt-get purge <package-name>

*remove* - does not include configuration files

3. Updating Package Index.

The APT package index is essentially a database of available packages from the repositories defined in the /etc/apt/sources.list file and in the /etc/apt/sources.list.d directory.

    sudo apt-get update

This command updates your package index with last changes made in the repositories.

To see your list of packages you can run this command

    nano /etc/apt/sources.list

4. Upgrade Packages

    sudo apt-get upgrade


*apt-get update* - updates the list of available packages and their versions, but it does not install or upgrade any packages.

*apt-get upgrade* - actually installs newer versions of the packages you have.



 The fist thing what you are going to do after Ubuntu instalation is updating your repository by *apt-get update* command.
After that you can install new software as well as upgrate them because now manager knows about available packages.

###Usefull comand to manipulate file system

*pwd* - current directory;

*ls* - list of the content in the current diectory;

    ls -l

To show detail list

*cd* - change directory

###Create a new directory

    mkdir <dirname>

###Create an empty file

    touch <filename>

###Print out someting

    echo 'Hi'
    echo $PATH

###Write a string to file

    echo 'hello' > <filename>
    echo 'hello' >> <filename>

###Print out the content of the file

    cat <filename>

###Print out the content of the file dinamicaly

    tail -n 20 -f <path-to-file>


###Edit file with nano

    nano <path-to-file>

##Copy files

    cp <source> <destination>

##Remove files

    rm <path-to-file>







