
Debian
====================
This directory contains files used to package rscoind/rscoin-qt
for Debian-based Linux systems. If you compile rscoind/rscoin-qt yourself, there are some useful files here.

## rscoin: URI support ##


rscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rscoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/rscoin128.png` to `/usr/share/pixmaps`

rscoin-qt.protocol (KDE)

