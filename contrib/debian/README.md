
Debian
====================
This directory contains files used to package teslad/tesla-qt
for Debian-based Linux systems. If you compile teslad/tesla-qt yourself, there are some useful files here.

## tesla: URI support ##


tesla-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tesla-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your teslaqt binary to `/usr/bin`
and the `../../share/pixmaps/tesla128.png` to `/usr/share/pixmaps`

tesla-qt.protocol (KDE)

