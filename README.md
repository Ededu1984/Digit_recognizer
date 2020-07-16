# Digit_recognizer is a problem from Kaggle platform

Competition Description
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision.
Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. 
As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.
In this competition, your goal is to correctly identify digits from a dataset of tens of thousands of handwritten images.
We’ve curated a set of tutorial-style kernels which cover everything from regression to neural networks. 
We encourage you to experiment with different algorithms to learn first-hand what works well and how techniques compare.

Model
CNN( Convolutional Neural Network) 

Layers:

_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_1 (Conv2D)            (None, 24, 24, 30)        780       
_________________________________________________________________
max_pooling2d_1 (MaxPooling2 (None, 12, 12, 30)        0         
_________________________________________________________________
dropout_1 (Dropout)          (None, 12, 12, 30)        0         
_________________________________________________________________
flatten_1 (Flatten)          (None, 4320)              0         
_________________________________________________________________
dense_1 (Dense)              (None, 128)               553088    
_________________________________________________________________
dense_2 (Dense)              (None, 64)                8256      
_________________________________________________________________
dense_3 (Dense)              (None, 32)                2080      
_________________________________________________________________
prediction (Dense)           (None, 10)                330      





This code provided the following score:

Accuracy: 98.32% 

Score in Kaggle after uploading: 0.98214

