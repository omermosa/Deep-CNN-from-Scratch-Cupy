# Deep-CNN-from-Scratch-Cupy

This repo implements Deep Convolutional Neural networks along with Fully connected layers and Adam Optimizer using Cupy from scratch to be able to run on GPU. The implementation was trained and tested using Flowers Dataset. This was done as a part of the Practical Machine Deep Learning course at AUC.

The implementation is inspired by Tensorflow.Keras API Sequential model. I tried to make the same layers and the same functionality equivalent to using tf.keras.

The model was able to achieve about 90% on the test data, which is close to the accuracy of the powerful MobileNet V2 on the same data.

The trained models can be downloaded using the link and can be loaded using
model.load_model() function in order to reproduce the results on the data. The link to the data and
the models is provided below:
https://drive.google.com/drive/folders/1wuF9XOJNXr0PKIhkALEyP9Ya5UPXsFK7
?usp=sharing

