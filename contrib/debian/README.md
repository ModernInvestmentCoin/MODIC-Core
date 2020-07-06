
Debian
====================
This directory contains files used to package modicd/modic-qt
for Debian-based Linux systems. If you compile modicd/modic-qt yourself, there are some useful files here.

## modic: URI support ##


modic-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install modic-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your modicqt binary to `/usr/bin`
and the `../../share/pixmaps/modic128.png` to `/usr/share/pixmaps`

modic-qt.protocol (KDE)

