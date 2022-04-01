# [Celebrity Face Recognition using Transfer Learning](https://github.com/buddhika159/Pinterest-celebrity-face-recognition)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)

The Deep Learning Model is trained using Tensorflow Framework and it gives a validation accuracy value of 85%

<p align="middle">
  <img src="fig.png" width="90%" />
</p>

## Description:
Download the dataset from the Kaggle link given below the description and split it into the training set and validation set based on the given ratio.**Transfer Learning** has been implemented  with the **MobileNetV2** model and **imagenet** weights. The pre-trained model consists of 155 layers and the whole layers of the pre-trained model are retrained to get better accuracy. Image Augmentation has been implemented to avoid the overfitting of the model. The model has been trained for the 50 epochs and the model has scored **Validation Accuracy of 85**.

## Dataset Content:

These images are collected from Pinterest and cropped. There are 17534 faces of 105 celebrities.

#### Dataset Link: https://www.kaggle.com/hereisburak/pins-face-recognition 

## Prerequisites:

Below libraries are needed to execute this Python code.

- Python 3.9
- Tensorflow 2.8.0
- Numpy
- Matplotlib

## Pre-Trained Weights:
The pre-trained model weights for the classification of 105 celebrities have been uploaded as a .zip file which can be extracted to obtain the .h5 file. This file can be loaded with the Tensorflow in case without training the model again to obtain the new weights.
