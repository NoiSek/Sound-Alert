Sound Alert
=====
A plugin that plays a random sound whenever you receive an alert.
Optional TF2 Taunts available [here](http://github.com/captain-lightning/Sound-Alert). 

### Installation
- To install, move soundoff.py into %appdata%/HexChat/addons for Windows, ~/.config/HexChat/addons for linux. Once there, it will load automatically.
- Move alert sounds into share/sounds within Hexchat's install folder or specify your own sounds folder with "/soundalert set <path>", see Usage.

### Requirements
- Python scripting interface plugin.
- Xine, for linux users.

### Features
- Plays all formats Xine does in Linux. (AAC, AC3, ALAC, AMR, FLAC, MP3, RealAudio, Shorten, Speex, Vorbis, WMA)
- Plays only .wav in Windows.
- Automatically searches for and plays from the share/sounds folder within Hexchat's install directory by default.

### Usage
- /soundalert set \<path> -- Specifies a directory to play sounds from.
- /alertson -- Turns on alerts. Enabled by default.
- /alertsoff -- Disables alerts until re-enabled.
