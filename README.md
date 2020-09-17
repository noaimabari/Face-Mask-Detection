# Face-Mask-Detection

This project treats the face mask detection in crowded scenarios as an object detection problem. A Faster R-CNN architecture with an inception v2 as base model is used. The model was trained for 9 hours on a TESLA K80 GPU from google colab.


## Dataset :

Publicly available dataset from Kaggle containing 853 annotated png images of crowded scenarios. The annotations were in xml format. Three classes were present:
1. With Mask
2. Without Mask
3. Mask weared incorrectly

## Method :

A Faster R-CNN network architecture with an inception v2 base model was used for the task from the TensorFlow model zoo. Tensorflow object detection API was used to train the model for 9 hours on a GPU using Google Colab free GPU access.
Tensorboard used for visualizing the training process.


## References :

1. https://github.com/roboflow-ai/tensorflow-object-detection-faster-rcnn
2. https://www.kaggle.com/andrewmvd/face-mask-detection
