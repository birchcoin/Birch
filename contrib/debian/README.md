
Debian
====================
This directory contains files used to package birchd/birch-qt
for Debian-based Linux systems. If you compile birchd/birch-qt yourself, there are some useful files here.

## birch: URI support ##


birch-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install birch-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your birch-qt binary to `/usr/bin`
and the `../../share/pixmaps/birch128.png` to `/usr/share/pixmaps`

birch-qt.protocol (KDE)

