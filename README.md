# mpv config

# Installation
1. Press "Win + r" to bring up run prompt.
2. Type "%appdata%\mpv" in the "open" field.
3. Clone/download the files from github however you want.
4. Drag all contents of the repo to the mpv folder you opened in step 2.

# General
My MPV settings I use, mostly for watching anime. Only tested on Windows 10.

# mpv.conf
Most of the stuff in here is pretty common, the only thing to note is that the default shaders are the heaviest anime4k shaders in terms of load on your computer. You may want to change this.

# Shaders
Includes all of [anime4k](https://github.com/bloc97/Anime4K) shaders. Details on what each of the keybind shader settings mean can be found [here](https://github.com/bloc97/Anime4K/blob/master/md/GLSL_Instructions_Advanced.md#advanced-usage-instructions-glsl--mpv-v4x)
Also includes SSimSuperRes upscaler and nnedi3 from the Ravu upscalers, but honestly I don't use them that much.

# Scripts
[copy-paste-URL](https://github.com/elhirchek/copy-paste-url/tree/master) allows for "CTRL + v" to be used on an mpv window instance to paste a link to be played.

[easycrop](https://github.com/aidanholm/mpv-easycrop) uses "c" as a keybind to crop current file. Press "c" once to begin cropping, left click once to set first point and left click again to set second point. To clear crop press "c" again.

[webm](https://github.com/ekisu/mpv-webm) is an easy webm creator for making webms. Press "W" (shift + w) to begin the process, an OSD will come up with instructions.


[seek-to](https://github.com/occivink/mpv-scripts) allows you to seek to a specific time. Go to their github link to see more instructions.

# What Needs To Be Changed
Make sure the directories in /script-opts/webm.conf(line 12) and mpv.conf(line 37) are what you want them to be.