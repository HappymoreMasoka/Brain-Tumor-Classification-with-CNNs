🧠 Brain Tumor Classification with CNNs

This project applies Convolutional Neural Networks (CNNs) using TensorFlow/Keras to classify brain MRI scans into multiple categories (e.g., Glioma, Meningioma, Tumor, Healthy). The goal is to assist in early tumor detection and demonstrate the application of deep learning in healthcare.

📌 Project Overview

Objective: Build an image classification model to automatically detect and classify different types of brain tumors from MRI scans.

Dataset: Publicly available brain MRI dataset (e.g., Kaggle / open medical datasets).

Approach: A deep CNN trained with data augmentation, dropout, and softmax classification.

Use Case: Assists radiologists by providing a second-opinion diagnostic tool.

📊 Model Performance

Training Accuracy: ~98%

Validation Accuracy: ~96%

Epochs: 30

Batch Size: 32

Input Size: 256×256 RGB images

📈 Example Training Log:

Epoch 20/30
152/152 [==============================] - 72s 476ms/step - 
accuracy: 0.9897 - loss: 0.0338 - val_accuracy: 0.9697 - val_loss: 0.1423


⚙️ Tech Stack

Python 🐍

TensorFlow/Keras for deep learning

Matplotlib/Seaborn for visualization

NumPy & Pandas for data handling
