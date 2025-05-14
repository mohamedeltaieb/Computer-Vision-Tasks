
Iris Dataset

This project implements a Multi-Layer Perceptron (MLP) neural network to classify iris flowers into three species using scikit-learn. The model achieves perfect 100% accuracy on the test set.

Table of Contents
Features

Dependencies

Model Architecture

Results

Visualization

License

Features
Loads and preprocesses the classic Iris dataset

Implements a neural network with 2 hidden layers

Includes data standardization

Provides classification metrics and visualizations

Dependencies
Python 3.7+

NumPy (pip install numpy)

pandas (pip install pandas)

scikit-learn (pip install scikit-learn)

Matplotlib (pip install matplotlib)


Model Architecture
The neural network has the following structure:

Input layer: 4 nodes (for the 4 iris features)

Hidden layers: 2 layers with 10 neurons each (ReLU activation)

Output layer: 3 nodes (Softmax for 3 classes)

Optimizer: Adam (learning rate=0.01)

Training: 500 maximum iterations

Results
The model achieves perfect classification:
Test Accuracy: 1.0000

Classification Report:
              precision    recall  f1-score   support

          0       1.00      1.00      1.00        10
          1       1.00      1.00      1.00         9
          2       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30




Visualization
The learning curve shows the model's loss decreasing over training iterations:
![image](https://github.com/user-attachments/assets/a520deaf-9840-467b-a194-6be33e0529b3)
