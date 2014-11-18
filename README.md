cjpeg-dssim
===========

## Introduction
Automatically find the ideal JPEG quality setting for a JPEG image by calculating the output images dissimilarity from the input JPEG. This frees us from having to rely on the unstandardized quality integer.

## Installation instructions
Place this script anywhere in your $PATH. Requires Bash >= 4.x

## Required tools
* dssim - https://github.com/pornel/dssim
* jpegoptim - https://github.com/tjko/jpegoptim
* mozjpeg - https://github.com/mozilla/mozjpeg

## CLI usage
	cjpeg-dssim /path/to/input-image.jpg
