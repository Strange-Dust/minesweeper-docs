# minesweeper-docs

A collection of documents for Minesweeper that I have gathered.  

Some copy-pasted from other people; some portions are originally written by me.

The goal is to have easily available resources, and clearly-written documentation for minesweeper-specific concepts and terminology.

Corrections/improvements/additions/questions are always welcome.


# Links and Sources
* https://minesweepergame.com
* https://minesweeper.fandom.com/
* https://mzrg.com/mines/info.shtml
* https://github.com/thefinerminer/minesweeper-rawvf
* https://github.com/ralokt/sweeping-view
* https://github.com/ralokt/rmv_spec
* https://github.com/eee555/ms-toollib
* https://github.com/putianyi889/Arbiter-help
* https://github.com/DavidNHill/JSMinesweeper



# SVG files

All of the `svg` files were created by me.

The tiles are 17x17 instead of 16x16.
* There is a 1-pixel overlap.
* It helps with non-integer scaling.

There are background files (`bg`) and foreground (`fg`).
* This allows for a cell to be highlighted,
* while preserving the colour of the number.

There are 2 categories: 
* Pixel
  * Recreated exactly pixel-by-pixel from screenshots.
  * This vastly improves scaling with pixel aesthetic.
* Smooth
  * Intended to match the original pixel versions as closely as possible,
  * while still being smooth, crisp, vector images.

