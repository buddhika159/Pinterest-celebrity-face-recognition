# Celebrity Face Recognition using Transfer Learning
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)

## Description:
This project builds a Deep CNN using **Transfer Learning** method.
  - Dataset: [Kaggle Pinterest celebrity faces](https://www.kaggle.com/datasets/hereisburak/pins-face-recognition)
    - There are 17534 faces of 105 celebrities
  - Randomly create training test datasets
  - Model: `MobileNetV2` 155 layers
    - `MobileNetV2()` with `imagenet` weights -->  `Dropout layer` --> `softmax layer`
  - `myCallback()` to stop training when accuracy reaches `98%`
  - Validation Accuracy: `95.56%`
  - Validation Accuracy: `96.81%`

<p align="middle">
  <img src="fig.png" width="90%" />
</p>

## Prerequisites:
Below libraries are needed to execute this Python code.
- Python 3.9
- Tensorflow 2.8.0
- Keras 2.7.0
- Numpy
- Matplotlib

## Pre-Trained Weights:
The pre-trained model weights for the classification of 105 celebrities have been uploaded as a .zip file which can be extracted to obtain the .h5 file. This file can be loaded with the Tensorflow in case without training the model again to obtain the new weights.
