# Face-recognition-through-transfer-learning
Dataset on which I worked on 5 Celebrity Faces Dataset (https://www.kaggle.com/dansbecker/5-celebrity-faces-dataset) then added some of my photos to expand the dataset. Then I used 'haar cascade classifier' for face detection and finally trained the data by adding 2 custom layers on top of MobileNetV2 CNN

The Loss function used is binary cross-entropy is uses sigmoind fuction to classify the data. it predicts for each the probabily of it being in postive class and negetive class.
The accuracy in validation data is ~86%  with batch size of 32

How to install
========
Install Jupyter - https://jupyter.org/install (Or Open in google collab https://colab.research.google.com)

How to run and test 
================
The .ipynb file has the code. Download the dataset unzip it, also download the 'haarcascade_frontalface_default.xml' in the root folder.

Dependencies used:
============
Numpy 
Pandas
Tensorflow
Keras
OpenCV 2
Matplotlib
