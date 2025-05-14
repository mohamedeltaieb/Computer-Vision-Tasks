Breast Cancer Classification with Decision Trees
Breast Cancer Classification

This project implements a Decision Tree classifier to predict whether a breast tumor is malignant or benign using the Wisconsin Breast Cancer Dataset. The model achieves 95% accuracy with clear interpretability of important features.

Table of Contents
Features

Dependencies

Model Details

Results

Visualizations

Feature Importance

License

Features
Loads and analyzes the Breast Cancer Wisconsin Diagnostic Dataset

Implements and visualizes a Decision Tree classifier

Includes hyperparameter tuning

Provides comprehensive evaluation metrics

Visualizes feature importance and decision paths

Dependencies
Python 3.7+

scikit-learn (pip install scikit-learn)

pandas (pip install pandas)

matplotlib (pip install matplotlib)


Model Details
Algorithm: Decision Tree Classifier

Default Parameters:

Random state: 42

Gini impurity for splitting

Tuned Parameters:

Max depth: 3

Min samples split: 5

Min samples leaf: 2

Results
The model achieves 95% accuracy on the test set:
Accuracy: 0.95

Classification Report:
              precision    recall  f1-score   support

   malignant       0.93      0.93      0.93        43
      benign       0.96      0.96      0.96        71

    accuracy                           0.95       114
   macro avg       0.94      0.94      0.94       114
weighted avg       0.95      0.95      0.95       114

Confusion Matrix:
[[40  3]
 [ 3 68]]


 Visualizations
Decision Tree Structure:

Full visualization of the decision paths

Color-coded by class
![image](https://github.com/user-attachments/assets/6aaa6e81-58c7-49fe-ac5a-be1575b6ca96)




Confusion Matrix:

Clear visualization of true/false positives/negatives
![image](https://github.com/user-attachments/assets/9b420d1b-97b5-4658-a0ee-3ef09be194aa)




Feature Importance
The top 10 most important features for classification:

Worst concave points

Worst perimeter

Worst radius

Worst area

Mean concave points

Worst concavity

Mean concavity

Mean perimeter

Mean radius

Mean area

Feature Importance
![image](https://github.com/user-attachments/assets/6e731607-e1c0-4f06-aafc-9715305c6cae)
