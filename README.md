# Celebrity-Face-Recognition
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

The Deep Learning Model is trained using Tensorflow Framework and it gives validation accuracy value of 85%

![Image detaset](https://user-images.githubusercontent.com/41227474/152083422-64a2e197-5da5-458b-8914-fbacd526e731.png)

## Description:
Download the dataset from the kaggle link given below the description and split it into the training set and and validation set based on the given ratio.**Transfer Learning** has been implemented  with the **MobileNetV2** model and **imagenet** weights. The pre-trained model consists of 155 layers and the whole layers of the pretrained model is retrained to get the better accuracy.Image Augmentation has been implemented to avoid the overfitting of the model.The model has been trained for the 50 epochs and the model has scored **Validation Accuracy of 85**.

## Dataset Content:

This images has been collected from Pinterest and cropped. There are 105 celebrities and 17534 faces

#### Dataset Link: https://www.kaggle.com/hereisburak/pins-face-recognition 

## Prerequisites:

The below libraries are needed to execute the Python code

- Python 3.9
- Tensorflow 2.8.0
- Numpy
- Matplotlib

## Pre-Trained Weights:
The pre-trained model weights for the classification of 105 celebrities has been uploaded as a .zip file which can be extracted to obtain the .h5 file. This file can be loaded with the Tensorflow in case of without training the model again to obtain the new weights.
