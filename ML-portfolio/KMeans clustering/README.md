# KMeans clustering
This project is an unsupervised learning algorithm that aims to minimise the sum of squared distances between datapoints, in order to cluster them with similar pieces of data.

## Installation
There are a number of libraries that this project uses, most of which can simply be imported, however some may need to be pip installed, depending on if you have installed them for similar projects in the past (if you are unsure how to do this, please view a website such as this one: https://python.land/virtual-environments/installing-packages-with-pip)
The libraries that need to be installed are:
-numpy
-pandas
-matplotlib
-sklearn
-sklearn.pmetrics
```
# Libraries
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from matplotlib import rcParams

import sklearn
from sklearn.cluster import KMeans
from mpl_toolkits.mplot3d import Axes3D
from sklearn.preprocessing import scale

import sklearn.metrics as am
from sklearn import datasets
from sklearn.metrics import confusion_matrix,classification_report
```

## Usage
To use this project, please create your own dataset or use the one provided. Then, set the number of clusters you want (see below) in the variable 'n_clusters'. The program will then put your data into a graph, while also predicting future datasets, after it has
been trained on you data input.

![image](https://github.com/op598598/ML-portfolio/assets/67995732/75626a58-a807-4e43-b133-80d3cff25b35)


## Configuration
All the configuring that is required for this project is setting the number of cluster that you want (see the usage heading), then creating your own data set.

## Features

K-Means seeks to minimize the total squared distances between data points and the centroids they are assigned to within a cluster. This process iteratively enhances clusters in each step, forming tighter and more unified groupings of data points.

## Documentation
For a more in depth look at KMeans and Machine Learning in general, please view the following sources:
- wikipedia: https://en.wikipedia.org/wiki/K-means_clustering#:~:text=k%2Dmeans%20clustering%20is%20a,a%20prototype%20of%20the%20cluster.
- medium: https://towardsdatascience.com/understanding-k-means-clustering-in-machine-learning-6a6e67336aa1

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
