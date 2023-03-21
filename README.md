# Simple Jigsaw Solver

This is a group project I had the opportunity to work on and I'm pretty happy with how it has turned out till this point.

## Description

The domain of the project falls under Image Processing and is essentially an image deconstruction and reconstruction (with constraints). We're using Jupyter Notebook and python coupled with OpenCV for some mundane tasks.

### Steps

We start with an image which is normal and we break it down into 8 parts which are stitched together randomly to make the actual input image for the program which takes the input and works on the image to try to rearrange it into the original image.

### The Algorithm Simplified

We are essentially splitting the shuffled image back into its constituent parts and work on the individual parts to first join them horizontally by matching the left and right edge pixel values with corresponding parts which are most likely to be the correct neighbour. Following the same step but now on top and bottom edges gives us a potential output which is very likely to be the original image.

### Constraints

(checked means removed)

- [x] Only works on grayscale images as of now. Coloured images are converted to grayscale variant when reading.
- [ ] Only works with portrait images as of now. Haven't tested with landscape images and they're pretty much borked.
- [ ] 8 parted image only. (Was a requirement of the project)

## Credits

- Me (Duh)
- [My Friend](https://github.com/sanidhya17N)
