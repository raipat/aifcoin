
Debian
====================
This directory contains files used to package aifd/aif-qt
for Debian-based Linux systems. If you compile aifd/aif-qt yourself, there are some useful files here.

## aif: URI support ##


aif-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install aif-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aif-qt binary to `/usr/bin`
and the `../../share/pixmaps/aif128.png` to `/usr/share/pixmaps`

aif-qt.protocol (KDE)

