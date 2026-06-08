# OIBSIP_domain_taskno.1
# Iris Flower Classification using K-Nearest Neighbors (KNN)

## Project Overview

This project implements a Machine Learning classification model using the K-Nearest Neighbors (KNN) algorithm to classify Iris flowers into one of three species:

* Setosa
* Versicolor
* Virginica

The model is trained using the famous Iris dataset available in Scikit-Learn.

---

## Dataset Information

The Iris dataset contains 150 flower samples.

### Features

1. Sepal Length (cm)
2. Sepal Width (cm)
3. Petal Length (cm)
4. Petal Width (cm)

### Target Classes

| Class Number | Species    |
| ------------ | ---------- |
| 0            | Setosa     |
| 1            | Versicolor |
| 2            | Virginica  |

---

## Technologies Used

* Python
* Pandas
* Scikit-Learn
* Jupyter Notebook

---

## Machine Learning Algorithm

### K-Nearest Neighbors (KNN)

KNN is a supervised machine learning algorithm used for classification problems.

The algorithm classifies a new data point based on the majority class among its K nearest neighbors.

For this project:

* Algorithm: KNN Classifier
* Number of Neighbors (K): 3

---

## Project Workflow

1. Import Required Libraries
2. Load Iris Dataset
3. Create DataFrame
4. Separate Features and Target
5. Split Dataset into Training and Testing Sets
6. Train KNN Model
7. Predict Test Data
8. Calculate Accuracy
9. Predict New Flower Species

---

## Train-Test Split

The dataset is divided into:

* Training Data: 80%
* Testing Data: 20%

Random State Used:

42

---

## Model Training

The KNN model is trained using the training dataset:

model.fit(X_train, y_train)

The model learns patterns from flower measurements and their corresponding species.

---

## Model Evaluation

Accuracy is used to evaluate the model performance.

Accuracy Formula:

Accuracy = Correct Predictions / Total Predictions

Example Output:

Accuracy: 1.0

This indicates that the model correctly classified all testing samples.

---

## Sample Prediction

Input:

[5.1, 3.5, 1.4, 0.2]

Output:

Setosa

---

## Expected Output

Training Samples: 120

Testing Samples: 30

Accuracy: 1.0

Predicted Species: Setosa

---

## Advantages of KNN

* Easy to understand
* Simple implementation
* No training complexity
* Effective for small datasets

---

## Limitations of KNN

* Slower on large datasets
* Sensitive to irrelevant features
* Requires choosing an appropriate K value

---

## Conclusion

This project successfully classifies Iris flowers using the K-Nearest Neighbors (KNN) algorithm. The model achieves high accuracy and demonstrates the basic workflow of a supervised machine learning classification problem.
