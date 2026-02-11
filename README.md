📖 Project Overview

This project focuses on building and comparing multiple machine learning models for Fraud Detection. The objective is to identify fraudulent transactions accurately by evaluating different classification algorithms and selecting the best-performing model based on business requirements.

🎯 Objectives
Apply necessary preprocessing steps.
Use the same train-test split for all models.
Train multiple classification models.
Compare model performance using evaluation metrics.
Identify the best generalizing model.
Save the best model for deployment.

📂 Dataset
File Used: Fraud dataset.csv
Target Variable: Last column in the dataset
Type: Binary Classification (Fraud / Not Fraud)

🛠 Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Joblib

🔄 Project Workflow
1️⃣ Data Preprocessing
Removed duplicate records.
Separated features (X) and target (y).
Applied StandardScaler for feature scaling.
Used stratified train-test split (80% train, 20% test).

2️⃣ Models Trained
The following models were trained and evaluated:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Linear Support Vector Machine (SVM)
Class imbalance was handled using:
class_weight='balanced'

📊 Evaluation Metrics
Each model was evaluated using:
Accuracy
Precision
Recall
F1-Score
Train vs Test Accuracy (for generalization check)
A comparison table and bar chart were generated to visualize performance.

📈 Deliverables
✅ 1. Model Comparison Table
A Pandas DataFrame containing:
Train Accuracy
Test Accuracy
Accuracy
Precision
Recall
F1-Score

✅ 2. Performance Comparison Plot
Bar chart comparing:
Accuracy
Precision
Recall
F1-Score

✅ 3. Best Model Saved
The best-performing model (based on F1-Score) was saved as:
best_fraud_model.pkl

🏆 Model Selection Criteria
Since Fraud Detection is a highly imbalanced problem:
Accuracy alone is not reliable.
Recall is important (to catch fraud cases).
F1-Score provides balanced performance.
The model with the highest F1-Score was selected as the best model.

🚀 How to Run the Project
Upload the dataset to Google Colab.
Run all cells in the notebook.
View comparison table and plot.
Download the saved model file.

📌 Business Insight
For fraud detection systems:
High Recall → Fewer fraud cases missed.
High Precision → Fewer false fraud alerts.
Balanced F1-score → Practical real-world deployment.

📁 Output Files
best_fraud_model.pkl
Model comparison table (displayed)
Performance comparison chart (displayed)

👨‍💻 Author
Inzamam Mohd
Machine Learning Project – Fraud Detection Model Comparison
