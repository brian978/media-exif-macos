# media-exif-macos

I came up with this project while I was exporting my images from Apple Photos. 

## Problem
After I export my images and videos from Apple Photos, the created date, is wrong. For example if I take a photo on the 21st of Nov and export it on 28th of Nov, the _Created Date_ of the file is the date of the export and not the date of when the photo was take. This in a way is accurate, however if I reimport the image into Apple Photos the date of the photo will be 28th of Nov instead of the original photo data

## The solution
This app reads the exif information of the images or videos and updates the creation date so that it matches with the date at which the picture was taken.
