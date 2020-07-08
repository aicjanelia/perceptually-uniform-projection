# Perceptually Uniform Projection (PUP)

PUP is an ImageJ/Fiji macro that uses the CIELAB color space to generate a perceptually accurate display of two grayscale images as a single color image. More information about PUP and its derivation can be found in the following publication:

*Taylor, A. B., Ioannou, M. S., Watanabe, T., Hahn, K., & CHEW, T. L. (2017). Perceptually accurate display of two greyscale images as a single colour image. Journal of microscopy, 268(1), 73-83.* <https://doi.org/10.1111/jmi.12588>

## File Descriptions

Our code consists of three files:

* `PUP_CODE.ijm` - the ImageJ/Fiji macro
* `PUP_NR.lut` - the narrow range lookup table
* `PUP_BR.lut` - the broad range lookup table

## Dependencies

PUP code depends on `ijp-color` written by Jarek Sacha. The *Color and Multiband Processing* plugin (which is part of *IJ-Plugins Toolkit*) can be installed through the ImageJ/Fiji update site <https://sites.imagej.net/IJ-Plugins/>. Instructions can be found at <https://github.com/ij-plugins/ijp-toolkit/wiki>.

## Installation

1. Install IJ-Plugins Toolkit dependency.
2. Place the lookup table files (i.e., `PUP_NR.lut` and `PUP_BR.lut`) in the default ImageJ `luts` folder (typically, `ImageJ.app/luts` or `Fiji.app/luts`).
3. Open/Run `PUP_CODE.ijm` through the ImageJ/Fiji menu system (`Plugins > Macros > Run…`).  Alternatively, drag-and-drop the file onto the ImageJ/Fiji toolbar.
