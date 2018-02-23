
Debian
====================
This directory contains files used to package capd/cap-qt
for Debian-based Linux systems. If you compile capd/cap-qt yourself, there are some useful files here.

## cap: URI support ##


cap-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cap-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your capqt binary to `/usr/bin`
and the `../../share/pixmaps/cap128.png` to `/usr/share/pixmaps`

cap-qt.protocol (KDE)

