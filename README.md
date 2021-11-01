# Food-Vision-using-Tensorflow
Food Vision mini: a transfer learning model which beat the original results of the Food101 paper with all of the data from the Food101 dataset.
All 75,750 training images and 25,250 testing images.

The goal is of beating DeepFood, a 2016 paper which used a Convolutional Neural Network trained for 2-3 days to achieve 77.4% top-1 accuracy.

Steps :
* Using TensorFlow Datasets to download and explore data
* Creating preprocessing function for our data
* Batching & preparing datasets for modelling (making our datasets run fast)
* Creating modelling callbacks
* Setting up mixed precision training
* Building a feature extraction model 
* Fine-tuning the feature extraction model 
