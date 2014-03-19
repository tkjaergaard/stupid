# Stupid Sprite Generator CLI

## Installation

* Clone this repository and move the `stupid` file to your `bin/` directory.
* Set the file to executable by `chmod +x stupid`

Now, the `stupid` command shoud be available anywhere.

## Dependencies
* Imagemagick
* Optipng

If your on osx, these two dependencies could be installed easily through [Homebrew](http://brew.sh/)


## Instructions
Navigate to a directory where you have your image files located.

Now, you could run `stupid` and your files would be generated to 2x9 sprites.

## Options
Options | default | description
:------ | :------ | :------------------------------------
-t      | 2x9     | Sprite grid to be generated
-o      | 5       | Optimization lavel [0-9]
-d      | .       | Image location
-n      | sprite  | Sprite name, numbers will be appended
-out    | .       | Output directory

No options are required.

    stupid -t 2x7 -o 5 -d images/ -n sprite -out sprites/
 
## Resources

You should take a look at the online generator that Stupid has published as well as the jQuery plugin that you need to implement at your site in order to get this up and running:

[Stupid Sprite Generator](http://apps.stupid-studio.com/)   
[Stupid jQuery Sprite Anim](https://github.com/StupidStudio/jQuery-Sprite-Anim)
