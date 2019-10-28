# Finding-Lane-Lines
Project to detect lane lines in images using Python and OpenCV

The following project's goal is to identify lane lines in an image by using basic and classical pre-processing to later apply Hugh transformation to identify the lanes. 


# Pipeline Description
1. Grayscale: This is the first step to initiate the image processing
2. Gaussian Filter: This will help to remove unwanted noise from the image
3. Canny Filter: This helps to identify edges in the image. 
4. A polygon is defined in the image that will be used to select the ROI we want to focus on.
In this cane the polygon covers the lane area
5. Using the parameters described in the jupypter notebook, the hough transformation is applied. 


# ******** README UNDER WORK  ***************
