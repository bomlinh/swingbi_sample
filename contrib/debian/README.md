
Debian
====================
This directory contains files used to package swingbicoind/swingbicoin-qt
for Debian-based Linux systems. If you compile swingbicoind/swingbicoin-qt yourself, there are some useful files here.

## swingbicoin: URI support ##


swingbicoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install swingbicoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your swingbicoinqt binary to `/usr/bin`
and the `../../share/pixmaps/swingbicoin128.png` to `/usr/share/pixmaps`

swingbicoin-qt.protocol (KDE)

