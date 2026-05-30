# 📊 Telecom Customer Churn Analysis using Power BI

An end-to-end Business Analytics project focused on understanding, analyzing, and visualizing customer churn behavior in the telecom industry using Exploratory Data Analysis (EDA) and Power BI.

## 🎯 Project Objective

Customer churn is one of the most critical challenges faced by subscription-based businesses. The objective of this project is to:

- Identify factors influencing customer churn.
- Perform exploratory data analysis to uncover customer behavior patterns.
- Generate business insights that can help improve customer retention.
- Build an interactive Power BI dashboard for decision-making.

---

## 📁 Repository Structure

```
├── Churn Analysis - EDA.ipynb
├── Exploratory Data Analysis - Satyajit.pdf
├── Telecom Retention - Business Understanding.pdf
├── Telecom-Churn-Analysis-Dashboard.pbix
├── Telco-Customer-Churn.csv
└── README.md
```

### File Description

| File | Description |
|--------|------------|
| `Telco-Customer-Churn.csv` | Telecom customer churn dataset |
| `Churn Analysis - EDA.ipynb` | Data cleaning, preprocessing, and exploratory analysis |
| `Exploratory Data Analysis - Satyajit.pdf` | EDA report and findings |
| `Telecom Retention - Business Understanding.pdf` | Business problem definition and objectives |
| `Telecom-Churn-Analysis-Dashboard.pbix` | Interactive Power BI dashboard |
| `README.md` | Project documentation |

---

## 📊 Dataset Information

The dataset contains **7,043 customer records** with **21 attributes** related to telecom customer demographics, services, billing information, and churn status.

### Key Features

- Customer Demographics
  - Gender
  - Senior Citizen
  - Partner
  - Dependents

- Customer Account Information
  - Tenure
  - Contract Type
  - Payment Method
  - Paperless Billing

- Services Subscribed
  - Phone Service
  - Multiple Lines
  - Internet Service
  - Online Security
  - Online Backup
  - Device Protection
  - Tech Support
  - Streaming TV
  - Streaming Movies

- Billing Information
  - Monthly Charges
  - Total Charges

- Target Variable
  - Churn (Yes/No)

---

## 🔍 Exploratory Data Analysis (EDA)

The notebook performs:

### Data Inspection

- Dataset shape and structure
- Data type validation
- Statistical summaries
- Churn distribution analysis

### Data Cleaning

- Converted `TotalCharges` to numeric format
- Identified missing values caused by invalid entries
- Removed records with missing TotalCharges values
- Created a clean dataset for analysis

### Univariate Analysis

Analysis of:

- Customer tenure
- Contract types
- Internet services
- Payment methods
- Monthly charges
- Customer demographics

### Bivariate Analysis

Churn analysis against:

- Contract Type
- Tenure
- Internet Service
- Monthly Charges
- Payment Method
- Senior Citizen Status
- Additional subscribed services

---

## 📈 Key Business Insights

### High-Risk Churn Segments

- Customers with **Month-to-Month contracts** exhibit significantly higher churn rates.
- Customers using **Electronic Check** payment methods are more likely to churn.
- New customers with lower tenure are more prone to leaving.

### Retention Indicators

- Customers with **One-Year** and **Two-Year contracts** show better retention.
- Longer-tenure customers are less likely to churn.
- Customers subscribed to additional services such as:
  - Online Security
  - Tech Support
  - Device Protection

  tend to remain with the company longer.

### Revenue Impact

- Churn directly affects recurring revenue streams.
- Identifying high-risk customers enables proactive retention strategies.

---

## 📊 Power BI Dashboard

The Power BI dashboard provides interactive visualizations including:

- Total Customers
- Churn Rate
- Customer Segmentation
- Contract Analysis
- Payment Method Analysis
- Tenure Distribution
- Service Subscription Patterns
- Revenue Metrics

### Dashboard Capabilities

- Dynamic filtering
- Customer segmentation
- Drill-down analysis
- Business KPI monitoring
- Retention-focused insights

---

## 🛠️ Tools & Technologies

### Data Analysis

- Python
- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn

### Business Intelligence

- Microsoft Power BI

### Documentation

- Jupyter Notebook
- PDF Reports

---

## 🚀 Project Workflow

```text
Business Understanding
          ↓
Data Collection
          ↓
Data Cleaning
          ↓
Exploratory Data Analysis
          ↓
Business Insights
          ↓
Power BI Dashboard Development
          ↓
Decision Support & Retention Strategy
```

---

## 📌 Business Value

This project demonstrates how analytics can be leveraged to:

- Reduce customer attrition
- Improve customer retention strategies
- Increase customer lifetime value
- Support data-driven business decisions
- Monitor churn KPIs through interactive dashboards

---

## 📷 Dashboard Preview

Open the Power BI file:

`Telecom-Churn-Analysis-Dashboard.pbix`

using Microsoft Power BI Desktop to explore the complete interactive dashboard.

---

## 👨‍💻 Skills Demonstrated

- Business Analytics
- Data Cleaning & Preparation
- Exploratory Data Analysis (EDA)
- Data Visualization
- Customer Churn Analysis
- KPI Development
- Power BI Dashboard Design
- Business Insight Generation

---

## 📄 License

This project is intended for educational, learning, and portfolio purposes.

---
⭐ If you found this project useful, consider giving it a star on GitHub.
