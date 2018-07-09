
Debian
====================
This directory contains files used to package wcxcoind/wcxcoin-qt
for Debian-based Linux systems. If you compile wcxcoind/wcxcoin-qt yourself, there are some useful files here.

## wcxcoin: URI support ##


wcxcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install wcxcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wcxcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/wcxcoin128.png` to `/usr/share/pixmaps`

wcxcoin-qt.protocol (KDE)

