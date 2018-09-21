
Debian
====================
This directory contains files used to package splashfarmsd/splashfarms-qt
for Debian-based Linux systems. If you compile splashfarmsd/splashfarms-qt yourself, there are some useful files here.

## splashfarms: URI support ##


splashfarms-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install splashfarms-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your splashfarmsqt binary to `/usr/bin`
and the `../../share/pixmaps/splashfarms128.png` to `/usr/share/pixmaps`

splashfarms-qt.protocol (KDE)

