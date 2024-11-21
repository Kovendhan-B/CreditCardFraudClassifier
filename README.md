# Credit Card Genuine or Fraud Transaction Classifier

## Project Description
This project involves building a machine learning model to classify credit card transactions as genuine or fraudulent. Using historical transaction data, the model identifies patterns and anomalies to detect fraudulent activities. This solution helps financial institutions minimize fraudulent transactions and improve transaction security.

---

## Features
- Classification of transactions as **genuine** or **fraudulent**.
- Supports multiple machine learning algorithms for comparison.
- Data preprocessing, including handling of **imbalanced datasets** and **scaling**.
- **Hyperparameter tuning** for optimal model performance.
- **Cross-validation** for robust performance evaluation.

---

## Dataset
**Source**: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)

### Description
- The dataset contains anonymized credit card transactions over two days.
- Total transactions: **284,807**
- Features: **31**
  
### Class Distribution
- **Genuine Transactions**: 99.83%  
- **Fraudulent Transactions**: 0.17% (highly imbalanced dataset)

---

## Technologies Used

### Programming Language
- **Python**

### Libraries
- **Data Analysis**: `pandas`, `numpy`
- **Data Visualization**: `matplotlib`, `seaborn`
- **Machine Learning**: `scikit-learn`
- **Imbalanced Dataset Handling**: `imbalanced-learn`
- **Performance Metrics**: `scikit-learn.metrics`

---

## Steps
1. **Data Preprocessing**: Handle missing values, scale features, and address class imbalance.
2. **Model Building**: Experiment with various machine learning algorithms.
3. **Hyperparameter Tuning**: Optimize the model's parameters for best performance.
4. **Evaluation**: Use metrics like accuracy, precision, recall, F1-score, and AUC-ROC for robust performance evaluation.

---

## Outcomes
A machine learning solution capable of accurately classifying credit card transactions as genuine or fraudulent, aiding in fraud prevention and improving financial transaction security.

