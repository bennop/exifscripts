# EXIF Scripts
Scripts making use of [`exiftool`](https://exiftool.org/) to work with EXIF metadata in images.

## Overview

| name | description |
| ---- | ----------- |
| `mainexif`  | extract some basic acquision parameters
| `cpexif`    | copy that set of EXIF data from one file to another
| `annotwexif`| put an EXIF annotation on the image

## External dependencies
By nature, these scripts rely on [`exiftool`](https://exiftool.org/)
being installed and functional.

The **annotation tool** `annotwexif` additionally utilizes [ImageMagick](https://github.com/ImageMagick)
(which on a Mac also seems to require [GhostScript](https://www.ghostscript.com/) to be installed).

---
*Benno Pütz*

