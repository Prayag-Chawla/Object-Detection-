
## Sign Language Recognition with Advanced Computer Vision
Sign Language is a form of communication used primarily by people hard of hearing or deaf. This type of gesture-based language allows people to convey ideas and thoughts easily overcoming the barriers caused by difficulties from hearing issues.

an evident solution to this issue is present in the world of Machine Learning and Image Detection. Implementing predictive model technology to automatically classify Sign Language symbols can be used to create a form of real-time captioning for virtual conferences like Zoom meetings and other such things.

This project somehow didn't work in the real time system, so I developed  cnn model for the same, and used a pre defined dataset for the same.


 The topic is 
 ##  Building CNN Algorithm on American Sign Language Dataset

## Computer Vision
Computer vision is a field of computer science that focuses on enabling computers to identify and understand objects and people in images and videos. Like other types of AI, computer vision seeks to perform and automate tasks that replicate human capabilities.


## CNN
 In deep learning, a convolutional neural network (CNN/ConvNet) is a class of deep neural networks, most commonly applied to analyze visual imagery. Now when we think of a neural network we think about matrix multiplications but that is not the case with ConvNet. It uses a special technique called Convolution. Now in mathematics convolution is a mathematical operation on two functions that produces a third function that expresses how the shape of one is modified by the other.


Before we go to the working of CNN’s let’s cover the basics such as what is an image and how is it represented. An RGB image is nothing but a matrix of pixel values having three planes whereas a grayscale image is the same but it has a single plane. Take a look at this image to understand more.

RGB image | Computer vision | CNN
For simplicity, let’s stick with grayscale images as we try to understand how CNNs work.

Grayscale image | Computer vision | CNN
The above image shows what a convolution is. We take a filter/kernel(3×3 matrix) and apply it to the input image to get the convolved feature. This convolved feature is passed on to the next layer.

Convolution process in Convolutional Neural Networks
In the case of RGB color, channel take a look at this animation to understand its working

Working of ConvNet on RGB color images
Convolutional neural networks are composed of multiple layers of artificial neurons. Artificial neurons, a rough imitation of their biological counterparts, are mathematical functions that calculate the weighted sum of multiple inputs and outputs an activation value. When you input an image in a ConvNet, each layer generates several activation functions that are passed on to the next layer.

## OpenCV
OpenCV is a Python library that allows you to perform image processing and computer vision tasks. It provides a wide range of features, including object detection, face recognition, and tracking.


## Model used
Here we have used a sequentiol model for training and testing purposes.
## Libraries and Usage

```
import numpy as np 
import tensorflow as tf 
import random 
import os 
import string 
import pandas as pd 
%matplotlib inline
import matplotlib.pyplot as plt 
import seaborn as sns 
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))
```






## Accuracy






## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


## Used By
In the real world, object detection and sign language detectios in very crucial, and used by many companies in the industry.
## Appendix

A very crucial project in the realm of data science and computer vision using visualization techniques as well as machine learning modelling.

## Acknowledgements

The project is taken from
https://towardsdatascience.com/sign-language-recognition-with-advanced-computer-vision-7b74f20f3442
and 
https://www.kaggle.com/code/rasitacar/deeplearningcnnproject
## Tech Stack

**Client:** Python, Image Segmentation, computer vision, CMM, deep learnin, sequential model of ML



## Feedback

If you have any feedback, please reach out to us at chawlapc.619@gmail.com

