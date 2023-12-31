# Image-Classification-VGG-16

## Introduction
This assignment focuses on Convolutional Neural Networks (CNNs) and the Keras API for image classification and regression tasks. The dataset involves plant images with various species and associated bounding box information.

## Data Preparation
The dataset consists of plant images obtained from the Plant Seedlings dataset by Giselsson et al. [Plant Seedlings Dataset](https://vision.eng.au.dk/plant-seedlings-dataset/). Download the subset from the Aarhus University Plant Seedlings Dataset .Organize the data into training, validation, and test sets.

## Basic Transfer Learning
Classification Network
Utilize the Keras implementation of VGG-16 as a starting point. Extend the model by adding extra layers for a CNN to classify images based on the number of leaves. Train the network on the training set, monitoring convergence on the validation set. Use images of size up to 128x128. Print learning curves and provide the confusion matrix for the training, validation, and testing datasets.

## Regression Network
Extend the same VGG-16 architecture for regression to predict the height and width of the bounding box for weed images. Ground truth bounding box information is available in the "bbox.json" file. Normalize the height and width corresponding to the image size. Print learning curves and provide the mean squared error on the training, validation, and testing datasets.

## Improving the Model
Incorporate two regularization methods (e.g., Batch Normalization, Dropout, Weight Normalization) into the network layers of the model that performs better between the Classification and Regression Networks. Print learning curves and corresponding metrics.

## Discussion
Discuss the possibility of overfitting based on learning curves for both Classification and Regression Networks. Evaluate the impact of regularization on model performance.


