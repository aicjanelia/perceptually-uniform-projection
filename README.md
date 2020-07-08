# Perceptually Uniform Projection (PUP)

PUP is an ImageJ macro that uses the CIELAB color space generate a perceptually accurate display of two grayscale images as a single color image. More information about PUP and its derivation can be found in the following publication:

*Taylor, A. B., Ioannou, M. S., Watanabe, T., Hahn, K., & CHEW, T. L. (2017). Perceptually accurate display of two greyscale images as a single colour image. Journal of microscopy, 268(1), 73-83.* <https://doi.org/10.1111/jmi.12588>

## File Descriptions

Our code consists of three files:

* `PUP_CODE.ijm` - the ImageJ macro
* `PUP_NR.lut` - the narrow range lookup table
* `PUP_BR.lut` - the broad range lookup table

## Installation

1. Place the lookup tables files (i.e., `PUP_NR.lut` and `PUP_BR.lut`) in the default ImageJ `luts` folder (typically, `ImageJ.app/luts` or `Fiji.app/luts`).
2. Open/run `PUP_CODE.ijm` through the ImageJ/Fiji menu system (`Plugins > Macros > Run…`).  Alternatively, 'drag-and-drop' the file onto the ImageJ/Fiji toolbar.

## Dependencies

PUP code depends on `ijp-toolkit` written by Jarek Sacha. IJ-Plugins Toolkit comes installed in newer versions of ImageJ/Fiji; however, it can be installed in older versions by following the instructions on <https://github.com/ij-plugins/ijp-toolkit/wiki>.
