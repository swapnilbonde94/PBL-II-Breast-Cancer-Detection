# PBL-II-Project

# Breast Cancer Detection using Machine Learning Algorithms

This repository contains the code and resources for breast cancer detection project using various machine learning algorithms. The goal of this project is to develop a reliable and accurate system for early detection of breast cancer, which can help in improving survival rates and providing timely treatment to patients.
This project was a part of Project Based Learning II, a subject in Sem 4 of SPPU Computer Engineering.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Algorithms](#algorithms)
- [Results](#results)
- [GUI](#GUI)
- [Contributing](#contributing)

## Introduction

Breast cancer is one of the most common forms of cancer affecting women worldwide. Early detection plays a crucial role in successful treatment. This project aims to utilize machine learning algorithms to build a model that can accurately classify breast tumors as malignant or benign based on various features extracted from medical images.

## Dataset

The dataset used for this project is the Breast Cancer Wisconsin (Diagnostic) dataset, available from the UCI Machine Learning Repository. It consists of 569 samples with 30 features, including attributes such as radius, texture, smoothness, symmetry, and more. Each sample is labeled as either malignant (cancerous) or benign (non-cancerous).

## Features

The dataset contains the following features:

1. Radius
2. Texture
3. Perimeter
4. Area
5. Smoothness
6. Compactness
7. Concavity
8. Concave points
9. Symmetry
10. Fractal dimension
...and more.

## Algorithms

In this project, we have implemented the following machine learning algorithms for breast cancer detection:

1. Logistic Regression 
2. Decision tree Classifier 
3. Random forest Classifier 
4. k-Nearest Neighbor Classifier(kNN)
5. Support Vector Machine Classifier(SVM)

These algorithms have been chosen due to their proven effectiveness in classification tasks and their ability to handle both linear and non-linear relationships in the data.

## Results

The performance of each algorithm on the breast cancer detection task was evaluated using various metrics such as accuracy, precision, recall, and F1 score. The results achieved by each algorithm are summarized below:

| Algorithm          | Accuracy | Precision | Recall | F1 Score |
| ------------------ | -------- | --------- | ------ | -------- |
| Logistic Regression| 0.96     | 0.93      | 0.95   | 0.94     |
| Decision Tree      | 0.94     | 0.95      | 0.97   | 0.96     |
| Random Forest      | 0.95     | 0.97      | 0.99   | 0.98     |
| KNN                | 0.93     | 0.92      | 0.95   | 0.93     |
| SVM                | 0.98     | 0.96      | 0.98   | 0.97     |

These results demonstrate the effectiveness of the implemented algorithms in accurately detecting breast cancer based on the provided features.

## GUI
We had created a webpage(only front-end) to display the workflow and results of our project at the time of presenting it.

## Contribution 

Contributions are welcome! If you have any ideas, improvements, or bug fixes, please open an issue or submit a pull request.
