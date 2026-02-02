# E-Learning Dropout Detection

## 📌 Project Overview
This project aims to predict student dropout in an e-learning environment using Machine Learning techniques.  
By analyzing students’ activity logs, the system identifies learners at risk of dropping out to support early intervention.

---

## 🎯 Objectives
- Analyze student engagement in online learning platforms  
- Handle imbalanced dropout data  
- Build and compare multiple classification models  
- Identify students at risk of e-learning dropout  

---

## 📊 Dataset
- **OULAD – Open University Learning Analytics Dataset**
- Contains logs of student interactions, activity duration, and course information  
- Link: https://analyse.kmi.open.ac.uk/open_dataset

---

## 🧠 Machine Learning Models
- Logistic Regression (LR)  
- Random Forest (RF)  
- K-Nearest Neighbors (KNN)  

---

## ⚙️ Data Preprocessing
- Handling missing values in activity logs  
- Normalization of time-based features  
- Treatment of class imbalance (dropout as a minority class)  

---

## 📈 Evaluation
Models are evaluated using appropriate classification metrics to handle imbalanced data:
- Accuracy  
- Precision  
- Recall  
- F1-score  

---

## 🏆 Results
Random Forest showed better overall performance in identifying students at risk of dropout compared to other models.

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 🚀 How to Run the Project
```bash
pip install -r requirements.txt
