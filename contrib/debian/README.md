
Debian
====================
This directory contains files used to package hengad/henga-qt
for Debian-based Linux systems. If you compile hengad/henga-qt yourself, there are some useful files here.

## henga: URI support ##


henga-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install henga-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hengaqt binary to `/usr/bin`
and the `../../share/pixmaps/henga128.png` to `/usr/share/pixmaps`

henga-qt.protocol (KDE)

