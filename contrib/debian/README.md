
Debian
====================
This directory contains files used to package chtcd/chtc-qt
for Debian-based Linux systems. If you compile chtcd/chtc-qt yourself, there are some useful files here.

## chtc: URI support ##


chtc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install chtc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your chtc-qt binary to `/usr/bin`
and the `../../share/pixmaps/chtc128.png` to `/usr/share/pixmaps`

chtc-qt.protocol (KDE)

