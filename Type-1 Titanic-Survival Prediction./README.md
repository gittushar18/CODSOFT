# Titanic Survival Prediction using Machine Learning

## 📌 Project Overview
This project uses the Titanic dataset to build a machine learning model that predicts whether a passenger survived the Titanic disaster.  
It is a classic beginner-friendly classification problem that demonstrates the complete machine learning workflow.

---

## 📊 Dataset Description
The dataset contains information about individual passengers, including:

- Passenger Class (Pclass)
- Gender (Sex)
- Age
- Number of siblings/spouses aboard (SibSp)
- Number of parents/children aboard (Parch)
- Fare
- Port of Embarkation (Embarked)
- Survival status (Target variable)

Target Variable:
- **Survived** → 0 = Did not survive, 1 = Survived

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🔧 Data Preprocessing
The following preprocessing steps were performed:

- Handled missing values in Age and Embarked columns
- Removed irrelevant features (Name, Ticket, Cabin, PassengerId)
- Converted categorical variables into numerical form
- Created new features such as:
  - FamilySize
  - IsAlone

---

## 🧠 Model Used
- **Random Forest Classifier**

Reasons for choosing Random Forest:
- Handles non-linear relationships effectively
- Reduces overfitting using ensemble learning
- Performs well on structured tabular data

---

## 📈 Model Evaluation
- The dataset was split into training and testing sets (80:20)
- Model performance was evaluated using:
  - Accuracy
  - Confusion Matrix
  - Classification Report

**Accuracy achieved:** ~84–86%

---

## 📊 Confusion Matrix
The confusion matrix was used to analyze correct and incorrect predictions made by the model, helping to understand false positives and false negatives.

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:pip install pandas numpy scikit-learn matplotlib seaborn
3. Place `train.csv` in the project directory
4. Run the Python script:codsoft1.ipynb

---

## 📌 Results & Insights
- Female passengers had higher survival rates
- Passengers in higher classes were more likely to survive
- Fare and age played a significant role in survival prediction

---

## 📚 Conclusion
This project demonstrates a complete end-to-end machine learning pipeline, making it an excellent beginner project for learning classification techniques and data preprocessing.

---

## ✨ Future Improvements
- Hyperparameter tuning
- Cross-validation
- Use of advanced models like XGBoost
- Feature scaling and selection

---

## 👤 Author
Tushar Sahu
---

## 📜 License
This project is for educational purposes only.
