# GrabPixelGen

Levels in GRAB are stored in .level files.
On Windows:
GRAB stores everything in ```Documents/GRAB``` or ```Documents/GRAB-Demo```.

On Quest:
GRAB stores everything in ```Android/data/com.slindev.grab``` or ```Android/data/com.slindev.grab_demo```.

This tool allows you to generate a .level file from a .jpg file. It will create a level with a small platform and a large block array that makes the pixel art.

## Usage

``` python GrabPixelGen.py img/input.jpg LevelName ``` will output a .level file into the ```generation/level_output ``` folder and can be moved into your GRAB levels folder.
