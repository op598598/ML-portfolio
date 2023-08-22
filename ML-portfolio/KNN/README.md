

# K-NN
This repository contains a Python program that uses the K-Nearest Neighbors (K-NN) algorithm to predict whether a person will be diagnosed with diabetes or not. The program utilizes a dataset of 768 individuals who have been diagnosed with or without diabetes.

## Objective
The main objective of this program is to demonstrate how the K-NN algorithm can be applied to predict the likelihood of diabetes diagnosis based on certain characteristics of the individual.

## Libraries
The following Python libraries are used in this program:

- pandas: For data manipulation and analysis.
- numpy: For numerical operations.
- scikit-learn: A machine learning library that provides tools for data preprocessing, model building, and evaluation.
- K-NN Algorithm Explanation
- The K-NN algorithm is employed to predict the outcome. The key aspects of the K-NN algorithm include:
~~~
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.neighbors import KNeighborsClassifier
from sklearn.metrics import confusion_matrix
from sklearn.metrics import f1_score
from sklearn.metrics import accuracy_score
~~~
## Grouping items
K: The hyperparameter that represents the number of nearest neighbors considered for making predictions.
Data Pre-processing: Handling missing values, scaling attributes, and choosing appropriate hyperparameters.
Data Pre-processing
Values for certain attributes like 'Glucose' and 'Blood Pressure' cannot be accepted as zeros. To address this, the program replaces these zeros with the mean of the respective column values.

## Dataset Overview
The dataset consists of the following columns:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (1 if diagnosed with diabetes, 0 otherwise)
## Model Building
Splitting the Dataset: The dataset is split into training and testing subsets using the train_test_split function from scikit-learn.
Attribute Scaling: Standardization is applied to scale the attributes between -1 and 1 using the StandardScaler.
Determine the K Value: The value of 'K' is determined based on the square root of the length of the testing set.
## Model Evaluation
The program evaluates the K-NN model using the following metrics:

Confusion Matrix: A table that evaluates the model's performance on the testing data.
F1-Score: A metric that considers both precision and recall to measure the model's accuracy.
The confusion matrix provides insights into:

True Positives (TP): Correctly predicted positive instances.
False Positives (FP): Instances incorrectly predicted as positive.
True Negatives (TN): Correctly predicted negative instances.
False Negatives (FN): Instances incorrectly predicted as negative.

## License
MIT License

Copyright (c) 2023 CAPSLOCKDIED

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Credits
I would like to credit Jupiter notebook, due to it being the primary coding space for this project.

## Contact
If you have any questions, queries or quandrums, please do not hesitate to contact me at: oliver.pracy@cgs.act.edu.au, or op598598@gmail.com

## Badges
![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)
![Wikipedia](https://img.shields.io/badge/Wikipedia-%23000000.svg?style=for-the-badge&logo=wikipedia&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Spotify](https://img.shields.io/badge/Spotify-1ED760?style=for-the-badge&logo=spotify&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
