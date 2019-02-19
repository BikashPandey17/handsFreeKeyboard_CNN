# handsFreeKeyboard_CNN
Deep learning project on CNN Hand gesture classification.

Proposed Title of the Project(By Guide) - Communication System for audibly Disabled people

# Introduction 

## Background

As a subfield of Deep learning, the field of computer vision has undergone tremendous research through the ages. Gesture recognition is one
such topic that falls under computer vision that allows users to control and interact with any device without actually touching them.
We attempt at providing an efficient hand gesture recognition system where the users can tweak the real time processing according to their environment and use it accordingly.
This project focuses on implementing a real time application that recognizes 48 different gesture inputs which include English Alphabets(A
-Z), Numbers(0-9) and special characters like(',', space, new line,... etc) which inturn aids in the communication of people who are
audibly or vocally impaired acting as the medium of translation. Moreover the application also allows people to continously use it as a
real time keyboard without actual "Keys". Frankly the technology has vast areas of application which includes Gaming, Security, Medicine
etc but we can focus on only one now!
Given the fact we wrote a software driven only by mathematical algorithms without using any external devices like kinect depth camera etc
(except obviously a Camera) reduces the cost drastically and helps the application to reach a greater demographic.

## Objectives

We attempt at providing an efficient hand gesture recognition system where the users can tweak the real time processing according to their environment and use it accordingly.
This project focuses on implementing a real time application that recognizes 48 different gesture inputs which include English Alphabets(A
-Z), Numbers(0-9) and special characters like(',', space, new line,... etc) which inturn aids in the communication of people who are
audibly or vocally impaired acting as the medium of translation. Moreover the application also allows people to continously use it as a
real time keyboard without actual "Keys". Frankly the technology has vast areas of application which includes Gaming, Security, Medicine
etc but we can focus on only one now!

## Purpose and Scope
### Purpose

We attempt at providing an efficient hand gesture recognition system where the users can tweak the real time processing according to their environment and use it accordingly.
This project focuses on implementing a real time application that recognizes 48 different gesture inputs which include English Alphabets(A
-Z), Numbers(0-9) and special characters like(',', space, new line,... etc) which inturn aids in the communication of people who are
audibly or vocally impaired acting as the medium of translation. Moreover the application also allows people to continously use it as a
real time keyboard without actual "Keys". Frankly the technology has vast areas of application which includes Gaming, Security, Medicine
etc but we can focus on only one now!

### Scope

Frankly the technology has vast areas of application which includes Gaming, Security, Medicine
etc but we can focus on only one now!
Given the fact we wrote a software driven only by mathematical algorithms without using any external devices like kinect depth camera etc
(except obviously a Camera) reduces the cost drastically and helps the application to reach a greater demographic.


# Survey Of Technologies 

Gesture Recognition has been growing as a research/application for several years. The two major branches include video processing and
CNN to recognize different classes. Such discipline have their foundation in various technologies and have evolved into various advanced
forms in modern technology.
In deep learning, a convolutional neural network (CNN, or ConvNet) is a class of deep neural networks, most commonly applied to analyzing visual imagery.Convolutional networks were inspired by biological processes in that the connectivity pattern between neurons resembles the organization of the animal visual cortex. 
OpenCV (Open source computer vision) is a library of programming functions mainly aimed at real-time computer vision. Originally developed by Intel, it was later supported by Willow Garage then Itseez 

# Requirement and Analysis

### * Problem Definition

The two main principles involved in the implementation of a gesture recognition system are (1)image processing (which involves feature extraction) and (2)Recognition / Prediction of the processed image. 

The code developed takes a live video as input and extracts frames, then applies the relevant image processing to track the hand in the region of interest then extract that relevant portion for further processing. This processed image is used as the input of the CNN which predicts it's class.

Thus we need to develop a software that provides a level of abstraction for the live video processing and the output of the algorithm.

### Requirement Specifcation

This software takes Live video as input and after internal processing and recognition/prediction provides the most probable output.

### * Software Requirements
        * Kivy 1.10.1
        * Tensorflow (version)
        * keras (version)
        * opencv (version)
        * python 2.7
   

### * Hardware Requirements 
        * Laptop or Desktop
        * Processor Clock Speed: 1.2GHz and above
        * RAM: 2GB and above
        * Camera/Web Camera 
     
### * Preliminary Product Description 

The final product is a software or an application or an interface to identify different gestures of English ASL at real time extracting the unique features of a frame extracted from a video using openCV and CNN. 

### * Conceptual Models

Diagram of our CNN model

# References
