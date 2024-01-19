
# Jumping Rabbit with infinite animation 


This game is written in Assemebly Nasm (0x8088) With infinite Background Animation .


The screen is Divided into three partition  (First two portion are for some background) And in the third portion we have  implemented the main game 


## Getting started 

To Run this Game you have the following things install in you system 
     
Follow this link to get started:

           https://github.com/ASD0x41/Assembly-Programming-Package 

If above link doesn’t work for you then follow this: 
Suggested version of NASM (you will need to install this in coming instructions): 

           https://www.nasm.us/pub/nasm/releasebuilds/2.15.05/
Option 3:
Make a separate folder COAL and NASM in your machine for example “D:\COAL\NASM.

Visit the link given below. Download and install NASM, AFD and DOSBOX, according to the instructions, in your NASM folder.

            http://wetolearn.blogspot.com/2013/09/setting-up-afd-nasm-and-dosbox-for-8086.html

After installations double click “DOSBox 0.74-2 Options.bat” file and at the end of the file paste following lines:

            MOUNT C D://COAL//NASM
            C:

(We are mounting C drive to our folder where we have saved AFD and we will save our .asm file in this directory)


Now Create a file and Save it in your NASM folder e.g. “D:\COAL\NASM”:

After that Go to NASM installation directory ( e.g. “D:\COAL\NASM”). Double click nasmpath.bat (batch file) and type following command there. (Your .asm file and nasm should be in one folder)

            nasm yourfilename.asm -o yourfilename.com -l yourfilename.lst

Now Open DOSBox (by double clicking dosbox.exe) And run your file 
## Happy learning.....
