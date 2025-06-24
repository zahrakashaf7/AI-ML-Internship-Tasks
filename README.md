# AI-ML-Internship-Tasks
 My tasks for the AI/ML Engineering Internship at DevelopersHub

# Task 1: Exploring and Visualizing a Simple Dataset

# Objective:
Explore and visualize the **Iris dataset** to understand feature relationships and data distribution using Python.

# Dataset Used:
[Iris Dataset (built-in in Seaborn)](https://en.wikipedia.org/wiki/Iris_flower_data_set)

# Key Results and Findings:
- Petal features clearly separate species visually and in classification.
- Setosa flowers are clearly separable using petal features.
- Feature distributions are fairly normal.
- Dataset is clean, balanced, and contains no missing values.

---

# Task 2: Predict Future Stock Prices (Short-Term)

# Objective:

The goal of this task is to predict the **next day's closing stock price** using historical stock market data.  
We utilize regression models to learn from historical trends and make short-term price forecasts.

# Dataset Used

- **Stock:** Apple Inc. (AAPL)
- **Source:** Yahoo Finance
- **Library Used:** `yfinance`
- **Time Range:** January 2020 to December 2024

The dataset includes the following features:
- Open
- High
- Low
- Close
- Volume

The target variable is the **next day's closing price**, created by shifting the `Close` column by -1.

# Models Applied

- **Linear Regression**
  - A basic and interpretable model to fit linear relationships between the features and the target.

# Key Results and Findings

- The **Linear Regression model** performed well in capturing the trend of closing prices.
- The **predicted values closely followed** the actual closing prices, as shown in the visualization.
- The plot of **actual vs predicted prices** demonstrated the model’s ability to generalize well to unseen data.
- Performance metrics (MAE and MSE) were within acceptable ranges for short-term stock predictions.
- Features like `Open`, `High`, `Low`, and `Volume` provided useful signals for forecasting the next day’s price.

---

# Task 3: Heart Disease Prediction

## 📌 Task Objective

Build a classification model that predicts whether a patient is at risk of heart disease based on their clinical and health-related features.  
This task uses real-world medical data to train and evaluate a binary classification model that can assist in early diagnosis.



## 📂 Dataset Used

- **Name:** Heart Disease UCI Dataset  
- **Source:** [Kaggle - Ronitf/heart-disease-uci](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)  
- **Format:** CSV (`heart.csv`)  
- **Features:** Age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, ECG results, max heart rate, exercise-induced angina, ST depression, etc.  
- **Target:** `1` = has heart disease, `0` = no heart disease



## 🧠 Models Applied

- ✅ **Logistic Regression**  
  A linear classification model ideal for binary outcomes and interpretable in healthcare settings.



## 📊 Key Results and Findings

- **Accuracy:** 79.5%  
- **ROC-AUC Score:** 0.88  
- **Confusion Matrix:** Balanced prediction across both classes (true positives and true negatives)
- **Key Features Identified:**
  - `cp` (chest pain type)
  - `thalach` (maximum heart rate achieved)
  - `oldpeak` (ST depression)
  - `slope` (slope of the peak exercise ST segment)



## ✅ Conclusion

- The Logistic Regression model demonstrated strong performance in predicting heart disease risk based on patient data.
- AUC score of 0.88 indicates the model can effectively distinguish between patients at risk and not at risk.
- The model can serve as a basic decision-support tool and could be further improved with more complex features or ensemble methods.






  

