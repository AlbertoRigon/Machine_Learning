# Machine Learning

This repository contains all the four homeworks completed for the Machine Learning 2020/2021 course attended at Università degli Studi di Padova.

## Classification on Wine Dataset
In this homework, we will be working with a dataset on wines from the [*UCI machine learning repository*](http://archive.ics.uci.edu/ml/datasets/Wine). It contains data for 178 instances. The dataset is the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines. We are going to perform binary classification and logistic regression tasks.

## Neural Networks for Classification
In this homework we are going to explore the use of Neural Networks for image classification. We are going to use a dataset of small images of clothes and accessories, the *Fashion MNIST*. You can find more information regarding the dataset [here](https://pravarmahajan.github.io/fashion/). Each instance in the dataset consist of an image, in a format similar to the digit images you have seen in the previous homework, and a label.

## SVM for classification
In this notebook we are going to explore the use of Support Vector Machines (**SVM**) for image classification. We are going to use the famous *MNIST* dataset, that is a dataset of handwritten digits. We get the data from *mldata.org*, that is a public repository for machine learning data. The dataset consists of 70,000 images of handwritten digits (i.e., 0, 1, ... 9). Each image is 28 pixels by 28 pixels and we can think of it as a vector of 28 x 28 = 784 numbers. Each number is an integer between 0 and 255. For each image we have the corresponding label (i.e., 0, 1, ..., 9).

## Regression
We consider a [dataset](https://www.kaggle.com/harlfoxem/housesalesprediction) containing house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015. For each house we know 18 house features (e.g., number of bedrooms, number of bathrooms, etc.) plus its price, that is what we would like to predict.
The price will be regressed using several different methods:
- **k-Nearest Neighbours**
- **Clustering and "Local" Linear Models** (clustering to identify groups of similar instances, and then linear models that are specific to each cluster)
- **Clustering and "Local" NNs** (same as above, but with neural networks instead of linear models)
