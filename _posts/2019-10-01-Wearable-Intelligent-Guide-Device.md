---
layout: post
title: 'Wearable Intelligent Guide Device'
date: 2019-10-01
author: Xinyang Huang
color: rgb(154,133,255)
cover: '../assets/guide_device1.JPG'
tags: Project
---

# A summary: Oct.2018 - Oct.2019

### Researcher and Team leader, Chengdu, China

Complete project: https://github.com/Huangxy-Minel/Wearable-Intelligent-Guide-Device

## Thermal Imaging Vision & Ultrasonic Obstacle Avoidance System

​	Designed Thermal Imaging Vision & Ultrasonic Obstacle Avoidance System, which recognized obstacle types through neural network algorithms, and measured distance to obstacles via the ultrasound system with accuracy 1 cm.  

​	The vision system uses Openmv, a lightweight vision module based on Python. Official Website is https://openmv.io/. We used it to implement image recognition, Apriltag positioning and other functions.

<img src="D:\Git\GitWorkspace\Huangxy-Minel.github.io\assets\img\openmv.jpg" alt="openmv" style="zoom:50%;" />

## GPS & Inertial Navigation & Vision Navigation System

​	Designed GPS & Inertial Navigation & Vision Navigation System, which realized navigation by calling navigation app software interface, and achieved accurate velocity measurement via EKF algorithm and Kalman filter. Indoor navigation system error can be ±50 cm without visual calibration and ±15 cm with visual calibration.

​	GPS navigation is already a very mature technology. Here we directly implement navigation through the Google Maps API. Compared with GPS, indoor positioning and navigation always have problems such as instability, position shift, and inability to eliminate errors. Therefore, the Kalman filter and visual positioning technology are introduced in the traditional inertial navigation mode.

![guide_device2](D:\Git\GitWorkspace\Huangxy-Minel.github.io\assets\img\guide_device2.jpg)

## 

## “Challenge Cup” Science and Technology Competition & "Internet +" Innovation Competition

​	From June to October 2019, we participated “Challenge Cup” Science and Technology Competition and "Internet +" Innovation Competition. The former is a technical competition, the latter is an entrepreneurial competition. After 4 months of struggle, although we have experienced many setbacks, we have also achieved good results in the end.

​	The picture below is a brochure we used for publicity at the time, designed by Wenjing Lu & Hang Lu.

![guide_device3](D:\Git\GitWorkspace\Huangxy-Minel.github.io\assets\img\guide_device3.png)![guide_device4](D:\Git\GitWorkspace\Huangxy-Minel.github.io\assets\img\guide_device4.png)



## Patent

​	A Wearable Intelligent Blind Guide Device (current status: Publication of invention patent application), Patent number: CN201910639192.3.

## Awards

​	The second prize in “Challenge Cup” Science and Technology Competition (Sichuan Division)(top %1)

​	The third prize in "Internet +" Innovation Competition (Sichuan Division) (top 3%)