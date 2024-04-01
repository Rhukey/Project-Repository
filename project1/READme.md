# `sudo apt upgrade`

## sudo apt upgrade is a command-line utility for installing, updating, removing, and otherwise managing deb packages on Ubuntu, Debian, and related Linux distributions. It combines the most frequently used commands from the apt-get and apt-cache tools with different default values of some options.

![alt text](<Images/Sudo apt update.png>)





# `pwd`

 ## "pwd" simply means print working directory, it allows one view the current directory.  It prints the path of the working directory, starting from the root. pwd is shell built-in command(pwd) or an actual binary(/bin/pwd). $PWD is an environment variable that stores the path of the current directory

![alt text](Images/pwd.png)




# `cd`

## The cd (“change directory”) command is used to change the current working directory in Linux and other Unix-like operating systems. It is one of the most basic and frequently used commands when working on the Linux terminal. The current working directory is the directory (folder) in which the user is currently working in. Each time you interact with your command prompt, you are working within a directory. In order to execute the command in the scrrenshot below, i had to create the ubuntu and commandslinux directory first on my ubuntu terminal

![alt text](<Images/cd command.png>)


# `ls`

## The ls command lists files and directories within the file system, and shows detailed information about them. It is a part of the GNU core utilities package which is installed on all Linux distributions. The ls command has a lot of syntax like ls-a, ls-lh, ls-R, ls-ltr etc which all have different functions and meanings.


![alt text](Images/ls-a.png)

![alt text](Images/ls.png)


# `cat`

## The cat command is one of the most widely used commands in Linux. The name of the cat command comes from its functionality to concatenate files. It can read, concatenate, and write file contents to the standard output. If no file is specified or the input file name is specified as a single hyphen (-), it reads from the standard input. Cat is most commonly used to display the contents of one or multiple text files, combine files by appending one file’s contents to the end of another file, and create new files. To run the command in the snapshot we need to create a file name tech4dev.sh on my linux terminal.


![alt text](<Images/cat command.png>)


# `cp`

## The cp is a command-line utility for copying files and directories on Unix and Linux systems.There are different syntax to cp command,we have cp -R, etc.


![alt text](<Images/cp command.png>)



# `mv`

##  The mv command has 2 major function:moving files and renaming files. The mv command (short from move) is used to rename and move and files and directories from one location to another. The syntax for the mv command is as follows: mv [OPTIONS] SOURCE DESTINATION


![alt text](<Images/mv command.png>)


# `mkdir`

## The "mkdir" command is to make directories, To create a directory in Linux, pass the directory’s name as the argument to the mkdir command. For example, to create a new directory newdir, you would run the following command: "mkdir newdir"


![alt text](Images/mkdir.png)

# `rmdir`

## The "rmdir" command is to use delete folders in Linux command line.


![alt text](<Images/rmdir command.png>)


# `rm`


## The "rm" command is used to remove objects such as files, directories, symbolic links and so on from the file system like UNIX. To be more precise, rm removes references to objects from the filesystem, where those objects might have had multiple references (for example, a file with two different names). By default, it does not remove directories. This command normally works silently and you should be very careful while running rm command because once you delete the files then you are not able to recover the contents of file.



![alt text](<Images/rm command.png>)


# `touch`

## The touch command is a standard command used in the UNIX/Linux operating system which is used to create, change and modify the timestamps of a file. This command can be used when the user doesn’t have data to store at the time of file creation.


![alt text](<Images/touch command.png>)

# `locate`

## Locate command in Linux is used to find the files by name. There are two most widely used file-searching utilities accessible to users called to find and locate. The locate utility works better and faster than the find command counterpart because instead of searching the file system when a file search is initiated, it would look through a database. To locate a file, you need to run the command locate "filename". The command wasn't working so i had to run the command "sudo apt install plocate" first 


![alt text](<Images/locate command.png>)


# `find`

## The "find" command in Linux is a dynamic utility designed for comprehensive file and directory searches within a hierarchical structure. Its adaptability allows users to search by name, size, modification time, or content, providing a flexible and potent solution.


![alt text](<Images/find command.png>)



# `grep`

## "grep" is a command-line utility that searches for a specific text string in one or more files. It looks for the pattern in each line of the file and prints out the lines that match it. It is a powerful tool for searching and analyzing large amounts of text data quickly and efficiently


![alt text](<Images/grep command.png>)


# `df`

## The df command is used to get a detailed report on the system’s disk space usage. To display information about disk drives in human-readable format (kilobytes, megabytes, gigabytes and so on), invoke the df command with the -h option


![alt text](<Images/df-h command.png>)


# `du` command 

## du command short for “disk usage” reports the estimated amount of disk space used by given files or directories. It is practically useful for finding files and directories taking up large amounts of disk space.


![alt text](<Images/du command.png>)


# `head`

## "head" command The head command does the opposite of what the tail command does. It shows the starting content of a file, while the tail command prints the ending lines of a file. By default, head displays the first 10 lines. If you want to print more or less than 10 lines, just use the -n option. Similarly, the -c option with the head command can restrict the output to a particular byte number. The head command can analyze logs and other text files that are subject to vary over time. You can use the head command in conjunction with other commands for selective, real-time monitoring.


![alt text](<Images/head command.png>)


# `tail`

## tail command is the complementary of head command. The tail command, as the name implies, prints the last N number of data of the given input. By default, it prints the last 10 lines of the specified files. If more than one file name is provided then data from each file is preceded by its file name.


![alt text](<Images/tail command.png>)

# `diff`

## "diff" command is used to compare files, line by line and it is crucial for identifying differences, debugging code, and ensuring the integrity of data.


![alt text](<Images/diff command.png>)


# `tar`

## tar command stands for tape archive, which is used to create Archive and extract the Archive files. tar command in Linux is one of the important commands that provides archiving functionality in Linux. We can use the Linux tar command to create compressed or uncompressed Archive files and also maintain and modify them.


![alt text](<Images/tar command.png>)



