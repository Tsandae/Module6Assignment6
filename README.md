# Module6Assignment6

**Fashion MNIST Classification Using Keras in Python
==================================================

**Project Overview
----------------
This project implements a Convolutional Neural Network (CNN) using **Keras** in the **python**. The model is trained and evaluated on the Fashion MNIST dataset, which is a standard dataset for image classification tasks.

**Prerequisites
-------------
To run this project, ensure the following are installed:

1. Jupyter or visual studio
   
Required python Libraries:
- keras
- matplotlib
- numpy
  
Dataset
-------
The Fashion MNIST dataset consists of:

60,000 training images
10,000 test images Each image is 28x28 pixels in grayscale and classified into one of 10 categories.

##steps to Implementation

1 Load and Preprocess Data:

Normalize pixel values to the range [0, 1].
Reshape images to include a channel dimension.
Convert class labels to categorical format.
Build the CNN Model:

2 Convolutional layers to extract features.

Pooling layers to reduce spatial dimensions.
Flatten layer to convert 2D to 1D.
Fully connected dense layers for classification.

Compile and Train:

Loss: Categorical crossentropy
Optimizer: Adam
Metric: Accuracy
Train for a fixed number of epochs.
Evaluate and Save:

Test the model's performance.
Save the trained model (model.h5).

Make prediction

##NB:
The code for R are in .py
