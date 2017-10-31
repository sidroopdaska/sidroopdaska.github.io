---
layout: post
title:  "Self Driving RC Car"
imgsrc: ../assets/portfolio/selfDrivingRCCar.jpg
github: https://github.com/sidroopdaska/SelfDrivingRCCar
youtube: https://www.youtube.com/watch?v=8V3rm8NNSXQ&feature=youtu.be
categories: ["portfolio"]
---
A scaled down version of self-driving system using Neural Networks and OpenCV. The system comprises of:
* Raspberry Pi with a camera and an ultrasonic sensor as inputs,
* Server that handles:
    * Steering using NN predictions
    * Stop sign and traffic light detection using Haar feature based Cascade Classifiers
    * Distance measurement through monocular vision
    * Front collision avoidance using an ultrasonic sensor
* an Arduino board for RC car control
