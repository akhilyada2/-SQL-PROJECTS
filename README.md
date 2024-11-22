# T-Mobile Customer Churn Analysis

## 📋 Project Overview
This project focuses on analyzing customer churn for T-Mobile using SQL. The dataset provides insights into customer behavior, subscription details, and churn patterns. The goal is to identify factors contributing to customer churn and develop strategies to improve retention.

## 🚀 Key Features
- **Database Design**: Creation of a relational database schema for storing customer data.
- **Data Import**: Loading and preprocessing the Telco Churn dataset into SQL Server.
- **Exploratory Data Analysis (EDA)**:
  - Churn rate analysis by demographic and subscription attributes.
  - Cohort analysis to measure customer retention.
  - Revenue loss estimation due to churn.
- **Advanced SQL Queries**:
  - Common Table Expressions (CTEs) for query optimization.
  - Time-series analysis of churn trends.
  - Retention and churn rate calculations by tenure and contract types.

## 🗂️ Project Structure
- **`TMobile_ChurnAnalysis.sql`**: SQL script for database creation and data analysis.
- **Dataset**: The Telco Customer Churn dataset (downloaded separately from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)).
- **Visualizations**: Insights and charts generated using tools like Tableau, Power BI, or Python (optional).

## 📊 Dataset Overview
The dataset contains the following key attributes:
- **Customer Demographics**: `Gender`, `SeniorCitizen`, `Partner`, `Dependents`.
- **Subscription Details**: `Tenure`, `PhoneService`, `InternetService`, `Contract`, `PaymentMethod`.
- **Financial Data**: `MonthlyCharges`, `TotalCharges`.
- **Churn Indicator**: `Churn` (Yes/No).

## 💡 Key Insights
- **Churn Prediction**: Identified the impact of tenure, contract type, and monthly charges on churn rates.
- **Retention Analysis**: Revealed retention trends across different customer groups.
- **Financial Impact**: Calculated revenue loss due to churned customers.

## 🔧 Tools and Technologies
- **Database**: SQL Server
- **Query Language**: SQL
- **Visualization** (Optional): Tableau, Power BI, or Python.

## 🚀 How to Use
1. Clone the repository.
   ```bash
   git clone https://github.com/your-username/TMobile_ChurnAnalysis.git
   ```
2. Load the SQL script `TMobile_ChurnAnalysis.sql` into your SQL Server instance.
3. Import the Telco Customer Churn dataset into the `Customers` table.
4. Run the provided SQL queries to explore churn patterns.

## 📝 License
This project is for educational and analytical purposes. Feel free to use and adapt it as needed.

