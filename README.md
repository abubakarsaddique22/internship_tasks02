# Internship Project: Machine Learning Tasks

## 🔹 Task Objective

This internship project consists of **three real-world machine learning tasks** designed to solve practical business problems through data-driven approaches:

1. **Customer Segmentation Using Unsupervised Learning**  
   Segment mall customers based on their spending habits and suggest targeted marketing strategies.

2. **Energy Consumption Forecasting**  
   Forecast household energy consumption using historical data and time series models.

3. **Term Deposit Subscription Prediction**  
   Predict whether a customer will subscribe to a term deposit based on bank marketing data.


## 🔹 Your Approach

### 1️⃣ Customer Segmentation (Unsupervised Learning)
- Performed **Exploratory Data Analysis (EDA)** to understand customer demographics and spending behavior.
- Applied **K-Means Clustering** to segment customers based on income and spending.
- Used **PCA (Principal Component Analysis)** for dimensionality reduction and visualization of clusters.
- Analyzed clusters to profile customer types and behaviors.


### 2️⃣ Energy Consumption Forecasting (Time Series)
- Parsed and resampled **household energy consumption** data into daily aggregates.
- Engineered time-based features: **day of the week, weekend indicator, lag consumption features**.
- Compared the performance of three models: **ARIMA**, **Prophet**, and **XGBoost**.
- Visualized actual vs. predicted energy usage for clear model evaluation.

### 3️⃣ Term Deposit Subscription (Supervised Learning)
- Conducted **EDA** to analyze patterns in the bank marketing dataset.
- Applied **data preprocessing**: encoding categorical features, handling imbalanced classes.
- Trained multiple models: **Logistic Regression, Decision Tree, Random Forest, XGBoost**.
- Evaluated models using **Accuracy, Precision, Recall, F1-Score**.


## 🔹 Results and Findings

### 1️⃣ Customer Segmentation
- Identified **4 distinct customer segments** through clustering based on income and spending behavior.
- Proposed tailored marketing strategies for each segment:
  - Loyalty programs for young high-spenders
  - Premium services for high-income, moderate spenders
  - Discounts for middle-income families
- PCA visualization validated the separation of customer groups.

---

### 2️⃣ Energy Consumption Forecasting

| **Model** | **MAE** | **RMSE** |
|-----------|---------|----------|
| ARIMA     | ~1.32   | ~1.78    |
| Prophet   | ~1.20   | ~1.50    |
| XGBoost   | **1.10** | **1.40** |

- **XGBoost provided the best forecasting accuracy.**
- Time-based feature engineering significantly improved model performance.

---

### 3️⃣ Term Deposit Subscription Prediction

| **Model**            | **Accuracy** | **F1-Score** |
|-----------------------|--------------|--------------|
| Logistic Regression   | ~89%         | ~78%         |
| Random Forest         | ~91%         | ~83%         |
| XGBoost               | **92%**      | **84%**      |

- **XGBoost outperformed other models** with the highest accuracy and F1-Score.
- Key predictive features: `previous campaign outcome`, `duration`, `poutcome`, `contact method`.


---
