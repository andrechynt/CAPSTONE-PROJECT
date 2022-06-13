# KulinerIN

<img src="https://github.com/mrafin/CAPSTONE-PROJECT/blob/main/MD/kulinerin/app/src/main/res/drawable/logo_kulinerin.png" width="250" height="250">

![GitHub contributors](https://img.shields.io/github/contributors/mrafin/CAPSTONE-PROJECT?color=%2342eff5&style=flat-square) ![GitHub forks](https://img.shields.io/github/forks/mrafin/CAPSTONE-PROJECT?color=%23000ce8&style=flat-square) ![GitHub issues](https://img.shields.io/github/issues/mrafin/CAPSTONE-PROJECT?color=%23f229d1&style=flat-square) ![GitHub all releases](https://img.shields.io/github/downloads/mrafin/CAPSTONE-PROJECT/total?color=%23ff8000&style=flat-square) ![GitHub pull requests](https://img.shields.io/github/issues-pr/mrafin/CAPSTONE-PROJECT?color=%23ff0000&style=flat-square)

# Table of Contents
1. [Project Description](#project-desc)
2. [Built With](#built-with)
3. [App Prerequisites](#app-prerequisites)
4. [How to Install App](#install)
5. [How to Use App](#use)
6. [Contributing](#contributing)
7. [Others](#others)
8. [Contact](#contact)
9. [License](#license)

# Project Description <a name="project-desc"></a>

On Boarding           |  Home Page          |  Prediction        | Detail
:-------------------------:|:-------------------------: |:-------------------------:|:-------------------------:
![](https://github.com/mrafin/CAPSTONE-PROJECT/blob/main/MD/Assets/onboard.png) | ![](https://github.com/mrafin/CAPSTONE-PROJECT/blob/main/MD/Assets/homePage.png) | ![](https://github.com/mrafin/CAPSTONE-PROJECT/blob/main/MD/Assets/result.png) | ![](https://github.com/mrafin/CAPSTONE-PROJECT/blob/main/MD/Assets/detail.png)



Hi, introduce **KulinerIN**, automatic Indonesian food detection application using image object detection.  This application is specifically intended to detect food image. **KulinerIN** comes to help to preserving Indonesian traditional food. With this app we hope tourist could get some help to recognizing food when they coming to vacation in Indonesia. Our Application also had some feature to recomend you to nearest restaurent from your location that integrate with google maps. **KulinerIN** if you want to know any food, you can take photo and analyze them.

# Built With <a name="built-with"></a>
- Android Studio [Jetpack MVVM Architecture](https://developer.android.com/jetpack/guide)
- Google Cloud Platform Services [GCP Console](https://console.cloud.google.com/home/dashboard?authuser=1&project=able-decorator-315006)

ML model built with framework and libraries :
- Google Colab
- python
- tensorflow
- matplotlib
- numpy
- object_detection
- [SSD MobileNet V2 FPNLite 320x320](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md)

# App Prerequisites <a name="app-prerequisites"></a>
- Android Version 9+
- Internet Connection

# You Can Replicate <a name="how-rep"></a>
Built Model :
- Download our dataset from our drive [Dataset](https://github.com/mrafin/CAPSTONE-PROJECT/tree/main/ML/Dataset)
- Install all framework and libraries that needed
- Run our model on your colab
- Download model saved_model that contain .pb file

Mobile Application Development :
- compileSdkVersion 32
- buildToolsVersion "32.0.0"

# How to Install App <a name="install"></a>
- Download apk from the [latest release](https://github.com/mrafin/CAPSTONE-PROJECT/blob/main/MD/kulinerin/app/release/app-release.apk)
- Enable install from unknown sources
- Install apk

# How to Use App <a name="use"></a>
- Open app
- Register account
- Login your account
- Add image or upload image
- Start predicting
- Showing result

# Contributing <a name="contributing"></a>
Pull requests are **welcome**. For major changes, please open an issue first to discuss what you would like to change. Next steps:
1. Fork the project repo on GitHub
2. Clone the project to your local machine
3. Commit changes to your own branch
4. Push your work back up to your fork
5. Submit pull request, so we can review your changes

Note : Please make sure to update tests as appropriate.

# Others <a name="others"></a>
- [Document Presentation](https://docs.google.com/presentation/d/17P2oUqvp4PCbyA4rk91go3KFv-uYluLv/edit?usp=sharing&ouid=116758418375247377982&rtpof=true&sd=true)
- [Video Presentation](https://youtu.be/Iz_Qe-HRBkQ)

# Contact <a name="contact"></a>
- Muhammad Rafi Nashrullah - muh.rafi.nash80@gmail.com
- Audynalia Kogitans - audynalia48@gmail.com
- Mochammad Andre Cahyanto - m.andrechynt@gmail.com
- Ardana Firmansyah - ardanafirmansyah@gmail.com
- Bayu Rizki Aufar - bayurizkiaufar@gmail.com
- Fhinka Hanifah - fhinkahanifah14@gmail.com

# License <a name="license"></a>
Copyright (c) 2022 Bangkit Academy led by Google, GoTo, & Traveloka
