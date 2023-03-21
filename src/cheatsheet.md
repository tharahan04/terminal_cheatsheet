# Terminal Cheatsheet 


* `cd` - change directory 
* `ls` - list folders and files
* `ls -l` - list all folders and files
* `mv` - moving files and folders
* `pwd` - print working directory (to see where you are)

**Creating New File/Folders**
* `touch` - touch commands to create new files
* `mkdir` - create new directories/folders

**Opening Files**
* `open my_file.txt` - opens the text editor named file <br>
The **_".txt"_** is the file type.

**Removing Files**
* `rm` - removing files and folders

**Copying Files**
* `cp -r` - copies the whole directory 

**Git Commands**

Once the file that needs to be pushed on to GitHub has been located: <br>
`git init` - initiates a tracker to record all changes in the directory <br>

**then if ANY changes are detected within the file,** <br>

`git add .` - this command allows you to record the changes made 
once it has been recorded, <br>
`git status` - use this command to check the status of the changes before being pushed. <br>
 Then you can use,<br>
`git commit -m"txt"`- to name the changes made and to be saved. <br>

Finally, <br>
`git push` - the initiates the .md/.txt file to be pushed on to GitHub to be viewed online.

``` 
Use `git status` to determine whether the changes have been made and pushed on to GitHub
```
**Extras**

`.gitignore` - this is a command that can be used to ignore a file that has been committed before <br>

