---
title: "Real Time Sign Language Detection Using ESP32-CAM"
collection: teaching
type: "Computer Vision"
permalink: /teaching/project-17
venue: "Object Tracking"
date: 2024-12-12
location: "Shiraz, Iran"
---

This project focuses on real-time sign language detection, utilizing an ESP32-CAM board for video capturing. 

![image](/images/ESP32-CAM.jpg)

Two methods are implemented:

1.	NickNochnack’s Method: A custom dataset of 100 images (20 images per class) is created with five classes: “hello,” “welcome,” “to,” “my,” and “website.” I wrote a separate code for capturing and gathering this dataset using laptop's camera. This dataset is then used to train NickNochnack’s sign language detection model.
	2.	Daniel’s Tutorial: This method also uses a different custom dataset captured and gathered using a separate code. It focuses on detecting hands and fingers, followed by training the model to recognize numerical signs (0-9).

This project demonstrates a hardware-software integration for real-time gesture recognition and expands accessibility through sign language detection. The code and additional details can be found in the GitHub repository.


Note 1: I wrote code for capturing the dataset and used my laptop for gathering my dataset. It is possible to use your phone, directly use the ESP32-CAM, or any other method.

Note 2: For annotation, use Pascal VOC format. Otherwise, you need to modify a couple of lines in the code.


![gif](/images/Sign_language_1ms.gif)


**Link to the gihub repository:**

[Link](https://github.com/PouyaSonej/RealTime_SignLanguage_Detection.git)
