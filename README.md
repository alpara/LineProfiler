# LineProfiler
Calculate multiple 3D profiles from multiple projected laser lines with multiple cameras

This software demonstrates a patented algorithm that allows the direct output of 3D points 
straight from the image input.
In the first step, a 2D line profile is calculated using a very simple algorithm, 
which is converted into 3D points in the second step.
The algorithm works with ordinary cameras and those that output cutting lines, 
e.g. from Photonfocus AG. In the second case, the calculation of the line profiles 
is of course superfluous because these are supplied directly by the camera.
It is possible to combine several cameras and evaluate them in a single step.
The calibration is a different but private project and is not made freely available.

The algorithm can also be implemented directly in camera hardware.
It is possible for multiple cameras to directly provide 3D points in a single coordinate system.

If you are interested in more.
Contact us
