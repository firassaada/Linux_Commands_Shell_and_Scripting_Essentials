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
 * apt    : Stands for "Advanced Package Tool" designed to simplify the process of installing,updating and managing software packages
 * base64 : Base64 is a binary-to-text encoding scheme that is used to encode binary/text data, such as images, audio, or other binary files, into a plain text format.
 * base64 -d: This would decode the encoded string back to the original type of data 
 * Bc     : Calculator 
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
 * grep   : It allows you to search files for characters that match a certain pattern
 * grep -i: It allows you to search with the case insensitive property
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
 * Openssl enc : Chiffrement des fichiers
 * Openssl enc -d : Dechiffrement des fichiers 
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
 * ssh    : The primary use of ssh is for remote login to a server or a computer. You can log in to a remote machine and have access to the command-line interface as     if  you were physically present at that machine.
 *strings : It is used to extract human-readable text strings from binary files.
 * sudo   : used to run a single command with root privileges,  
 * sudo -i: simulates a full login, changes the environment to that of the root user, and starts a new shell session.
 * sudo su: only switches the user to root without simulating a full login. It preserves your current environment.
 * su
 * su -c
 * tail   : it will show you the last 10 lines in a file.
 * tail -n: it specifies the nbr of lines to show
 * tail -f: you can see everything that is getting added to that file.(ex : tail -f syslog )
 * tee    : It reads from the input and write to both standard output and one or more files simultaneously ($ ls | tee peanuts.txt)
 * touch  : Creates  files
 * tr     : It allows you to translate a set of characters into another set of characters. 
 * tree   : It displays the hierarchical structure of directories and files in a tree-like format. 
 * uname -a: All details about ur linux kernel
 * uniq   : It removes duplicate lines that are ADJACENT in a file
 * uniq -c: Shows the number of duplications 
 * uniq -d: Shows duplicated attributes
 * uniq -u: Shows unique attributes
 * vi     :  File editor
 * wc     : counts the nbr of lines ,words and bytes in a file
 * whatis : tells you what a command does
 * Zip -r : Creates a zip file(ex: zip -r newzip.zip dir_to_be_zipped)  

 
 
 Symbols  :
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
 
*Vim editor : 
 \      : find the word in the file(ex \pretty looks for pretty)
 ?      : finde the last apparition of the word
  Vim appending text :
 i - insert text before the cursor
 O - insert text on the previous line
 o - insert text on the next line
 a - append text after the cursor
 A - append text at the end of the line
  Vim editing :
 x - used to cut the selected text also used for deleting characters
 dd - used to delete the current line
 y - yank or copy whatever is selected
 yy - yank or copy the current line
 p - paste the copied text before the cursor

 *User Mangement :
 /etc/passwd  : This file shows you a list of users and detailed information about them. 
     root:x:0:0:root:/root:/bin/bash
     1-Username
     2-User's password - the password is not really stored in this file,it's usually stored in the /etc/shadow file. We'll discuss more in the next lesson about /etc/shadow      shadow, but for now, know that it contains encrypted user passwords. You can see many different symbols that are in this field, if you see an "x" that means the             password is stored in the /etc/shadow file, a "*" means the user doesn't have login access and if there is a blank field that means the user doesn't have a password.
     3-The user ID - as you can see root has the UID of 0
     4-The group ID
     5-GECOS field - This is used to generally leave comments about the user or account such as their real name or phone number, it is comma delimited.
     6-User's home directory
     7-User's shell - you'll probably see a lot of user's defaulting to bash for their shell
     
 /etc/shadow  : The /etc/shadow file is used to store information about user authentication. It requires superuser read permissions. (info about pwds)
     root:MyEPTEa$6Nonsense:15000:0:99999:7:::
     1-Username
     2-Encrypted password
     3-Date of last password changed - expressed as the number of days since Jan 1, 1970. If there is a 0 that means the user should change their password the next time    
     they login
     4-Minimum password age - Days that a user will have to wait before being able to change their password again
     5-Maximum password age - Maximum number of days before a user has to change their password
     6-Password warning period - Number of days before a password is going to expire
     7-Password inactivity period - Number of days after a password has expired to allow login with their password
     8-Account expiration date - date that user will not be able to login
     9-Reserved field for future use

 /etc/group  : This file is  for different groups with different permissions. 
     root:*:0:pete
     1-Group name
     2-Group password - there isn't a need to set a group password, using an elevated privilege like sudo is standard. A "*" will be put in place as the default value.
     3-Group ID (GID)
     4-List of users - you can manually specify users you want in a specific group



Openssl :
openssl -enc <alg>  < f.txt  > f.enc      : encrypter f.txt dans f.enc
openssl -enc <alg>  < f.enc  -d > f.txt   : decrypter f.enc dans f.txt
openssl genrsa > cle 4092                 : generating private rsa key in 'cle'
openssl rsa -pubout < cle > cle.pub       : generating pub rsa key in 'cle.pub'
openssl rsa < cle -des3- > cle            : Add a pswd to access the keys
openssl pkeyutl -encrypt -pubin -inkey cle.pub < fichier.txt > fichier.enc : encrypter fichier.txt avec le pub key created
openssl pkeyutl -decrypt -inkey cle < fichier.enc >  fichier.txt           : Decrypter .......
openssl pkeyutl –sign –inkey cle < fichier.txt > fichier.sign              : Signer le fichier.txt avec le cle privée 
openssl pkeyutl –verify –pubin –inkey cle.pub < fichier.txt –sigfile fichier.sign : Verifier la signature du fichier avec la cle publique


