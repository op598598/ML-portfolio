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
Specify the project's license for usage and distribution.

## Credits
Acknowledgements for external libraries, tools, or resources used in the 
project.

## Contact
Ways to get in touch with you or the maintainers.

## Badges
Showcase project status, like build, coverage, or license badges.

## Changelog
Version history and changes made in each release.

## Getting Started
Quick guide for new users to get started with the project.

## Troubleshooting
Common issues users might encounter and their solutions.

## Examples
Additional usage examples or use cases.
