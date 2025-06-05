🕵️‍♂️ Fake Instagram Account Detector

A neural network-based system to detect fake Instagram accounts using structured data analysis and machine learning. This project leverages TensorFlow to train a custom classification model, with data preprocessing and analysis handled in Pandas, and clustering via KMeans to visualize latent feature groupings.

🚀 Overview

This project aims to automatically identify fake Instagram profiles based on profile attributes. It follows a full ML pipeline:

Feature Analysis: Using pandas, exploratory data analysis was done to understand which profile metrics matter most.

Normalization: Input features were normalized with StandardScaler to ensure uniform scale and faster convergence.

Model Building: A custom feedforward neural network was built using TensorFlow and Keras for binary classification (real vs fake).

Training Visualization: Plotted training and validation loss to monitor overfitting and model performance.

Feature Clustering: Applied KMeans on learned features to visualize natural clusters of real vs fake accounts.

🧠 Tech Stack

Python

TensorFlow / Keras

Pandas / NumPy

Scikit-learn

Matplotlib / Seaborn

📊 Sample Outputs
Training vs Validation Loss Graphs

KMeans Cluster Visualization of Feature Space
