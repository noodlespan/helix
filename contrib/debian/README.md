
Debian
====================
This directory contains files used to package tcashd/tcash-qt
for Debian-based Linux systems. If you compile tcashd/tcash-qt yourself, there are some useful files here.

## tcash: URI support ##


tcash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tcash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tcashqt binary to `/usr/bin`
and the `../../share/pixmaps/tcash128.png` to `/usr/share/pixmaps`

tcash-qt.protocol (KDE)

