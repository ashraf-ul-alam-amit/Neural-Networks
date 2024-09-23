# Implementation and Analysis of Neural Networks for Liver Disease Diagnosis

This repository contains the implementation and analysis of various neural networks and machine learning algorithms developed from ***scratch*** to gain a deeper understanding of how these models function. The project focuses on classifying liver disease using the Indian Liver Patient Dataset and explores a variety of learning techniques, neural network architectures, and methods to optimize weight adaptation for enhanced performance. Additionally, an Exploratory Data Analysis (EDA) was conducted to better understand the dataset prior to model building.

> **📝 Note:** Detailed reports and code for each algorithm have been included, where you can explore the analysis, findings, and the implementation of the algorithms.

## Algorithms Implemented

### 1. K-Nearest Neighbors (KNN)
- Implemented KNN for classification based on Euclidean distance.

### 2. Single Layer Perceptron
- Implemented with three different weight adaptation methods:
  1. **Basic Weight Adaptation**
  2. **Learning Rate-Adjusted Weight Adaptation**
  3. **Widrow-Hoff Delta Rule**

### 3. Multi-Layer Perceptron (MLP)
- Implemented with:
  - **ReLU Activation Function**
  - **Sigmoid Activation Function**
- Compared the MLP performance with a Dense Layer of a Convolutional Neural Network (CNN).

### 4. Kohonen Self-Organizing Map (SOM)
- Implemented SOM to visualize the clustering patterns in the liver disease dataset.

### 5. Hopfield Neural Network
- Implemented Hopfield networks to test pattern recall.

## Dataset

The dataset used in this project is the **[Indian Liver Patient Dataset](https://www.kaggle.com/datasets/uciml/indian-liver-patient-records)**, which is available as `indian liver patient.csv`. It contains medical records of 583 patients, with 10 features and 1 target variable. The target variable indicates whether the patient has a liver disease or not.

- **Age**: Integer representing the patient's age.
- **Gender**: Categorical feature (0 for female, 1 for male).
- **Total Bilirubin, Direct Bilirubin, Alkaline Phosphatase, Alamine Aminotransferase, Aspartate Aminotransferase**: Numeric liver measurements.
- **Total Proteins, Albumin, Albumin and Globulin Ratio**: Numeric values indicating various protein levels in the body.
- **Dataset**: Target variable (1 for liver disease, 2 for no liver disease).
