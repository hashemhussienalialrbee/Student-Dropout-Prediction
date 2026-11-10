# 🎓 Student Dropout Prediction

## 📌 Project Overview

Student Dropout Prediction is a Machine Learning project that aims to analyze student-related factors and predict whether a student is likely to drop out or continue their education.

The project follows a complete Machine Learning workflow, starting with data cleaning and Exploratory Data Analysis (EDA), followed by data preprocessing, model development, and performance evaluation.

## 🎯 Project Objectives

- Analyze factors associated with student dropout.
- Explore academic performance and student characteristics.
- Perform Exploratory Data Analysis (EDA).
- Prepare and preprocess the dataset.
- Develop Machine Learning classification models.
- Evaluate and compare model performance.

## 📊 Exploratory Data Analysis (EDA)

EDA was conducted to understand the dataset and identify patterns related to student dropout.

Key analysis areas:

- CGPA and academic performance.
- Attendance rates.
- Stress index.
- Family income.
- Internet access.
- Part-time employment.
- Correlation analysis.
- Dropout distribution.

The analysis identified academic performance, attendance, and stress as important factors associated with dropout status.

## 🧹 Data Cleaning

The data cleaning stage included:

- Dataset inspection and structure analysis.
- Missing value detection and handling.
- Duplicate record checking.
- Handling extreme values.
- Data type correction.
- Statistical summaries and comparisons.

## ⚙️ Data Preprocessing

The preprocessing stage included:

- Train, validation, and test splitting.
- Feature engineering.
- Categorical feature encoding.
- Numerical feature scaling.
- Handling class imbalance using SMOTE.
- Preparing data for Machine Learning models.

## 🤖 Machine Learning Models

Three classification algorithms were developed and evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest

Hyperparameter tuning was performed using GridSearchCV and Stratified 5-Fold Cross-Validation, with F1-score as the optimization metric.

## 📈 Model Evaluation Results

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.75 | 0.47 | 0.72 | 0.57 |
| Decision Tree | 0.72 | 0.44 | 0.76 | 0.56 |
| Random Forest | 0.75 | 0.48 | 0.68 | 0.57 |

*Precision, Recall, and F1-Score refer to the Dropout class.*

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook

## 📁 Project Structure

```text
Student-Dropout-Prediction/
│
├── Data/
│
├── student_dropout_prediction(Data Cleaning).ipynb
│
├── student_dropout_prediction(Preprocessing).ipynb
│
├── Student_Dropout_Combined_Models_Refinment.ipynb
│
└── README.md
```

## 👥 Team Members & Contributors

This project was developed collaboratively by:

- **Ola Alkurdi** — [GitHub Profile](https://github.com/Ola-Alkurdi)
- **Rua'a Alkurdi** — [GitHub Profile](https://github.com/ruaa-alkurdi)
- **Noha Ahmad Alsdifat** 
- **Hashem Alrabie** — [GitHub Profile](https://github.com/hashemhussienalialrbee)

### Project Contributions

The project covers the following collaborative activities:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Machine Learning Model Development
- Model Evaluation and Comparison

---

**Project:** Student Dropout Prediction  
**Domain:** Machine Learning | Data Science  
**Language:** Python
