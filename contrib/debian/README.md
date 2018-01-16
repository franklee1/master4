
Debian
====================
This directory contains files used to package masterd/master-qt
for Debian-based Linux systems. If you compile masterd/master-qt yourself, there are some useful files here.

## master: URI support ##


master-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install master-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your master-qt binary to `/usr/bin`
and the `../../share/pixmaps/master128.png` to `/usr/share/pixmaps`

master-qt.protocol (KDE)

