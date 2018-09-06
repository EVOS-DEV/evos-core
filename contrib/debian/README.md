
Debian
====================
This directory contains files used to package evosd/evos-qt
for Debian-based Linux systems. If you compile evosd/evos-qt yourself, there are some useful files here.

## evos: URI support ##


evos-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install evos-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your evosqt binary to `/usr/bin`
and the `../../share/pixmaps/evos128.png` to `/usr/share/pixmaps`

evos-qt.protocol (KDE)

