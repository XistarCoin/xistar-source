
Debian
====================
This directory contains files used to package xistard/xistar-qt
for Debian-based Linux systems. If you compile xistard/xistar-qt yourself, there are some useful files here.

## xistar: URI support ##


xistar-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xistar-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xistarqt binary to `/usr/bin`
and the `../../share/pixmaps/xistar128.png` to `/usr/share/pixmaps`

xistar-qt.protocol (KDE)

