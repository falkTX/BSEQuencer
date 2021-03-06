# B.SEQuencer
Repository: BSEQuencer

Description: Multi channel MIDI step sequencer LV2 plugin with a variable matrix

![screenshot](https://github.com/sjaehn/BSEQuencer/blob/master/docs/screenshot.png "Screenshot from B.SEQuencer")


Installation
------------
Build your own binaries in the following three steps.

Step 1: Clone or download this repository.

Step 2: Install the development packages for x11, cairo, and lv2 if not done yet.

Step 3: Building and installing into the default lv2 directory (/usr/lib/lv2/) is easy. Simply call:
```
sudo make install
```
from the directory where you downloaded the repository files.

For installation into an alternative directory (e.g., /usr/local/lib/lv2), modify line 2 in the makefile.


Running
-------
After the installation Carla, Ardour and any other LV2 host should automatically detect B.SEQuencer.

If jalv is installed, you can also call it
```
jalv.gtk https://www.jahnichen.de/plugins/lv2/BSEQuencer
```
to run it stand-alone and connect it to the JACK system.


Key features
------------
* Step sequencer with a selectable pattern matrix size (8x16, 16x16, 24x16, or 32x16)
* Autoplay or host / MIDI controlled playing
* Handles multiple MIDI inputs signals (keys) in one sequencer instance
* Use musical scales and / or drumkits
* Scale editor
* Controls for playing direction, jump, skip, and stop options placeable to any position within the matrix
* Notes can be associated with four different, configurable output channels
* Output channels connectable with individual MIDI channels


Usage
-----
see https://github.com/sjaehn/BSEQuencer/wiki/B.SEQuencer


TODO
----
* Sort MIDI output messages (bugfix)
* Stability (Note: **This plugin is experimental, yet. Not for production!**)
* Testing
* Bugfixes


See also
--------
* Feature tour: https://www.youtube.com/watch?v=J6bU4GdUVYc
* Preview: https://www.youtube.com/watch?v=iERRKL7J-KU




