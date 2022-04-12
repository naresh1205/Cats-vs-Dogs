# Image-Classification-with-Keras
Convolutional Neural Network model to classify cats vs dogs images using Tensorflow Keras
This repository contains two major CNN models.
First, keras_learn_CNN.ipynb, this contains a modified VGG16 model. The final layer of the VGG16 model has been modified to ouput either 0 or 1, 
corresponding to dogs and cats respectively.
Second, keras_learn_mobilenet.ipynb, this uses the mobilenet_1.00_224 model (excluding the last 6 layers) and classifies sign language digits.
