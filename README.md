# OSP7
This is the repo for the csn232 OSP.

# ParallelDE
One usually can run only one DE ( Desktop Environment at a time)
To change the DE one has to install its required files and logout and then login again to change the DE for a different desktop experience.

This push explains how to use them in parallel and switch between them instantly.
Linux allows multi-user interface from TTY 1 to 7.
We by default are in 7.

What we need to do is download the respective DEs and create an .xinitrc executable for home directory to configure startx command to initiate a different DE session.

Then simply initiate another tty and run startx.

Switching between them simply by Ctrl+Alt+i (i can be 1 to 6) and Ctrl+Alt+7.
