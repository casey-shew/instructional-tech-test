There are two important commands for using the Terminal: `ls` and `cd`.  

The `ls` command lists the files in the active directory (the directory the Terminal is currently showing). If you add the optional ` -l` after the command, you will see the file sizes and dates they were last modified. 

The `cd` command is used to move to a new directory. To use the command, type the name of the folder after the command. But you can only move to a folder if is visible from the active directory. So you can move from the starting directory to `folder1`, but you cannot move from `folder1` to `folder2`.  Instead, you will first need to back out of `folder1` with the command:
    
    cd ..

![Navigation](.guides/img/navigate.png "Navigating Folders")
