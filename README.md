# 💳 Online Payment Fraud Detection

This project is focused on detecting fraudulent transactions in online payment systems using machine learning techniques. With the rapid growth of digital payments, identifying and preventing fraudulent activities has become increasingly important.

## 📁 Project Structure

- `onlinepaymentfraud.ipynb`: Jupyter Notebook containing the full workflow of the project — from data preprocessing to model training and evaluation.

## 🧠 Objectives

- Understand the nature of online payment fraud.
- Perform exploratory data analysis (EDA) on the dataset.
- Preprocess the data for machine learning.
- Train multiple machine learning models to detect fraud.
- Evaluate the performance of each model using classification metrics.

## 🗃️ Dataset

The dataset includes anonymized records of online transactions, with features such as:

- `step`: Time step at which the transaction occurred.
- `type`: Type of transaction (e.g., CASH_OUT, TRANSFER).
- `amount`, `oldbalanceOrg`, `newbalanceOrig`, etc.
- `isFraud`: Target variable indicating whether the transaction is fraudulent.

> Note: The dataset is assumed to be loaded within the notebook. If not, you may need to upload it separately.

## 🔧 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## ⚙️ Machine Learning Models

- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier

Each model is evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

## 📊 Results Summary

The notebook compares multiple models and discusses which one performs best for this specific fraud detection task. The focus is on minimizing false negatives — i.e., ensuring fraudulent transactions are not missed.

## 🚀 Getting Started

1. Clone this repository or download the notebook.
2. Open the notebook using Jupyter Notebook or any compatible IDE.
3. Run the cells step-by-step to follow the analysis and model training process.
4. Optionally, modify or extend the models for improved performance.

## 📌 Future Work

- Hyperparameter tuning
- Handling class imbalance using SMOTE or other techniques
- Real-time fraud detection implementation


