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
 * echo
 * file   : Show the type of the file
 * find   : Search file/directory in a directory (find 'name of dir' -name 'name of file/dir')  
 * history: shows all command u typedfilefile bana from the start
 * less   : Shows you large files
 * ls
 * ls -a  : all files
 * ls -l  : ordered files
 * ls -al : all files ordered
 * man    : Gives u all info about a command 
 * mkdir
 * mkdir -p : Creating directories with subdirectories (mkdir nnn/lll/..)
 * mv     : moves file to a directory / rename files/Directories
 * nano   :   File editor
 * PWD    : it outputs the current directory or the path of the directory you are currently in.
 * rm     :   Remove a file
 * rm -r  : Remove a directory 
 * rm -f  :  Force remove
 * rmdir  : Remove directories
 * ssh    : The primary use of ssh is for remote login to a server or a computer. You can log in to a remote machine and have access to the command-line interface as     if you were physically present at that machine.
 * sudo -i: simulates a full login, changes the environment to that of the root user, and starts a new shell session.
 * sudo su: only switches the user to root without simulating a full login. It preserves your current environment.
 * tee    : It reads from the input and write to both standard output and one or more files simultaneously ($ ls | tee peanuts.txt)
 * touch  : Creates  files
 * tree   : It displays the hierarchical structure of directories and files in a tree-like format. 
 * vi     :  File editor
 * uname -a: All details about ur linux kernel
 * whatis : tells you what a command does
 
 
 Text-Fu :
 >      :  $ echo Hello World  peanuts.txt 
 >>     :  $ echo Hello World >> peanuts.txt 
 <  >   :  $ cat < peanuts.txt > banana.txt     $ ls < peanuts.txt > banana.txt
 2>     :  $ ls peanuts.txt 2> banana.txt : writes only stderr result to the file
 1>     :  $ ls peanuts.txt 1> banana.txt : writes only stdout result to the file
 2>&1   :  $ ls /fake/directory > peanuts.txt 2>&1 : wirtes both stderr and stdout in the file
 |      :  The pipe operator |, represented by a vertical bar, allows us to get the stdout of a command and make that the stdin to another process.$ ls -la /etc | less 
  
  
