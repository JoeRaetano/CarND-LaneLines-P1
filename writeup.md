# **Finding Lane Lines on the Road** 

## Writeup 

### 

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"
[image2]: ./test_images/solidWhiteCurve.jpg "solidWhiteCurve.jpg"
[image3]: ./test_images/solidWhiteRight.jpg"solidWhiteRight.jpg"
[image4]: ./test_images/solidYellowCurve.jpg "solidYellowCurve.jpg"
[image5]: ./test_images/solidYellowCurve2.jpg "solidYellowCurve2.jpg"
[image6]: ./test_images/solidYellowLeft.jpg "solidYellowLeft.jpg"
[image7]: ./test_images/whiteCarLaneSwitch.jpg "whiteCarLaneSwitch.jpg"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. 

step 1: create constants so it's easier to test each variable and to make substantive changes 
step 2: build image processing pipeline
step 3: create a gray scale version of the image 
step 4: add gaussian blur effect on image
step 5: apply canny algorithm to identify edges
step 6: work to apply region of interest
step 7: define a four sided polygon to mask and then create masked edges instead of region_of_interest function
step 8: Run Hough on edge detected image

output examples:

![alt text][image1]
![alt text][image2]
![alt text][image3]
![alt text][image4]
![alt text][image5]
![alt text][image6]
![alt text][image7]


### 2. Identify potential shortcomings with your current pipeline


One shortcoming when I worked on the challenge problem. It took a while to get set up and ran out of time figuring out creative ways to tackle that problem.


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to set up a function correctly to determine separate left and right lines


