# 🍽️ Tips Prediction using Linear Regression

## 📌 Project Overview
This project aims to build a Machine Learning model to predict the tip amount given by restaurant customers based on various factors such as total bill, number of people, gender, smoking status, day, and time.

The primary goal of this project is to understand and apply the fundamentals of Linear Regression.

---

## 🎯 Problem Statement
To develop a regression model that predicts the tip amount using customer and billing information.

---

## 📊 Dataset
- Dataset used: Seaborn "Tips" dataset
- It contains information about restaurant bills and tips.

### Features:
- total_bill: Total bill amount
- tip: Tip amount (Target Variable)
- sex: Gender of customer
- smoker: Smoking status
- day: Day of the week
- time: Lunch/Dinner
- size: Number of people

---

## 🔍 Steps Performed

### 1. Data Loading
- Loaded dataset using seaborn library

### 2. Data Understanding
- Checked data types and structure using `.info()`
- Checked dataset shape

### 3. Missing Value Check
- Verified no missing values using `.isnull().sum()`

### 4. Exploratory Data Analysis (EDA)
- Univariate analysis (distribution of tips)
- Bivariate analysis (total bill vs tip)
- Categorical analysis (tips across days)

### 5. Feature Engineering
- Created new feature: tip_percentage

### 6. Data Preprocessing
- Converted categorical variables using One-Hot Encoding

### 7. Model Building
- Applied Linear Regression algorithm

### 8. Model Evaluation
- Evaluated using:
  - R² Score
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)

---

## 📈 Results
- The model shows a strong relationship between total bill and tip
- Total bill is the most influential feature in predicting tips
- The model performs reasonably well for a basic regression approach

---

## 🧠 Key Learnings
- Understanding of Linear Regression fundamentals
- Importance of EDA before modeling
- Handling categorical data using encoding
- Evaluating regression models using appropriate metrics

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 🚀 Future Improvements
- Use advanced models like Random Forest and XGBoost
- Perform hyperparameter tuning
- Improve feature engineering
- Handle outliers for better accuracy

---

## 📌 Conclusion
This project successfully demonstrates the implementation of Linear Regression for predicting continuous values. It helped build a strong foundation in machine learning concepts such as data preprocessing, feature engineering, and model evaluation.

---

## 📂 How to Run the Project
1. Clone the repository
2. Install required libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
