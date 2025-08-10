# BreastCancerDetection_ANN
Breast Cancer Detection using Neural Networks
This project implements a deep learning model in TensorFlow/Keras to classify breast cancer tumors as malignant or benign using the Breast Cancer Wisconsin Diagnostic Dataset from sklearn.datasets.

Model Architecture
Input Layer: 30 numerical features (e.g., radius, texture, perimeter, area, smoothness, etc.)

Dense Layer (64 units, ReLU activation) with L1 regularization (0.001)

Batch Normalization for faster and more stable training

Dropout (0.3) to prevent overfitting

Dense Layer (32 units, ReLU activation) with L1 regularization (0.001)

Batch Normalization

Dropout (0.3)

Output Layer (1 unit, Sigmoid activation) for binary classification

Training Details
Loss Function: binary_crossentropy

Optimizer: Adam (default settings)

Evaluation Metric: Accuracy

Train/Test Split: Standard 80/20 split

Results
Test Accuracy: 97.3%

The model generalizes well with low overfitting, thanks to regularization and dropout layers.

