# Face-Mask-Detection

This project treats the face mask detection in crowded scenarios as an object detection problem. A Faster R-CNN architecture with an inception v2 as base model is used. The model was trained for 9 hours on a GPU from Google Colab.


## Dataset :

Publicly available dataset from KAGGLE containing 853 annotated png images of crowded scenarios. The annotations were in xml format. Three classes were present:
1. With Mask
2. Without Mask
3. Mask weared incorrectly

## Method :

A Faster R-CNN network architecture with an inception v2 base model was used for the task from the TensorFlow model zoo. Tensorflow object detection API was used to train the model for 9 hours on a GPU using Google Colab free GPU access.
Tensorboard used for visualizing the training process.

## Results :

Add graphs and pictures

## References :

1.
2. 
