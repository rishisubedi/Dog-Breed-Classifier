# Project Overview

This project is a part of the Udacity Deep Learning Nanodegree Program where I get chance to build the application that classify any breed of the dogs from the supplied images. Furthermore, the application can also predict the best resemble of the dog breed if human face is provided. 

The CNN architecture I build have the accuracy of the 13% .

The code is written in Python 3 and Pytorch as the deep learning framework that are all presented in Jyputer Notebook.


# Dog Images 

wget https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip and unzip it.

# Human Images

wget http://vis-www.cs.umass.edu/lfw/lfw.tgz and unzip it.

# Metrics
Since, the application focus on the muti-classification problem and images are usually not a regular pixel size. I used the accuracy evaluation metrics as well the crossentropy cost function. The labels are put into the respective categorical format. The target files are all list of the encoded dog labels that is related to the images with this given format.

# Dog and Human Detector

To detect the dog and the human effectively, I used OpenCV's implementation of Haar feature-based cascade object classifier.

# Dog Classifier Model
I created a four layer CNN in Pytorch that classifies the dog breed and the accuracy is exactly 13% which is better than the random guessing. As my model still fails to classify dog breed,I use state of art model ResNet50 to classify dogs. The resnet model achieve the accuracy of 83% and used to classify the dog dataset.

# Implementation and result

I try VGG19 and the InceptionV3 in the implementation but used the Resnet50 model to classify the dog breed and it classify most of the dog breed correctly.
