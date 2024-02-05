
Debian
====================
This directory contains files used to package APHd/APH-qt
for Debian-based Linux systems. If you compile APHd/APH-qt yourself, there are some useful files here.

## pivx: URI support ##


APH-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install APH-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your APH-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

APH-qt.protocol (KDE)

