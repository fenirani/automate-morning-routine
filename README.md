# Automate Morning Routine

Simple program that opens websites that are used on daily basis And which can be started from DASH.

Instructions:

-In the goodmorning.sh, change 'fen' to your user directory:

	#!/usr/bin/env bash
	python3 /home/fen/auto-morning/goodmorning.py
	bash

-Change rights to the file with the following command:

	~$ chmod u+x /home/fen/example.sh
	
(Remember to use your user directory name and not 'fen')

Finally, go home:

	~$ cd ~
	
And then:

	~$ cd .local/share/applications

In here create a file called example.desktop and write in it the following (remember to change fen):

	[Desktop Entry]
	Name=goodmorning.py
	Exec=gnome-terminal -- /home/fen/auto-morning/goodmorning.sh
	Type=Application
	Categories=GTK;GNOME;Utility;

And that's it.
