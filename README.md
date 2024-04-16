# Streetview-Digit-Recognition
![shvn](https://github.com/manoj2001ms/Streetview-Digit-Recognition/assets/142727610/34144c53-66e0-4548-94ee-8da7354ef1bf)

# Overview
Recognizing multi-digit numbers in photographs captured at street level is a crucial component of modern-day map making. This project focuses on transcribing address numbers from geo-located patches of pixels, particularly from Google's Street View imagery, to pinpoint building locations accurately. The task poses challenges due to variations in text appearance, environmental factors, and image acquisition issues.

# Problem Statement
The goal is to develop a neural network model capable of accurately transcribing address numbers from street-level images, leveraging the Street View House Numbers (SVHN) dataset. This involves recognizing and transcribing multi-digit numbers despite diverse fonts, colors, orientations, and environmental conditions.

# Data
[SVHN Dataset](https://drive.google.com/file/d/1Gybs-NV0KcBrpjT_Su5TtYfW924oipQA/view?usp=drive_link)
# Dataset Description
The SVHN dataset consists of real-world images obtained from Google Street View, with labels representing prominent numbers in each image. The dataset comes in h5py file format and presents a challenging real-world problem of recognizing digits and numbers in natural scene images.

# Model Training and Evaluation
Several neural network models were trained and evaluated on the SVHN dataset to accomplish the recognition task. Model performance was assessed based on accuracy metrics, with the second model demonstrating superior performance.

# Conclusion
The project successfully addressed the challenge of recognizing multi-digit numbers in street-level photographs using neural network models. Leveraging the SVHN dataset, the second neural network model achieved an accuracy of [77%], showcasing its effectiveness in transcribing address numbers accurately. The deployed model holds potential for enhancing map-making processes and advancing optical character recognition (OCR) and computer vision applications.

# Dependencies
Python 3.x
TensorFlow
Keras
h5py
