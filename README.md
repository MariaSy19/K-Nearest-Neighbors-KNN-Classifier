# K-Nearest Neighbors (KNN) Classifier

This repository contains Python code for implementing the K-Nearest Neighbors (KNN) algorithm for classification on the Iris dataset. The code includes the implementation of KNN from scratch as well as using the scikit-learn library for comparison.

## Description

The KNN algorithm is a simple and intuitive method for classification. It classifies a data point by finding the majority class among its k nearest neighbors in the feature space. This implementation supports three distance measures: Euclidean distance, Manhattan distance, and Cosine similarity.

## Dataset

The Iris dataset is a classic dataset in machine learning and statistics. It contains measurements of iris flowers, including sepal length, sepal width, petal length, and petal width, along with the species of each iris. The dataset consists of 150 samples with 3 different species of iris flowers.

## Files

- `knn_classifier.py`: Python script containing the implementation of the KNN algorithm.
- `README.md`: Markdown file describing the project and providing instructions.
- `Iris.csv`: CSV file containing the Iris dataset.

## Dependencies

- Python 3.x
- pandas
- scikit-learn
- numpy
- matplotlib
- seaborn



   This will execute the KNN classifier on the Iris dataset, calculate the accuracy scores using different distance measures, and print the results.

## Results

The accuracy scores of the KNN classifier using different distance measures are as follows:

- Accuracy (Euclidean): 1.0
- Accuracy (Manhattan): 1.0
- Accuracy (Cosine): 0.9666666666666667

