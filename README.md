# Gene-Sequence-Classification

### Overview
The aim of the code is to preprocess promoter gene sequence data and evaluate the performance of multiple machine learning models in classifying the sequences. It achieves this by converting sequences into numerical data, applying various classification algorithms, performing cross-validation, and comparing the models' performance based on accuracy and classification metrics. This approach ensures a robust and comprehensive evaluation of different machine learning techniques on the dataset.

### Data Source
The dataset used for this analysis was sourced from the Machine Learning Repository at the UCI

### Tools
-Google Colab [Download here](https://colab.research.google.com/)

### Data Cleaning/Preparation

### Exploratory Data Analysis

### Data Analysis
~~~ Python
import sys
import numpy as np
import matplotlib as mpl
import matplotlib.pyplot as plt
import seaborn as sns
import pandas as pd
import sklearn

plt.rcParams['figure.figsize'] = (8, 8)

