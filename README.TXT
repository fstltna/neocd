NEOCD/SDL v0.2.0  
================
http://www.geocities.com/neocdsdl
neocdsdl at yahoo dot com

NeoCD/SDL is a port of NeoCD using SDL libraries.
SDL portions written by Fosters(2001,2003).

Original NeoCD(DOS Version) by Martinez Fabrice



About
=====
NeoCD/SDL is a port of the NeoCD emulator for dos to the multiplatform SDL 
library.

It is capable of running many original Neogeo CD games 

It is currently capable of compiling and running on Windows, Linux and BeOS
(BeOS v0.1.8 - see www.beemulated.net)

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.



Note
====
This program requires a system rom (bios) from the original Neogeo CD console to
function.  This code is copyrighted and therefore you are not entitled to a 
copy unless you own an original Neogeo CD console.

Do not enquire where to find this file.  Suffice to say that it should be called
neocd.bin and should be 512kb in size.

A smaller version of this bios file exists on the internet, however this will no
longer work with NeoCD/SDL(v 0.2.0 onwards)




Usage
=====
Unpack all the files from the archive to a directory.  Ensure the neocd bios is 
called "neocd.bin" and add it to the same directory (it should not be compressed
- it will be 512kb in size).

Insert a neogeo cd into one of your cd drives and ensure that it is mounted.

Run the neocd exectuable.

If all goes well NeoCD/SDL should detect the cd drive that the cd is in and run 
the game.

**** When running on windows all textual output from the program goes into 
*NB* stdout.txt instead of to the console.  You should examine this file when 
**** things go wrong.





Controls
========
Player 1 may be controlled using either the keyboard or the first joystick 
attached to the system.

Player 2 may be controlled using the second joystick attached to the system.

The joypad buttons have been allocated to suit my MS sidewinder gamepads.

The controls roughly follow the default layout for the MAME emulator. 
As such they are as follows:

                     Keyboard       Joystick
----------------------------------------------		   
Up                   Cursor-Up      Joy-Up
Down                 Cursor-Down    Joy-Down
Left                 Cursor-Left    Joy-Left
Right                Cursor-Right   Joy-Right

A                    Left-Ctrl      Button-0
B                    Left-Alt       Button-1
C                    Space          Button-2
D                    Left-Shift     Button-3

Player 1 Start       1              Button-8
Player 2 Start       2

Player 1 Select      5              Button-9
Player 2 Select      6

Toggle Fullscreen    F1
Cycle Video Effect   F2
Increase Frameskip   F3
Disable Sound        F4

Quit                 Esc 
----------------------------------------------

The player select buttons can often be used to pause the game.

To modify the controls it is necessary to recompile the software.




Acknowledgements (in no particular order)
=================
Fabrice Martinez    - For the original NeoCD emulator
Caz                 - For the BeOS NeoCD/SDL build

Sam Lantinga et al. - For the amazing libSDL cross-platform C library.

Snes9x 	            - Where I found the 2xSaI code.

The RAINE team      - For getting SEAL audio libraries to build with MINGW.
		      (I think it was you guys anyway.)

The MAME team       - For an incredible emulator, a source tree full of useful
                      information, and for sucking away more of my time than any
		      other computer program in years 8)

Everyone Else       - Thanks for taking an interest.



Enjoy!


Fosters
neocdsdl at yahoo dot com

