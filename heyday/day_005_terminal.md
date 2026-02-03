today topic
    1.Basic Linux Commands
    2.User and Privileges


basic Linux commands

sudo - means super user do
cat - short for concatenate, and it's a command used to read, display
pwd - print working directory
cd - change directory
ls - list
mv - move
man - manual 
cp sample.txt downloads/   -  to copy paste the file
rm sample.txt   - to remove file
locate base - this search the file of base

implementing

cd ..   - to go previous directory
cd /downloads  - to move next directory
ls -la   -  it show the hidden folders


user and privileges

----permission code----

example

┌──(kali㉿kali)-[~]
└─$ ls -la      
total 340
drwx------ 21 kali kali   4096 Jan 22 11:47 .
drwxr-xr-x  3 root root   4096 Sep  9 06:19 ..
-rw-r--r--  1 kali kali    220 Sep  9 06:19 .bash_logout


d - directory
r - read
w - write
x - execute
                drwx     r -x     r-x
                  ^        ^       ^            
                  |        |       |         
# it has 3 group   owner   group    other    
# Owner: Can create, delete, or modify files within this directory.
# Group/Others: Can enter the directory (x) and list its contents (r), but cannot create or delete files (w)

passwd - to change password

add user by
Example
--> $ adduser john
--> $ cat /etc/passwd - to comform it exist
--> $ su john - to switch user
--> $ sudo password john - to change password

