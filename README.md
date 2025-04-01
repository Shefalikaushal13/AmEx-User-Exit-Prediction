📌 Overview
This repository contains a Deep Learning model built to predict whether a customer will exit (churn) from American Express based on their transaction history and demographic data. 
The model uses an Artificial Neural Network (ANN) implemented with TensorFlow/Keras and achieves high accuracy in classifying potential churners.

📂 Dataset
The dataset (AmExUserExit.csv) contains customer attributes such as:
Credit Score
Geography (Country)
Gender
Age
Tenure
Balance
Estimated Salary
Exit Status (Target: 1 if exited, 0 if retained)

🛠️ Tech Stack
Python 3.8+
TensorFlow/Keras (for ANN)
Scikit-learn (for preprocessing & evaluation)
Pandas & NumPy (data manipulation)
Matplotlib (visualization)

🚀 Key Features
✅ Data Preprocessing
One-Hot Encoding for categorical features (Geography, Gender)
Feature scaling using MinMaxScaler
Train-test split (80-20)
✅ Deep Learning Model
3-layer Neural Network (128 → 64 → 32 neurons)
Dropout layers to prevent overfitting
Early Stopping to optimize training
✅ Performance Metrics
Accuracy: ~86%
Confusion Matrix Analysis

