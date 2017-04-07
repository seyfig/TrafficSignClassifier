#**Traffic Sign Recognition**

**Build a Traffic Sign Recognition Project**

The goals/steps of this project are the following:
* Load the data set (see below for links to the project data set)
* Explore, summarize and visualize the data set
* Design, train and test a model architecture
* Use the model to make predictions on new images
* Analyze the softmax probabilities of the new images
* Summarize the results with a written report


[//]: # (Image References)

[image1]: ./output_images/KeepRight.jpeg "Sample Traffic Sign"
[image2]: ./output_images/visualization.jpg "Visualization"
[image3]: ./output_images/grayscale.jpg "Grayscaling"


## Rubric Points
###Here I will consider the [rubric points](https://review.udacity.com/#!/rubrics/481/view) individually and describe how I addressed each point in my implementation.

###Data Set Summary & Exploration

####1. Basic summary of the data set

The code for this step is contained in the third code cell of the IPython notebook.

I used python functions and the numpy library to calculate summary statistics of the traffic
signs data set:

* The size of training set is 39209
* The size of test set is 12630
* The shape of a traffic sign image is 32 x 32 x 3
* The number of unique classes/labels in the data set is 43

A sample traffic sign image, which belongs to Keep Right class, is given below:
![alt text][image1]

Samples from each class are given in the code cell 6.

####2. Exploratory visualization of the dataset

The code for this step is contained in the seventh code cell of the IPython notebook.

Here is an exploratory visualization of the data set. It is a bar chart showing how the data is distributed between classes.
![alt text][image2]



###Design and Test a Model Architecture

####1. Describe how, and identify where in your code, you preprocessed the image data. What tecniques were chosen and why did you choose these techniques? Consider including images showing the output of each preprocessing technique. Pre-processing refers to techniques such as converting to grayscale, normalization, etc.

As a first step, the traffic signs were converted to grayscale with the code which is contained in the eighth code cell of the IPython notebook.

Here is an example of a traffic sign image before and after grayscaling.

![alt text][image3]

TODO

###Test a Model on New Images
