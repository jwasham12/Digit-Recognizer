## Problem Statement

**Classify digit images using Principal Component Analysis (PCA) and supervised classification machine learning methods.**
    
    
## Executive Summary

Image processing is a method to perform some operations on an image, in order to get an enhanced image or to extract some useful information from it. In machine learning, the images are converted into pixels in order to extract common characteristics of pixels to classify the similar image. The dataset from Kaggle contained the pixel values of the 42000 digit images and the correct labels. The goal of this project is to correctly identify digits from a dataset of tens of thousands of handwritten images using data science techniques and computer vision fundamentals.

## Data Dictionary

- Obtain data from [Kaggle](https://www.kaggle.com/c/digit-recognizer).
- Dataset is relased in 1999 by MNIST (Modified National Institute of Standards and Technology).
- Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. 

|Feature|Type|Description|
|---|---|---|
|Label|integer|Label of the digit image (0-9)| 
|Pixel0~783|integer|pixel value of the images| 

## Method

- Obtain the data from Kaggle
- Check the images of the digits
- Build model using different types of pre-processing
- Select the best model
- Search the best parameter of the final model (Use AWS)
- Evaluate the model


## Conclusion

**Best Model**
- Preprocessing
    - Standard Scaler (Scaling)
    - Principal Component Analysis (222 components)
- Support Vector Classifier (SVC)
    - C = 1
    - gamma = 0.001

**Train Accuracy = 0.974**

**Test Accuracy = 0.956**
