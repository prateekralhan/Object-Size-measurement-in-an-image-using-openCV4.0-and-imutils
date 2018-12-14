# Object-Size-measurement-in-an-image-using-openCV4.0-and-imutils
Measuring the size of objects in an image using Pixel per Metric ratio and openCV4.0 with imutils.

## Libraries Installation:

1. OpenCV4.0: Refer this: https://www.pyimagesearch.com/opencv-tutorials-resources-guides/

2. numpy/argparse/imutils/scipy: Do _pip install numpy/argparse/imutils/scipy_

Measuring the size of objects in an image is similar to computing the distance from our camera to an object — in both cases, we need to define a ratio that measures the number of pixels per a given metric.

    ### Property 1: 
We should know the dimensions of this object (in terms of width or height) in a measurable unit (such as millimeters, inches, etc.).
   ### Property 2: 
We should be able to easily find this reference object in an image, either based on the placement of the object (such as the reference object always being placed in the top-left corner of an image) or via appearances (like being a distinctive color or shape, unique and different from all other objects in the image). In either case, our reference should should be uniquely identifiable in some manner.

### Execute the command: 
 python object_size.py --image images/example.png --width 0.955 
