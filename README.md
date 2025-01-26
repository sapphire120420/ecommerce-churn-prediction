# E-commerce Churn Prediction and Analysis

This repository contains a data analysis and machine learning project focusing on customer churn prediction for an e-commerce company. The project explores customer behavior, predicts churn, and segments churned users to help the company reduce churn and offer targeted promotions.

## 🚀 Project Overview

The project addresses the following objectives:
1. **Understanding Churned Users' Patterns and Behaviors:**
   - Identify patterns and behaviors of churned users.
   - Provide actionable recommendations to reduce churn.
   
2. **Building a Machine Learning Model:**
   - Develop and fine-tune a model to predict customer churn.

3. **Customer Segmentation for Targeted Promotions:**
   - Segment churned users into distinct groups.
   - Highlight differences between these groups to enable personalized promotions.

---

## 📂 Project Structure

- **Notebook:** [`K27_Nguyen_Thi_Nam_Phuong_Project3.ipynb`](https://colab.research.google.com/drive/1XQIpJkM2wkG87h7MEYbH-t7ZOxxbK6vp#scrollTo=9YSv_JwcbKG3)
  - Contains the code for data exploration, machine learning model development, and user segmentation.

- **Dataset:** `churn_predict.csv` (Not included in this repository for privacy reasons)
---

## 📊 Dataset Description

The dataset includes the following features:

| **Feature Name**               | **Description**                                                                 |
|---------------------------------|---------------------------------------------------------------------------------|
| `CustomerID`                   | Unique identifier for each customer.                                            |
| `Churn`                        | Churn flag (whether the customer has churned).                                  |
| `Tenure`                       | Tenure of the customer in the organization.                                     |
| `PreferredLoginDevice`         | Customer's preferred login device.                                              |
| `CityTier`                     | City tier (1, 2, 3).                                                            |
| `WarehouseToHome`              | Distance between warehouse and customer's home.                                 |
| `PreferPaymentMethod`          | Preferred payment method of the customer.                                       |
| `Gender`                       | Gender of the customer.                                                        |
| `HourSpendOnApp`               | Hours spent on the mobile app or website.                                       |
| `NumberOfDeviceRegistered`     | Total number of devices registered by the customer.                             |
| `PreferredOrderCategory`       | Most preferred order category of the customer in the last month.                |
| `SatisfactionScore`            | Customer satisfaction score.                                                    |
| `MaritalStatus`                | Marital status of the customer.                                                 |
| `NumberOfAddress`              | Total number of addresses added by the customer.                                |
| `Complain`                     | Whether the customer raised a complaint last month.                             |
| `OrderAmountHikeFromLastYear`  | Percentage increase in order amount from last year.                             |
| `CouponUsed`                   | Total number of coupons used in the last month.                                 |
| `OrderCount`                   | Total number of orders placed in the last month.                                |
| `DaySinceLastOrder`            | Days since the last order by the customer.                                      |
| `CashbackAmount`               | Average cashback received by the customer in the last month.                    |

---

## 🛠️ Steps in the Project

### 1. **Exploratory Data Analysis (EDA)**
   - Analyzed churn patterns using customer attributes like tenure, login preferences, and order behavior.
   - Identified correlations and trends between features and churn status.

### 2. **Predictive Modeling**
   - Built and fine-tuned machine learning models to predict churn.
   - Evaluated model performance using metrics like accuracy, precision, recall, and F1 score.

### 3. **Customer Segmentation**
   - Clustered churned users into distinct groups using clustering techniques.
   - Highlighted behavioral differences across groups for targeted marketing.

---

## 🗃️ Results and Recommendations

### **Key Findings**
- Churned users tend to have lower satisfaction scores, fewer recent orders, and higher complaints.
- Customers with higher order frequency and cashback amounts are less likely to churn.

### **Recommendations**
- Improve customer satisfaction by addressing complaints promptly.
- Offer loyalty programs with targeted cashback or discounts for users at risk of churning.
- Develop personalized marketing strategies based on user segmentation insights.

---

## 📦 Dependencies

The following Python libraries were used in this project:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`
- `dataprep` 
---

## 📜 License

This project is for educational purposes only.

---

## 👩‍💻 Author

**Sapphie Nguyen**

---

