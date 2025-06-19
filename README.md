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





  

