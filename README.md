# The dmounter &8212; Thumb Drive Automounter
A cheap clone 'fork' of amounter by SteveLitt for FreeBSD

Version 0.1.1

Created: 30-December-2015

Authors: Steve Litt and David Billsbrough

## Introduction:

The Amounter thumb drive automount software is designed to have minimal
dependencies or complications. It's completely independent of file
managers, window managers, and desktop environments. Given the erratic
track record of various file managers with automounting, this is a key
advantage. Amounter doesn't need X: It can run anywhere that Python and
the Inotify command line tools exist. In practice, it seems to automount
within 5 seconds of insertion.

To install it, read the INSTALL document.

To find out about its bugs, read the BUGS document.

## Usage: 

_NOTE:_

Amounter must be running before you insert a thumb drive.  On many/most
distros, you must run Amounter as root, although some distros provide
a group that can automount, and on those distros, running Amounter as
a member of that group **might** work.

To run Amounter version 0.2.0, run the following as root:

> \# amctl.py
