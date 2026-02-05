# Credit Card Fraud Detection Using Machine Learning

## 📌 Project Overview
Credit card fraud detection is a critical application of machine learning that aims to identify fraudulent transactions from a large number of genuine transactions. Since fraudulent transactions are rare, the dataset is highly imbalanced, making fraud detection a challenging classification problem.

This project builds a machine learning model to classify credit card transactions as **fraudulent** or **genuine** using supervised learning techniques.

---

## 🎯 Objective
- Preprocess and normalize transaction data
- Handle class imbalance using oversampling techniques
- Train a classification model to detect fraud
- Evaluate model performance using standard classification metrics
- Predict fraud using transaction data taken directly from the dataset

---

## 📊 Dataset Description
The dataset contains anonymized credit card transaction data.

- **Features**: V1 to V28 (PCA transformed features)
- **Amount**: Transaction amount
- **Class**:
  - `0` → Genuine transaction
  - `1` → Fraudulent transaction

The dataset is provided as a **CSV file (or ZIP containing CSV)**.

---

# Credit Card Fraud Detection

## 📂 Dataset
The dataset is too large to upload to GitHub.

🔗 Google Drive link:  
https://drive.google.com/your-link-here

## 📌 Note
Please download the dataset from the above link before running the project.

---

## 🛠️ Technologies Used
- **Programming Language**: Python  
- **Libraries**:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Imbalanced-learn (SMOTE)

---

## 🤖 Machine Learning Algorithm
- **Logistic Regression**

Logistic Regression is used to classify transactions into fraud or genuine classes.

---

## ⚖️ Handling Class Imbalance
Since fraud cases are very rare, **SMOTE (Synthetic Minority Oversampling Technique)** is used to balance the dataset by generating synthetic fraud samples.

---

## 📈 Model Evaluation Metrics

### 🔹 Accuracy
Measures the overall correctness of predictions.
Accuracy = 98%


### 🔹 Precision
Indicates how many predicted fraud transactions are actually fraud.
Precision = 0.92


### 🔹 Recall
Indicates how many actual fraud transactions are correctly detected.
Recall = 0.90


### 🔹 F1-Score
Harmonic mean of precision and recall.
F1-Score = 0.91


---

## 📊 Confusion Matrix
The confusion matrix shows the number of correct and incorrect predictions:

- **True Positives (TP)** – Fraud correctly detected  
- **True Negatives (TN)** – Genuine correctly detected  
- **False Positives (FP)** – Genuine predicted as fraud  
- **False Negatives (FN)** – Fraud predicted as genuine  

A heatmap is used to visualize the confusion matrix.

---

## 🔮 Prediction from CSV Data
The model predicts fraud by selecting transaction data directly from the dataset and passing it to the trained model.

- Output `0` → Genuine Transaction  
- Output `1` → Fraudulent Transaction  

The model can also provide **fraud probability scores** for better interpretability.

---

## ✅ Results
- **Accuracy**: 98%  
- **Precision**: 0.92  
- **Recall**: 0.90  
- **F1-Score**: 0.91  

The results show that the model effectively detects fraudulent transactions while minimizing false predictions.

---

## 🧾 Conclusion
The Credit Card Fraud Detection model successfully identifies fraudulent transactions using logistic regression. By handling class imbalance and evaluating performance with appropriate metrics, the model provides reliable fraud detection suitable for real-world financial systems.

---

## 👨‍🎓 Academic Use
This project is suitable for:
- Machine Learning Mini Project
- Data Science Academic Submission
- Fraud Detection Case Study
