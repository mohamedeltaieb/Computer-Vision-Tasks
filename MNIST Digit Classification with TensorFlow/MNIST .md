MNIST Digit Classification with TensorFlow/Keras
A neural network model for classifying handwritten digits from the MNIST dataset.

📌 Overview
This project implements a deep learning model using TensorFlow/Keras to classify handwritten digits (0-9) from the famous MNIST dataset. The model achieves 98.11% test accuracy using a fully connected neural network with regularization and dropout to prevent overfitting.

🛠️ Dependencies
Python 3.8+

TensorFlow (pip install tensorflow)

NumPy (pip install numpy)

scikit-learn (pip install scikit-learn)
🧠 Model Architecture
The model consists of:

Input Layer: Flattens the 28×28 MNIST images into a 1D vector.

Hidden Layers:

Dense (256 neurons, ReLU, L2 regularization)

Dropout (50%)

Dense (128 neurons, ReLU, L2 regularization)

Dropout (30%)

Dense (64 neurons, ReLU, L2 regularization)

Output Layer: Dense (10 neurons, Softmax for classification)

Optimization & Training
Optimizer: Adam (lr=1e-3)

Loss: sparse_categorical_crossentropy

Callbacks:

EarlyStopping (patience=5)

ReduceLROnPlateau (factor=0.5, patience=3)

📊 Results
Test Accuracy: 98.11%

Training logs (accuracy/loss over epochs) can be visualized using matplotlib (example code not included here).

🔄 Possible Improvements
Use Convolutional Neural Networks (CNNs) for better accuracy.

Experiment with data augmentation to improve generalization.

Try different optimizers (e.g., RMSprop, SGD with momentum).

Deploy as a web app using Flask/FastAPI.
