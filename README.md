# TensorFlow Speech Recognition Challenge

### Description:

This repository contains code for constructing an algorithm that understands simple speech commands, a neural network with **EfficientNet** architecture is used as an algorithm, trained on ten classes of [competition data](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data).

### Motivation :
Training practice and an autonomous alternative for voice recognition, for my [voice assistant for Raspberry Pi](https://github.com/OldBonhart/home_ai)

### Data:
Available [here](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data)

<p>
 <img border="0"src="https://github.com/OldBonhart/TensorFlow_Speech_Recognition_Challenge/blob/master/static/waves.png" width="600" height="406">
</p>

### Solution:
[Train___EfficientNet.ipynb](https://github.com/OldBonhart/TensorFlow_Speech_Recognition_Challenge/blob/master/Train___EfficientNet.ipynb)[<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1lHiPQnoNZiLfQvPfQCk-mCEGztPz4LuF)<br>
This is a [pytorch implementation](https://github.com/lukemelas/EfficientNet-PyTorch) neural net with architecture **EfficientNet**, by uploading pre-trained weights to the net, you can test it right from google colaboratory. [demo.ipynb](https://github.com/OldBonhart/TensorFlow_Speech_Recognition_Challenge/blob/master/demo.ipynb)[<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1oUxjH9X6CiThACCuFIndUwKK5eZVVepp)<br>

### Results:
Below is a confusion matrix of validation data.

<p>
 <img border="0"src="https://github.com/OldBonhart/TensorFlow_Speech_Recognition_Challenge/blob/master/static/confusion_test_matrix.png" width="300" height="255">
</p>

