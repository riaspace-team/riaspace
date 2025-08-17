
Debian
====================
This directory contains files used to package riaspaced/riaspace-qt
for Debian-based Linux systems. If you compile riaspaced/riaspace-qt yourself, there are some useful files here.

## riaspace: URI support ##


riaspace-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install riaspace-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your riaspace-qt binary to `/usr/bin`
and the `../../share/pixmaps/riaspace128.png` to `/usr/share/pixmaps`

riaspace-qt.protocol (KDE)

