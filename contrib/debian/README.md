
Debian
====================
This directory contains files used to package ulmd/ulm-qt
for Debian-based Linux systems. If you compile ulmd/ulm-qt yourself, there are some useful files here.

## ulm: URI support ##


ulm-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ulm-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ulm-qt binary to `/usr/bin`
and the `../../share/pixmaps/ulm128.png` to `/usr/share/pixmaps`

ulm-qt.protocol (KDE)

