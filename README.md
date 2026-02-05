E-Learning Dropout Detection using Machine Learning
📌 Project Overview

This project focuses on predicting student dropout in an e-learning environment using Machine Learning techniques.
By analyzing students’ engagement and activity logs, the system aims to identify learners at risk of dropping out in order to support early intervention and academic success.

 Objectives

Analyze student engagement in online learning platforms

Handle missing and noisy data from activity logs

Address class imbalance where dropout students are underrepresented

Build and compare multiple classification models

Identify students at risk of e-learning dropout

 Dataset

OULAD – Open University Learning Analytics Dataset

Contains:

Student interaction logs

Activity duration

Course and assessment information

 Dataset source:
https://analyse.kmi.open.ac.uk/open_dataset

 Data Preprocessing

The following preprocessing steps were applied:

Handling missing values in activity logs

Feature scaling and normalization of time-based features

Treatment of class imbalance using appropriate techniques

Data splitting into training and testing sets

🧠 Machine Learning Models

The following classification models were implemented and compared:

Logistic Regression (LR)

Random Forest (RF)

K-Nearest Neighbors (KNN)

 Evaluation Metrics

Given the imbalanced nature of the dataset, multiple metrics were used:

Accuracy

Precision

Recall

F1-score

These metrics provide a balanced view of model performance, especially for detecting dropout students.

 Results
 ###  Results Comparison
### 🏆 Results Comparison

| Model | Accuracy | Recall | F1-Score |
| Logistic Regression | 0.72 | 0.68 | 0.70 |
| KNN | 0.76 | 0.71 | 0.73 |
| **Random Forest** | **0.84** | **0.86** | **0.85** |

- **Random Forest** achieved the best overall performance.
- It demonstrated stronger recall and F1-score in identifying students at risk of dropout compared to Logistic Regression and KNN.
Random Forest achieved the best overall performance

It demonstrated stronger recall and F1-score in identifying students at risk of dropout compared to Logistic Regression and KNN

 Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

 How to Run the Project

Clone the repository

git clone <repository-url>


Install the required dependencies

pip install -r requirements.txt


Run the Jupyter Notebook

jupyter notebook elearning_dropout_analysis.ipynb

 Conclusion

This project demonstrates how Machine Learning can be applied to learning analytics to detect students at risk of dropping out.
It highlights the importance of data preprocessing, proper evaluation metrics, and model comparison when working with real-world educational data.

