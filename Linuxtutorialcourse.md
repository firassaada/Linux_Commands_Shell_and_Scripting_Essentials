Linux tutorial course : https://olympus.mygreatlearning.com/courses/52823 
file:///C:/Users/MSI/Downloads/Linux+Tutorial.pdf

What is linux ?
Linux is an open source  kernel . It is highly flexible ,lightweighted,highly configurable and has fewer malware .
Kernel : 
The kernel is like the brain of the operating system—it's the core component responsible for managing system resources and providing a bridge between software and hardware.
Linux Architecture : 
Hardware ->Linux Kernel ->Shell(Interacitve layer for users) ->Apps
Linux Components :
Schedulers / File System / Security / Network / Drivers
Linux basic concepts :
-The packet manager downloads,installs and desinstalls apps on linux .
-U can monitor processes

Linux commands :
 *apt     : Stands for "Advanced Package Tool" designed to simplify the process of installing,updating and managing software packages
 *Bc      : Calculator 
 * Cat    : Print file content
 * cp     : Copying a file
 * cp -i  : Check if a file/directory could be overwritten 
 * cp -r  : Copying a directory
 * curl   : it is a command-line tool and library for making HTTP requests. It stands for "Client for URLs" or "cURL."
 * cut    : It extracts portions of text from a file. 
 * cut -c : To extract contents by a list of characters
 * cut -f : The -f or field flag cuts text based off of fields, by default it uses TABs as delimiters
 * cut -f -d : U specify delimeters (ex -d ';')
 * echo
 * file   : Show the type of the file
 * find   : Search file/directory in a directory (find 'name of dir' -name 'name of file/dir')
 * grep   : It grep allows you to search files for characters that match a certain pattern 
 * join   : It allows you to join multiple files together in one file  by a common field
 * head   : the head command will show you the first 10 lines in a file.
 * head -n : it specifies the nbr of lines to show 
 * history: shows all command u typedfilefile bana from the start
 * less   : Shows you large files
 * ls
 * ls -a  : all files
 * ls -l  : ordered detailed  files
 * ls -al : all files ordered
 * man    : Gives u all info about a command 
 * mkdir
 * mkdir -p : Creating directories with subdirectories (mkdir nnn/lll/..)
 * mv     : moves file to a directory / rename files/Directories
 * nano   :   File editor
 * nl     : enumerates the lines in a file
 * paste -s : It merges the lines of a file into one line(with TAB delimeter)
 * paste -s -d : Yopu specify the delimeter(Ex : -d ' ')
 * pwd    : it outputs the current directory or the path of the directory you are currently in.
 * rm     :   Remove a file
 * rm -r  : Remove a directory 
 * rm -f  :  Force remove
 * rmdir  : Remove directories
 * sort   :  It sort lines/files/dirs.. by alpha order(num then alpha 2 3 a b ..)
 * sort -r: reverse sorting
 * sort -n: alpha then num(a b 1 2 ...)
 * ssh    : The primary use of ssh is for remote login to a server or a computer. You can log in to a remote machine and have access to the command-line interface as     if you were physically present at that machine.
 * sudo -i: simulates a full login, changes the environment to that of the root user, and starts a new shell session.
 * sudo su: only switches the user to root without simulating a full login. It preserves your current environment.
 * tail   : it will show you the last 10 lines in a file.
 * tail -n: it specifies the nbr of lines to show
 * tail -f: you can see everything that is getting added to that file.(ex : tail -f syslog )
 * tee    : It reads from the input and write to both standard output and one or more files simultaneously ($ ls | tee peanuts.txt)
 * touch  : Creates  files
 * tree   : It displays the hierarchical structure of directories and files in a tree-like format. 
 * vi     :  File editor
 * uname -a: All details about ur linux kernel
 * wc     : counts the nbr of lines ,words and bytes in a file
 * whatis : tells you what a command does

 
 
 Text-Fu :
 ^      : Specifies beginng of a line
 $      : Specifies the end of a line
[]      : Specifies a character (Ex grep j[a-n][h]n f2 : taatik john)
 >      :  $ echo Hello World  peanuts.txt 
 >>     :  $ echo Hello World >> peanuts.txt 
 <  >   :  $ cat < peanuts.txt > banana.txt     $ ls < peanuts.txt > banana.txt
 2>     :  $ ls peanuts.txt 2> banana.txt : writes only stderr result to the file
 1>     :  $ ls peanuts.txt 1> banana.txt : writes only stdout result to the file
 2>&1   :  $ ls /fake/directory > peanuts.txt 2>&1 : wirtes both stderr and stdout in the file
 |      :  The pipe operator |, represented by a vertical bar, allows us to get the stdout of a command and make that the stdin to another process.$ ls -la /etc | less 
  
  
