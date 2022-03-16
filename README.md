# Panorama Image Stiching

This project focuses on how to perform __image stitching__.    
The input images are two different views of the same panorama and the output is a combined version of the two to obtain a panorama.  
Image stitching requires the following fundamental __steps__:   

* Keypoint Detection and Description
* Matching of the descriptors
* RANSAC algorithm to estimate a homography matrix
* Warping 

The project discussion contains a description of each step and the corresponding design choices and the discussion and comparison of the results obtained.  
The code is provided along with some test images that we used to test our implementation.  

## Result  ##
Results are shown in the result folder.    
Example:  

__Input Image 1__  
![alt text]( https://github.com/SaraPieri/Panorama/blob/main/Image_stiching/input_images/p1/i1.jpg "Input Image 1")  
__Input Image 1__   
![alt text]( https://github.com/SaraPieri/Panorama/blob/main/Image_stiching/input_images/p1/i2.jpg "Input Image 2")  
__Result__  
![alt text]( https://github.com/SaraPieri/Panorama/blob/main/Image_stiching/outputs/o1.png "Result")  
