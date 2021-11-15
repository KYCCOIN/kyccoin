
Debian
====================
This directory contains files used to package kyccoind/kyccoin-qt
for Debian-based Linux systems. If you compile kyccoind/kyccoin-qt yourself, there are some useful files here.

## kyccoin: URI support ##


kyccoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kyccoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kyccoinqt binary to `/usr/bin`
and the `../../share/pixmaps/kyccoin128.png` to `/usr/share/pixmaps`

kyccoin-qt.protocol (KDE)

