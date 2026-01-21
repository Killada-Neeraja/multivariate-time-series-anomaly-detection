# Multivariate Time-Series Anomaly Detection

This project implements anomaly detection on multivariate equipment sensor data using both classical machine learning and deep learning techniques.

## Methods Used
- Isolation Forest for unsupervised anomaly detection
- LSTM Autoencoder for sequence-based anomaly detection
- Time-series feature extraction using tsfresh

## Workflow
1. Data preprocessing and normalization
2. Feature extraction using tsfresh
3. Anomaly detection with Isolation Forest
4. Temporal anomaly detection using LSTM Autoencoder
5. Evaluation using classification metrics and visualization

## Tools & Technologies
- Python
- pandas, NumPy
- scikit-learn
- tsfresh
- TensorFlow / Keras
- Jupyter Notebook

## Results
The LSTM Autoencoder significantly outperformed Isolation Forest by capturing temporal dependencies in sensor data and detecting anomalous behavior with high accuracy.

## Note
The dataset is not included in this repository.
The dataset used in this project was sourced from Kaggle and contains multivariate equipment sensor readings.
The dataset is not included in this repository to keep the project lightweight and focused on modeling.
