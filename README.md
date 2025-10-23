## 🏦 Banking Dashboard Project
📋 Project Overview

-This project presents a comprehensive banking analytics dashboard designed in Power BI.
It visualizes insights from various financial datasets, including deposits, loans, savings, and customer transactions.

-Before dashboard creation, Exploratory Data Analysis (EDA) was performed using Python (Jupyter Notebook) to clean, transform, and understand the data.

🔍 Objectives

-Analyze key financial metrics such as Total Deposits, Total Loans, and Customer Distribution

-Provide insights into banking performance across multiple account types

-Enable interactive analysis using Power BI filters and slicers

-Create a visually engaging and data-driven decision support dashboard

🧠 Tech Stack
Tool	Purpose
-Python (Jupyter Notebook)	Data cleaning, preprocessing, and EDA
-Pandas, NumPy, Matplotlib, Seaborn	Statistical analysis and data visualization
-Power BI	Dashboard creation and KPI visualization
⚙️ Workflow

-Data Cleaning & Preparation (Jupyter Notebook)

Loaded raw banking data into a DataFrame

Handled missing values, duplicates, and data type mismatches

Generated summary statistics and correlation heatmaps

Derived metrics like Total Deposits and Total Loans

-Data Modeling (Power BI)

Imported the cleaned dataset into Power BI

Created relationships between banking tables

Added calculated columns and measures (using DAX):

Total Deposit = 
  SUM('Banking (1)'[Bank Deposits]) +
  SUM('Banking (1)'[Saving Accounts]) +
  SUM('Banking (1)'[Checking Accounts]) +
  SUM('Banking (1)'[Foreign Currency Account])

Total Loan = 
  SUM('Banking (1)'[Bank Loans]) +
  SUM('Banking (1)'[Business Lending]) +
  SUM('Banking (1)'[Credit Card Balance])


-Dashboard Design (Power BI)

Developed multiple KPI visuals (Total Deposits, Loans, etc.)

Added interactive slicers for filtering by customer, account type, and region

Used cards, bar charts, and line charts for trend analysis

Ensured responsive layout and professional design aesthetics

📊 Key Insights

-Comparison of deposit vs loan distribution

-Customer segmentation by account type and balance size

-Identification of high-performing banking categories

-Trend visualization over time to support financial forecasting

🧾 Files in Repository
File	Description
banking_eda.ipynb	Jupyter Notebook containing Python-based data exploration

powerbi_dashboard.pbit	Power BI template file of the interactive dashboard

README.md	Documentation of the project

Snapshot  screenshot of dashboards

🧩 Future Enhancements

Integrate real-time banking data through APIs

Add customer churn prediction model in Python

Publish dashboard to Power BI Service for online sharing

👩‍💻 Author

Tripti Singh- Data Analyst & Power BI Developer

📧 triptisingh2305@gmail.com

📍 Built with 💙 using Python & Power BI
