Bank Customer Churn Prediction Using Artificial Neural Network (ANN)
Project Overview

This project predicts whether a bank customer is likely to leave (churn) or remain with the bank using an Artificial Neural Network (ANN) built with TensorFlow and Keras.

Customer churn prediction is a critical business problem in the banking sector. By identifying customers at risk of leaving, banks can take proactive measures to improve customer retention and reduce revenue loss.

This project demonstrates the complete deep learning workflow including data preprocessing, feature engineering, ANN model development, training, evaluation, and prediction.

Dataset

The project uses the Bank Customer Churn Prediction dataset from Kaggle.

Features
Credit Score
Country
Gender
Age
Tenure
Balance
Number of Products
Credit Card Status
Active Member Status
Estimated Salary
Target Variable
Churn (0 = Customer Stays, 1 = Customer Leaves)
Technologies Used
Python
Pandas
NumPy
Scikit-Learn
TensorFlow
Keras
Matplotlib
Project Workflow
Data Preprocessing
Data Loading
Missing Value Analysis
Categorical Feature Encoding
Feature Scaling using StandardScaler
Train-Test Split
Model Development
Artificial Neural Network (ANN)
Hidden Layer 1: 16 Neurons with ReLU Activation
Hidden Layer 2: 8 Neurons with ReLU Activation
Output Layer: 1 Neuron with Sigmoid Activation
Model Evaluation
Accuracy Score
Confusion Matrix
Classification Report
Churn Prediction
ANN Architecture
Input Layer
      ↓
Dense Layer (16 Neurons, ReLU)
      ↓
Dense Layer (8 Neurons, ReLU)
      ↓
Output Layer (1 Neuron, Sigmoid)
      ↓
Customer Churn Prediction
Results

The model achieved approximately 84%–88% accuracy on the test dataset.

Key evaluation metrics:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix
Learning Outcomes

Through this project, I gained hands-on experience in:

Artificial Neural Networks (ANN)
Deep Learning Fundamentals
Forward Propagation
Backpropagation
Activation Functions
Binary Classification
Model Evaluation Techniques
TensorFlow and Keras
Future Enhancements
Hyperparameter Tuning
Dropout Regularization
Early Stopping
Cross Validation
Model Deployment using Flask/FastAPI
Comparison with Machine Learning Models
