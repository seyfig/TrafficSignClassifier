## Project: Build a Traffic Sign Recognition Program
[Udacity - Self-Driving Car NanoDegree Traffic Sign Classifier Project](https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project)

Overview
---
In this project, I trained a convolutional neural network to classify traffic signs using the German Traffic Sign Dataset. After training the model, I tried out the model on the images that I capture in Turkey.

I completed the project using Ipython notebook, which is saved as [HTML](https://seyfig.github.io/TrafficSignClassifier/), and TensorFlow.

The Project
---
The goals / steps of this project are the following:
* Load the data set
* Explore, summarize and visualize the data set
* Design, train and test a model architecture
* Use the model to make predictions on new images
* Analyze the softmax probabilities of the new images
* Summarize the results with a written report

### Dependencies
This lab requires either the conda environment described in section A or the libraries listed in section B.

#### A.
* [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit)

The lab environment can be created with CarND Term1 Starter Kit. Click [here](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md) for the details.

#### B.
The following libraries:
* pickle
* matplotlib
* numpy
* scikit-learn
* TensorFlow

### Dataset

The dataset, downloaded from the Udacity Classroom, was a pickled dataset in which the images have been already resized to 32x32. It contained a training, validation and test set.
