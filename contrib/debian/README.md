
Debian
====================
This directory contains files used to package mitrad/mitra-qt
for Debian-based Linux systems. If you compile mitrad/mitra-qt yourself, there are some useful files here.

## mitra: URI support ##


mitra-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mitra-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mitraqt binary to `/usr/bin`
and the `../../share/pixmaps/mitra128.png` to `/usr/share/pixmaps`

mitra-qt.protocol (KDE)

