# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > 1) pwd : This shows the current working directory path.
    2) mkdir: This creates a directory.
    3) rm -r: This deletes a directory.
    4) touch: This creates a file.
    5) rm: This deletes a file.
    6) mv: This moves files around, but can be used to rename files.
    7) ls -a: This lists all files in a directory, hidden or otherwise.
    8) cp: This copies a file from the working directory to another directory.
    9) sort: This sorts lines of text alphabetically.
    10) grep: This searches for a text pattern and outputs it.
    11) sed: This searches for a text pattern, modifies it, and outputs it.

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > ls: This lists the files in the working directory.
    ls -a: This lists the files in the working directory, including hidden ones.
    ls -l: This lists the files in the working directory in long format.
    ls -lh: This lists the files in the working directory in long format with readable file size
    ls -lah: This lists the files in the working directory in long format with readable file size, including hidden files.
    ls -t: This lists the files in the working directory sorted by time and date.
    ls -Glp: This lists the files in the working directory in long format, without group names, with "/" appended to directories
---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 1) ls -F: Flags filenames
    2) ls -d: Displays only directories
    3) ls -x: Displays files as rows across the screen
    4) ls -m: Displays names as a comma-separated list
    5) ls -1: Displays each entry on a line

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs takes input from the standard input and executes a given command a number of times based on the input. The default command is echo. For example, if you wanted to find all the text files in the current directory (and any sub directories) you could input:
$ xargs find -name
"*.txt"
The terminal would then output all text files in the current directory and any sub directories.

 

