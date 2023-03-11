# Python_SVM
Support Vector Machine(SVM)

<img align="centre" width="400" height="200" src="https://miro.medium.com/v2/resize:fit:1600/1*337BitR7IzplaesOIUaRDQ.png">

Support Vector Machine (SVM) is a machine learning algorithm used for classification and regression tasks. 
It works by finding a hyperplane that best separates the different classes in the input data. 
SVMs seek to find a decision boundary that separates the different classes with the largest possible margin. 
This decision boundary is defined by a hyperplane that maximizes the distance between the closest data points from each class. 
SVMs are able to handle non-linearly separable data by using a kernel trick, 
and they have several advantages including the ability to handle high-dimensional data and the ability to handle non-linearly separable data.

## SVM Algorithm

import pandas as pd

import numpy as np

import seaborn as sns

import matplotlib.pyplot as plt

%matplotlib inline


data = pd.read_csv('bc2.csv')

dataset = pd.DataFrame(data)

dataset.columns
