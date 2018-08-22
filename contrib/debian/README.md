
Debian
====================
This directory contains files used to package xorxd/xorx-qt
for Debian-based Linux systems. If you compile xorxd/xorx-qt yourself, there are some useful files here.

## xorx: URI support ##


xorx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xorx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xorxqt binary to `/usr/bin`
and the `../../share/pixmaps/xorx128.png` to `/usr/share/pixmaps`

xorx-qt.protocol (KDE)

