**Finding Lane Lines on the Road**

Term 1, Project 1

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report

Steps used to create this project
* Grayscale image
* HSV image - set a range of colors to filter out the lane lines within a range of whites and yellow
* Blur the image using Gaussian blur
* Detect the edges using Canny edge detection
* Set the region of interest to focus the line detection
* Set adjustable parameters for the Hough Lines
* Separate and calculate an average line to use for the left and right hand lanes  

[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

There are a number of areas that could be improved upon that could give better performance in lane detection:

* Different times of the day
* Curves in the road
* Larger missing lane lines
* Shadows


This has been my first attempt at piecing together different filters and parameters to build a basic lane line detection algorithm. I would like to spend more time improving the edge cases in lane detection given more time but as this is my first project I want to keep moving through the course.

I plan to revisit this project once I have learned some more skills and knowledge to be able to build a more robust solution to the problem and very interested to compare my results in the future with what the solution I came up with so early in the course.
