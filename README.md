# Telecom Customer Churn Analysis

## Overview
This project focuses on analyzing customer churn in the telecom industry using data analytics techniques. The objective is to identify key factors influencing customer retention and attrition, uncover churn patterns, and provide business recommendations to improve customer loyalty.

The project includes data cleaning, preprocessing, exploratory data analysis (EDA), and dashboard creation using Power BI. It reflects a real-world Data Analyst workflow used in IT companies for business decision-making.

---

## Project Objectives

- Analyze telecom customer data to identify churn drivers  
- Understand customer behavior based on demographics and services used  
- Detect high-risk customer segments likely to churn  
- Build an interactive dashboard for business insights  
- Recommend strategies to improve customer retention  

---

## Dataset Information

The dataset contains **7,000+ customer records** with multiple features related to customer accounts and services.

### Key Columns:
- CustomerID  
- Gender  
- SeniorCitizen  
- Partner  
- Dependents  
- Tenure  
- PhoneService  
- InternetService  
- OnlineSecurity  
- TechSupport  
- Contract  
- PaymentMethod  
- MonthlyCharges  
- TotalCharges  
- Churn  

---

## Tools & Technologies Used

### Python
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

### Business Intelligence
- Power BI Desktop  
- Power Query  

### Development Environment
- Jupyter Notebook  

---

## Project Workflow

### 1. Data Cleaning & Preprocessing
- Handled missing values in `TotalCharges`
- Converted incorrect data types
- Removed blank spaces and inconsistencies
- Verified column formatting

### 2. Exploratory Data Analysis (EDA)
Performed visual and statistical analysis to identify churn trends:

- Churn distribution
- Churn by gender
- Churn by contract type
- Churn by tenure
- Monthly charges distribution
- Churn by payment method
- Service-wise churn comparison

### 3. Dashboard Development (Power BI)

Built an interactive dashboard containing:

- Total Customers
- Total Churned Customers
- Churn Rate (%)
- Churn by Gender
- Churn by Contract Type
- Churn by Tenure Groups
- Churn by Payment Method
- Service Usage Insights

---

## Key Insights

- Customers with **month-to-month contracts** have the highest churn rate.
- Customers with **short tenure (0–12 months)** are more likely to churn.
- Customers with **higher monthly charges** show increased churn probability.
- Customers without **Tech Support** or **Online Security** churn more frequently.
- **Electronic Check** users show higher churn compared to auto-pay users.

---

## Business Recommendations

- Promote long-term contracts with discounts
- Improve onboarding for new customers
- Offer loyalty rewards to high-value customers
- Encourage auto-payment methods
- Improve support services and bundled plans

---

## How to Run the Project

### Run Python Analysis

1. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn notebook
