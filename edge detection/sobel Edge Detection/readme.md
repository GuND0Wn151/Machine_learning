# Sobel Edge Detection Technique

Image Edge Detection is done on the bases of change in intensies of the color. In this we are using Sobel operator for Doing the Edge Detection

Sobel Edge Dection has a Kernal which is kinda like a matrix and this is usefull for finding the Edge
Example of a Kernal is 
	[ -1 , 0 , 1
	 -2 , 0 , 2
	  -2 , 0 , 2 ]
#### This is sobel x and sobel y is transpose of this matrix
  
#### Note: The Size of Matrix must be a odd number

Here we have to do Both in X direction and y direction which will detect both vertical and horizontal edges.

### For Getting More clarity in the images we need to convert the image in grayscale so the RGB colors are converted into intensities.

#### As we are only Finding the Edges or outline of the image we will be only using sobel_y

For more Information on Sobel Operator visit:

#### [Finding Edges using Sobel Operator](https://www.youtube.com/watch?v=uihBwtPIBxM)
```
```
