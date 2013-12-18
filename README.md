# Stupid Sprite Generator CLI

## Installation

* create a file in `/usr/local/bin` called "stupid" and add the content for "stupid" in this gist to the file.
Alternatively you could do a wget.

* Set the file to executable by `chmod +x stupid`

Now, the `stupid` command shoud be available anywhere.

## Dependencies
* Imagemagick
* Optipng

## Instructions
Navigate to a direvtory where you have your image files located.

Now, you could run `stupid` and your files would be generated to 2x9 sprites.

## Options
Options | default | description
:------ | :------ | :------------------------------------
-t      | 2x9     | Sprite grid to be generated
-o      | 5       | Optimization lavel [0-9]
-d      | .       | Image location
-n      | sprite  | Sprite name. Numbers will be appenden
-out    | .       | Output directory

No options are required.

    stupid -t 2x7 -o 5 -d images/ -n sprite -out sprites/