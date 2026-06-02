# E-Commerce Customer Churn Classification

## Project Overview

Customer churn is one of the most important business challenges in the e-commerce industry. Retaining existing customers is significantly less expensive than acquiring new ones, making churn prediction a valuable tool for improving customer retention and profitability.

In this project, I developed and evaluated multiple machine learning models to predict whether an e-commerce customer would churn. The objective was to identify high-risk customers using demographic information, purchasing behavior, customer satisfaction metrics, and engagement data.

The project followed a complete machine learning workflow including exploratory data analysis, feature engineering, model development, hyperparameter tuning, performance evaluation, and customer segmentation.

---

## Dataset Description

The dataset contains information on approximately 5,600 e-commerce customers and their interactions with an online retail platform.

### Target Variable

**Churn**

* 1 = Customer Churned
* 0 = Customer Retained

### Features Included

#### Customer Information

* Tenure
* City Tier
* Marital Status
* Gender

#### Platform Engagement

* Preferred Login Device
* Hours Spent on App
* Number of Registered Devices

#### Purchasing Behavior

* Order Count
* Preferred Order Category
* Coupon Usage
* Cashback Amount
* Days Since Last Order

#### Customer Experience

* Satisfaction Score
* Complaint History
* Number of Saved Addresses

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

* Investigated customer churn patterns
* Handled missing values
* Examined feature distributions
* Identified potential churn indicators

### 2. Data Visualization

Created visualizations to understand:

* Churn distribution
* Customer satisfaction trends
* Complaint behavior
* Order category preferences
* Customer engagement metrics

### 3. Machine Learning Models

Several supervised learning models were developed and compared:

#### Ridge Classifier

* Test Accuracy: 77.0%

#### Gradient Boosting Classifier

* Test Accuracy: 93.7%

#### Random Forest Classifier

* Test Accuracy: 95.7%
* Best overall model

### 4. Hyperparameter Tuning

Used:

* GridSearchCV
* RandomizedSearchCV
* Cross-validation techniques

to optimize model performance and reduce overfitting.

### 5. Customer Segmentation

Applied clustering techniques to identify customer groups with similar purchasing and engagement behaviors.

---

## Model Performance

### Best Model: Random Forest Classifier

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 95.7% |
| Precision | 96%   |
| Recall    | 78%   |
| F1 Score  | 86%   |

The Random Forest model demonstrated the strongest balance between overall accuracy and churn detection performance, making it the most effective solution for identifying customers at risk of leaving.

---

## Key Insights

Some of the strongest indicators of customer churn included:

* Customer complaints
* Customer tenure
* Days since last order
* Satisfaction score
* Order frequency
* Customer engagement metrics

These findings provide actionable insights that can help businesses proactively target at-risk customers with retention campaigns.

---

## Business Impact

This solution can help e-commerce organizations:

* Identify customers likely to churn
* Improve customer retention strategies
* Reduce acquisition costs
* Increase customer lifetime value
* Support targeted marketing campaigns
* Improve overall customer satisfaction

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

