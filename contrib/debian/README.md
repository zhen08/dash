
Debian
====================
This directory contains files used to package gustd/gust-qt
for Debian-based Linux systems. If you compile gustd/gust-qt yourself, there are some useful files here.

## gust: URI support ##


gust-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gust-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gust-qt binary to `/usr/bin`
and the `../../share/pixmaps/gust128.png` to `/usr/share/pixmaps`

gust-qt.protocol (KDE)

