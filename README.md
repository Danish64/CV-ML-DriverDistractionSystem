#Check DistractionDetection Prediction Notebook (Main Work)
# Distracted-Driver-Detection
# Abstract
The objective of this work is to successfully predict the likelihood of what a driver is doing in each of the pictures in the dataset.
The data consists on a set of images, each taken in a car where the driver is doing some action (e.g. texting, talking on the phone, doing their makeup). These are some examples:

# Dependencies
Python 3.6.1
Tensorflow 1.3.0
Keras 2.1.2
matplotlib 2.0.2
numpy 1.12.1

# Project Overview
According to the CDC motor vehicle safety division, one in five car accidents is caused by a distracted driver. Sadly, this translates to 425,000 people injured and 3,000 people killed by distracted driving every year.
In this project, we have created and refined machine learning models to detect what the driver is doing in a car given driver images. This is done by predicting the likelihood of what the driver is doing in each picture.

# Problem Statement
In order to improve the alarming statistics states in the project overview section, innovative methods should be tested. One such method would be to develop an algorithm to detect drivers engaging in distracted behaviours by feeding it 2D dashboard camera images. This algorithm can then be used as an API in a device to classify the driver’s behaviour by checking if they are driving attentively, wearing their seatbelt and remind them if they are not.
The dataset provided by State Farm consists of images, which means that the most efficient way to tackle the problem at hand is to develop a deep convolutional neural network model and then train it on a training subset of the dataset with the objective to optimize a certain evaluation metric. The model will then be tested on a testing subset of the dataset and evaluated.
 
Following are needed tasks for the development of the algorithm:
Download and preprocess the driver images
Build and train the model to classify the driver images
Test the model and further improve the model using different techniques.
 
# Data Exploration
The dataset used in this project was provided by State Farm through a Kaggle competition, which if a set of images of drivers taken inside a car capturing their activities such as texting, talking on the phone, eating, reaching behind, putting on makeup, etc. These activities are classified into 10 classes as:
+ c0: safe driving
c1: texting — right
c2: talking on the phone — right
c3: texting — left
c4: talking on the phone — left
c5: operating the radio
c6: drinking
c7: reaching behind
c8: hair and makeup
c9: talking to a passenger
 
 
The dataset contains a total of 102150 images split into a training set of 22424 images and a testing set of 79726 images.

# Input

![First Test Image](https://github.com/Danish64/CV-ML-DriverDistractionSystem/blob/master/InputOutputImages/Input1.PNG)
![Second Test Image](https://github.com/Danish64/CV-ML-DriverDistractionSystem/blob/master/InputOutputImages/Input2.PNG)
![Third Test Image](https://github.com/Danish64/CV-ML-DriverDistractionSystem/blob/master/InputOutputImages/Input3.PNG)

# output 

![First Test Image](https://github.com/Danish64/CV-ML-DriverDistractionSystem/blob/master/InputOutputImages/Output1.PNG)
![Second Test Image](https://github.com/Danish64/CV-ML-DriverDistractionSystem/blob/master/InputOutputImages/Output2.PNG)
![Third Test Image](https://github.com/Danish64/CV-ML-DriverDistractionSystem/blob/master/InputOutputImages/Output3.PNG)






