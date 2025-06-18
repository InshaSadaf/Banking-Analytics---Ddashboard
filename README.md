# 🏦 Basic Banking Analytics Dashboard
This project is a full-fledged Banking Analytics System designed in Power BI, with backend integration using Microsoft SQL Server and data preprocessing handled through Python (Jupyter & Google Colab). It presents a complete 360° view of customer insights and financial metrics, useful for financial analysts, banks, and data science portfolios.

📌 Project Highlights
🔍 Data Source: Customer banking data (structured via SQL Server)

📊 Toolset: Power BI, SQL Server, Python (Pandas, Matplotlib, Seaborn)

💻 Environment: Google Colab, Jupyter Notebook

🎯 Use Case: Real-world data analyst project for banking domain

🔧 Tools & Technologies Used
Stack	Tools
Backend	Microsoft SQL Server
Scripting	Python (Pandas, NumPy, Seaborn, Matplotlib)
BI Tool	Power BI
Notebook Environment	Jupyter Lab, Google Colab
Data Modeling	DAX (Power BI Measures & Calculations)

🧠 Dashboard Pages
🔹 Page 1: Basic Banking Analytics
This dashboard gives a snapshot of the bank’s key metrics:

KPI Cards:

Total Clients

Total Deposits

Total Loans

Total Fees

Visuals:

Line chart of monthly deposits/fees

Pie charts for deposit/fee breakdown

Scatter plot for customer segmentation

Bar charts showing banking behavior by channel

Filters Used:

Nationality

Occupation

Loyalty classification

Income Band

Gender

Risk Weighting

Engagement Time

Location ID

🔹 Page 2: Client History Analysis
Focused on analyzing monthly and yearly trends in customer activity:

Bar Graphs:

Total clients over time (by Year & Month)

Slicers/Filters:

Gender

Income Band

Loyalty Classification

Occupation

Nationality

🧾 Data Model
📁 Tables Used:
Customer: base dataset with client demographics and financial info

Basic Calculations: derived measures including:

Total Clients

Total Deposits

Total Loans

Total Fees

Breakdown by Account Types (Credit, Saving, etc.)

📌 Features & Insights
Identifies high-value customer segments

Visualizes loan and deposit trends

Tracks client activity and history

Supports drill-through filters and dynamic exploration

📂 Project Structure
bash
Copy
Edit
/
├── PowerBI_Report/
│   └── Banking_Analytics.pbix
├── Python_EDA/
│   ├── data_cleaning.ipynb
│   └── adi_insights.py
├── SQL_Queries/
│   └── customer_query.sql
├── Screenshots/
│   ├── dashboard_main.png
│   └── dashboard_client_history.png
└── README.md
