# KNN-classifier
Iris classification  using KNN

A machine learning project implementing the K-Nearest Neighbors (KNN) algorithm to classify Iris flowers into three species using the classic Iris dataset.

Dataset
Source: Scikit-learn's built-in load_iris() dataset

Features: 4 numerical attributes
Sepal Length (cm)
Sepal Width (cm)
Petal Length (cm)
Petal Width (cm)

Target: 3 Iris species
Setosa (0)
Versicolor (1)
Virginica (2)
First five rows of the data set:
   sepal length (cm)  sepal width (cm)  petal length (cm)  petal width (cm)  \
0                5.1               3.5                1.4               0.2   
1                4.9               3.0                1.4               0.2   
2                4.7               3.2                1.3               0.2   
3                4.6               3.1                1.5               0.2   
4                5.0               3.6                1.4               0.2   

   species  
0        0  
1        0  
2        0  
3        0  
4        0


Libraries
- pandas
- numpy
- matplotlib
- scikit-learn

Key Concepts
Data loading with sklearn.datasets
Train-test split (80/20)(train-75% / 80%, test-25% / 20% )
KNN classification with k=5 neighbors

Model evaluation metrics:
Model Evaluation
----------------
Accuracy: 1.0

Confusion Matrix:
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]

Classification Report:
              precision    recall  f1-score   support
      setosa       1.00      1.00      1.00        10
  versicolor       1.00      1.00      1.00         9
   virginica       1.00      1.00      1.00        11

New Flower Prediction-
Input: [[5.1, 3.5, 1.4, 0.2]]
Predicted Species: setosa
