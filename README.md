📌 Overview<br>
This repository contains a Deep Learning model built to predict whether a customer will exit (churn) from American Express based on their transaction history and demographic data. 
The model uses an Artificial Neural Network (ANN) implemented with TensorFlow/Keras and achieves high accuracy in classifying potential churners.

📂 Dataset<br>
The dataset (AmExUserExit.csv) contains customer attributes such as:<br>
Credit Score<br>
Geography (State)<br>
Gender<br>
Age<br>
Tenure<br>
Balance<br>
Estimated Salary<br>
Exit Status (Target: 1 if exited, 0 if retained)<br>

🛠️ Tech Stack<br>
Python 3.8+<br>
TensorFlow/Keras (for ANN)<br>
Scikit-learn (for preprocessing & evaluation)<br>
Pandas & NumPy (data manipulation)<br>

🚀 Key Features<br>
✅ Data Preprocessing<br>
One-Hot Encoding for categorical features (Geography, Gender)<br>
Feature scaling<br>
Train-test split (80-20)<br>
✅ Deep Learning Model<br>
3-layer Neural Network (128 → 64 → 32 neurons)<br>
Dropout layers to prevent overfitting<br>
Early Stopping to optimize training<br>
✅ Performance Metrics<br>
Accuracy: ~86%<br>
Confusion Matrix Analysis<br>

