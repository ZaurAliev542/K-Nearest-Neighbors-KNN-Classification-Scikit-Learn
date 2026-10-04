# K-Nearest-Neighbors-KNN-Classification-Scikit-Learn
A practical implementation of the K-Nearest Neighbors (KNN) classification algorithm using the Breast Cancer Wisconsin dataset from Scikit-Learn, including feature scaling, model evaluation, hyperparameter tuning, and selection of the optimal K value.
# K-Nearest Neighbors (KNN) Classification

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm for binary classification using the **Breast Cancer Wisconsin dataset** provided by Scikit-Learn.

## Topics Covered

* Loading and exploring the dataset
* Feature-target separation
* Train-test split
* Feature standardization using `StandardScaler`
* KNN classification with `KNeighborsClassifier`
* Model prediction and evaluation
* Accuracy, confusion matrix, and classification report
* Testing different values of `K`
* Selecting the optimal `K`
* Final KNN model evaluation

## Technologies

* Python
* NumPy
* Pandas
* Scikit-Learn
* Matplotlib

## Dataset

The Breast Cancer Wisconsin dataset contains **569 observations and 30 numerical features**. The target variable represents two classes:

* `0` — Malignant
* `1` — Benign

## Key Concept

KNN classifies a new observation based on the classes of its nearest neighboring observations. Since KNN is distance-based, **feature scaling is an important preprocessing step**.

## Main Workflow

`Dataset → Train/Test Split → Standardization → KNN → Prediction → Evaluation → K Selection → Final Model`

This project is part of my ongoing **Machine Learning study and practical implementation portfolio**.
