Minecraft MapStitcher
=====================

This is a simple python script that generates a map image of a world based on the already-generated in-game maps.
Because this does not depend on the region file format, this should work in 1.12 and 1.13, and probably previous
versions as well.

How To Use
------------

You'll need to install Python. Then you will need the [NBT library by twoolie](https://github.com/twoolie/NBT).
The easiest way to get this is to use PIP (```pip install NBT```).

Then, put mapstitcher.py and config.py into a folder. Edit the values in config.py to your liking, then
run ```python mapstitcher.py```. That's it!