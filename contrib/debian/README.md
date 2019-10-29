
Debian
====================
This directory contains files used to package naspd/nasp-qt
for Debian-based Linux systems. If you compile naspd/nasp-qt yourself, there are some useful files here.

## nasp: URI support ##


nasp-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nasp-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your naspqt binary to `/usr/bin`
and the `../../share/pixmaps/nasp128.png` to `/usr/share/pixmaps`

nasp-qt.protocol (KDE)

