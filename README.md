 
Measuring the size of objects in an image with OpenCV


Measuring the distance from a camera to an object, we need to determine our “pixels per metric” ratio, which describes the number of pixels that can “fit” into a given number of inches, millimeters, meters, etc.

To compute this ratio, we need a reference object with two important properties:

  Property #1: The reference object should have known dimensions (such as width or height) in terms of a measurable unit (inches,                       millimeters, etc.).
  Property #2: The reference object should be easy to find, either in terms of location of the object or in its appearance.
           Provided that both of these properties can be met, you can utilize your reference object to calibrate your pixels_per_metric                variable, and from there, compute the size of other objects in an image.
       
Requirements : 1)OpenCV 2)Python 3.6 3)imutils
Run Command : python object_size.py --image 'path to image'/example_01.png --width 'width in cm'

Project by -
Saikiran Naramwar-2016BTECS00079
Sourabh Kanwade-2016BTECS00053
Yogesh Kumare-2017BTECS00109
