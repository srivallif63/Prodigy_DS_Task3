# 📊 Decision Tree Classifier – Bank Marketing

## 📌 Project Overview
This project builds a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit using bank marketing data.

## 📁 Dataset
- Bank Marketing Dataset
- CSV file (semicolon `;` separated)
- Target column: y
  - yes → 1
  - no → 0

## ⚙️ Steps
1. Loaded dataset using pandas
2. Cleaned column names
3. Converted target variable (y)
4. Applied one-hot encoding
5. Split data into train and test
6. Trained Decision Tree model
7. Made predictions
8. Calculated accuracy
9. Plotted decision tree

## 📈 Result
- Accuracy: ~80–90%
- Important features: duration, balance, age

## 🛠️ Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## ▶️ Run the Project

pip install pandas scikit-learn matplotlib
jupyter notebook TASK_03.ipynb

## 📂 Files

TASK_03.ipynb
bank.csv
README.md

## 📌 Conclusion
Decision Tree model successfully predicts customer subscription based on input features.
