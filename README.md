# Bioscience Research - Neuron Groups

### Year : 2022

![360_F_53460968_1qqGtMbrEELFsW9wlFnM3ZUGkDaOJOHB](https://github.com/sarveshsn/Bioscience-Research-Neuron-Groups/assets/93898181/7246ca63-8676-4c64-be09-5d929146395d)


## Introduction

This project explores the analysis and comparison of neuron groups using Python. The dataset consists of morphological measurements for different neuron groups, and we aim to investigate various aspects with help of  data exploration, statistical analysis, predictive modeling, and clustering.

## Getting Started

### Prerequisites

Before running the code, make sure you have the following libraries installed:

- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scipy](https://www.scipy.org/)
- [scikit-learn](https://scikit-learn.org/stable/)

You can install these libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn
```

## Dataset

The dataset used in this project is stored in CSV files:

    neurons_group_1.csv
    neurons_group_2.csv
    neurons_additional_measurements.csv

These files contain information about different measurements of neuron groups.
Project Overview

## This project is divided into several sections:

### Data Loading and Inspection

We start by loading the datasets into Python using pandas and inspecting the data. We determine the number of neurons, the number of different measurements, and check for missing values.

### Exploratory Data Analysis (EDA)

We perform exploratory data analysis to create both numerical and graphical summaries of the data. This includes generating box plots and correlation matrices to understand the relationships between different measurements.

### Hypothesis Testing

We conduct two-tailed t-tests to test whether neuron properties differ between group 1 and group 2. We use a significance level of α = 0.01 and examine properties such as average diameter, overall depth, overall height, and more.

### Data Merging

We merge the neuron group data with additional measurements data using pandas. We also handle missing values by filling them with the mean of the remaining values.

### Predictive Modeling

We build a linear regression model to predict the total surface area of a neuron using the remaining morphological measurements as predictor variables. We also perform forward selection using Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC) and compare the models.

### Random Forest Regression

We implement a Random Forest Regression model to predict the total surface area of a neuron using the remaining morphological measurements as predictor variables. We split the data into training and test sets and assess the model's performance using various metrics.

### Model Performance

We assess the Random Forest Regression model's performance with different numbers of trees and repeat the model fit and prediction multiple times for each number of trees. We visualize the mean squared error (MSE) as the number of trees varies.
### Clustering Analysis

We perform K-means clustering analysis using the morphological measurements as features. We identify the optimal number of clusters using the elbow method and then run K-means with the optimal number of clusters. We also identify the most discriminatory variables for each cluster.
### Visualization

We create scatter plots for the most discriminatory variables, coloring the points by cluster number to visualize the distinct properties of different neuron types.

### Results and Conclusions

The project provides comprehensive insights into neuron group analysis, including statistical analysis, predictive modeling, and clustering. We have identified discriminatory variables and visualized the distinct properties of different neuron types.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

    Thanks to the authors of the datasets used in this project.
    Special thanks to the Python and data analysis communities for their valuable resources and libraries.

## License
This project is open-source and available under the [MIT License](LICENSE).

---

**Author:** Sarvesh Sairam Naik  
**GitHub Repository:** [GitHub Link](https://github.com/sarveshsn)
