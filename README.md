# Dacon Semiconductor Image Classification - CNN with TensorFlow.

_This project implements a Convolutional Neural Network (CNN) model for classifying semiconductor images from the Dacon Semiconductor dataset using TensorFlow._

## Project Goal
The goal is to train a CNN model to automatically distinguish between different types of semiconductors in images (Good and Bad). This can be useful for applications like semiconductor inspection or automated sorting.

## Functionality

* Data Preprocessing
  * Renames image files according to a consistent naming convention.
  * Splits the dataset into training, validation, and test sets.
  * Applies data augmentation techniques (e.g., rescaling) to the training data.
    
* Model Architecture
  * Constructs a CNN model with convolutional layers for feature extraction, pooling layers for dimensionality reduction, and fully connected layers for classification.
* Model Training
  * Trains the CNN model using the Adam optimizer and binary cross-entropy loss function suitable for binary classification problems.
  * Monitors training progress using accuracy metrics.
## Getting Started
* Prerequisites
  * Python 3.x
  * TensorFlow library (installation instructions: https://www.tensorflow.org/install/pip)
  * Scikit-learn library (installation instructions: https://scikit-learn.org/0.16/install.html)
  * Matplotlib library (installation instructions: https://matplotlib.org/stable/install/index.html)
* Downloading the Dataset
  * Download the Dacon Semiconductor dataset from https://dacon.io/en.
