                        Copyright (c) 1988 Bellcore
                            All Rights Reserved
       Permission is granted to copy or use this program, EXCEPT that it
       may not be sold for profit, the copyright notice must be reproduced
       on copies, and credit should be given to Bellcore where it is due.
       BELLCORE MAKES NO WARRANTY AND ACCEPTS NO LIABILITY FOR THIS PROGRAM.

Fork of Bell MGR windowing system which builds on Debian 11.11 and uses X11 Xlib as display output.

APT packages installed prior to build:
"build-essential"
"git"
"m4"
"libx11-dev"
"xorg"
"twm" (as debian system window manager)

Edit Configfile and replace USERNAME with your home path.

Then from within /mgr/
"make first",
"make depend",
"make install".

startx to get into the debian system window manager and run /mgr/bin/./mgr

MGR runs in an X window.
