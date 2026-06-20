# Employee Attrition Prediction

## Overview

Employee attrition is one of the major challenges faced by organizations. High turnover rates can lead to increased recruitment costs, productivity loss, and knowledge gaps.

This project applies Machine Learning techniques to predict whether an employee is likely to leave the company based on demographic, professional, and compensation-related factors.

The goal is to help organizations identify at-risk employees and develop retention strategies.

---

## Objectives

- Analyze employee data and identify factors influencing attrition.
- Perform Exploratory Data Analysis (EDA).
- Handle data imbalance issues.
- Train and evaluate multiple Machine Learning models.
- Compare model performance and select the best model.

---

## Dataset

The dataset contains employee information such as:

- Employee Age
- Gender
- Education
- Department
- Job Role
- Salary Tier
- Years of Experience
- Joining Year
- City
- Attrition Status

Target Variable:

```text
Attrition:
0 = Employee Stays
1 = Employee Leaves
```

---

## Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Imbalanced-learn (SMOTE)

### Development Environment

- Jupyter Notebook

---

## Project Workflow

### 1. Data Preprocessing

- Handle missing values
- Remove duplicate records
- Encode categorical features
- Feature selection

### 2. Exploratory Data Analysis (EDA)

- Attrition distribution
- Salary analysis
- Age analysis
- Department comparison
- Correlation analysis

### 3. Class Imbalance Handling

Applied SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.

### 4. Model Training

Models evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

### 5. Model Evaluation

Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Results

### Best Performing Model

Random Forest achieved the highest overall performance.

| Metric | Value |
|----------|----------|
| Accuracy | 82.38% |
| F1 Score | 72.6% |

---

## Key Findings

The most influential factors affecting employee attrition include:

- Age
- Joining Year
- Payment Tier
- City
- Experience Level

Employees with lower compensation levels and shorter tenure showed a higher probability of leaving the organization.

---

## Repository Structure

```text
Employee-Attrition-Prediction
│
├── employee_attrition_prediction.ipynb
├── Employee.csv
├── README.md
```

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/tonthatgiahuy16/Employee-Attrition-Prediction.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn imbalanced-learn
```

### Launch Notebook

```bash
jupyter notebook
```

Open:

```text
employee_attrition_prediction.ipynb
```

---

## Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- Feature engineering improvements
- Model deployment with FastAPI
- Interactive dashboard development

---

## Author

Ton That Gia Huy

Final-Year Information Technology Student

Interested in:

- Data Engineering
- Data Science
- Machine Learning
- Big Data Analytics

GitHub:
https://github.com/tonthatgiahuy16
