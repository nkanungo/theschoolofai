

Assignment 3
Name : Nihar Kanungo Batch : 6:30 AM , Monday

Background :
===========

This is a simple Image Recognition program which makes use of the MNIST preprocessed dataset to process the handwritten digit images and predict the numerical digit each image resents . The Code uses one of the most popular Tensorflow API Keras to perform the operations .It's a supervised Computer Vision problem.

Input
===========
1) 60000 Handwritten digit images (between 0-9) 2) The Images are already segreegated as Train and Test Data with the respective target values

Environment
===========
Development - Colab GPU , Jupyter Notebook
Repository : Github

Algorithm
===========
Linear Model 
Convolutional Neural Network (2D) - Gray Scale images
Maxpooling 
Softmax Activation function
loss Function : Categorical Crossentropy
Optimizer=Adam
Metrics=accuracy

Parameters
===========
Batch Size - Variable 
Epochs - Variable
Kernel Size - Variable (Advisable to use 3 * 3)
Number of Kernels - Variable 

Condition
===========
The Number of parameters < 20,000
Should use only Conv2D
Should not have applied Maxpooling before 2-4 layers of the conversion into number of classes (10 in this case)
Maxpooling should be applied on receptive field of at least 5 x 5 or 7 x 7
Activation function should be relu on conv 2D

Expected Result
===========
To get >= 99.4 % accuracy

Actual Result
===========
Best Results till now ( 2nd August 5:50 PM)

Accuracy - 99.23 %
Accuracy - 99.21 %
Accuracy - 99.20 %
Accuracy - 99.19 %
Accuracy - 99.17 %


Below is just a pictorial representation of how convolution reduces the image size by increasing the receptive field. 
The Illustration shows an image of 9 x 9 at the beginning where as in reality the images are very big and complex in nature. We will see in future how to apply different techniques on then, but for simplicity of our understanding we will use small size kernels here. If you haven’t seen the previous article which talks about why a 3 x 3 kernel is the best one to use then please go back and read through it. 

