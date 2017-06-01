# **Finding Lane Lines on the Road** 

## Writeup 

### 

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image2]: ./examples/image2.jpg "image2.jpg"
[image3]: ./examples/image3.jpg "image3.jpg"


---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 8 steps. 

step 1: create constants so it's easier to test each variable and to make substantive changes 
step 2: build image processing pipeline
step 3: create a gray scale version of the image 
step 4: add gaussian blur effect on image
step 5: apply canny algorithm to identify edges
step 6: work to apply region of interest
step 7: define a four sided polygon to mask and then create masked edges instead of region_of_interest function
step 8: Run Hough on edge detected image

output examples:

![alt text][image2]
![alt text][image3]



### 2. Identify potential shortcomings with your current pipeline


One shortcoming when I worked on the challenge problem. It took a while to get set up and ran out of time figuring out creative ways to tackle that problem.


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to set up a function correctly to determine separate left and right lines


