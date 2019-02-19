# handsFreeKeyboard_CNN
Deep learning project on CNN Hand gesture classification.

Proposed Title of the Project(By Guide) - Communication System for audibly Disabled people

# Introduction 

## Background


We have come a long way from conventional image processing where we only performed mathematical functions on the pixels and their clusters but with the help of present day and computing power and capability we can make more sense and infer more about the images by the use of deep learning as we cultivate the pixels as huge tensors i.e multidimensional vectors and use a convolutional neural network (CNN) to map images to specific alphanumeric signs through which we achieve gesture control.

Gesture recognition is one
such topic that falls under computer vision that allows users to control and interact with any device without actually touching them.
We attempt at providing an efficient hand gesture recognition system where the users can tweak the real time processing according to their environment and use it accordingly.
This project focuses on implementing a real time application that recognizes 48 different gesture inputs which include English Alphabets(A
-Z), Numbers(0-9) and special characters like(',', space, new line,... etc) which inturn aids in the communication of people who are
audibly or vocally impaired acting as the medium of translation. Moreover the application also allows people to continously use it as a
real time keyboard without actual "Keys". The technology has vast areas in which it can be integrated seemlessly, viz. Security - encyption using gestures, 
Gaming - hands free control for more immersive experience, 
Medicine - generalised epileptic seizure detection,
etc but in this case we have devoted our research towards welfare of the specially abled exclusively the audibly and speech imapaired to aid their communication.
Given the fact this piece of software is driven only by mathematical algorithms without using much of external peripherals like kinect depth camera etc reduces the cost drastically and helps the application to reach a greater demographic as this requires only a basic camera either a webcam or an inbuilt camera.

## Objectives

We attempt at providing an efficient hand gesture recognition system where the users can calibrate the real time processing according to their environment and use it accordingly.
This project focuses on implementing a real time module that recognizes 48 different gesture inputs which include English Alphabets(A
-Z), Numbers(0-9) and special characters like(',', space, new line,... etc) which inturn aids in the communication of people who are
audibly or vocally impaired acting as the medium of translation. Moreover the application also allows people to continously use it as a
real time keyboard without actual "Keys".

## Purpose and Scope
### Purpose

We attempt at providing an efficient hand gesture recognition system where the users can tweak the real time processing according to their environment and use it accordingly.
This project focuses on implementing a real time application that recognizes 48 different gesture inputs which include English Alphabets(A
-Z), Numbers(0-9) and special characters like(',', space, new line,... etc) which inturn aids in the communication of people who are
audibly or vocally impaired acting as the medium of translation. Moreover the application also allows people to continously use it as a
real time keyboard without actual "Keys". 

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
