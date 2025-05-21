# 📊 Customer Churn Analysis
This project provides a detailed analysis of customer churn in a telecommunications company. It uses Python (Pandas, Seaborn, Matplotlib) to explore the dataset and derive meaningful business insights.

## 📁 Dataset
The dataset contains customer-level information such as:

Demographics: Gender, SeniorCitizen, Partner, Dependents

Services signed up for: Phone, Internet, Streaming

Account information: Tenure, Contract, Payment Method, Charges

Target: Churn (Yes/No)

## 🛠️ Technologies Used
Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook

## 📌 Key Insights
Overall churn rate: ~26.5%

Senior citizens churn more (~42%) than non-senior citizens (~24%)

Customers with month-to-month contracts are much more likely to churn (~43%) compared to those on longer contracts.

TechSupport and OnlineSecurity show strong correlation with churn: customers without these services tend to churn more.

Fiber optic users show higher churn rates (~42%) than DSL users (~19%).

## 📈 Visualizations
Count plots for each service category (Phone, Internet, Streaming, etc.)

Churn distribution per category

Annotated bars showing total users vs. churned users

## 📋 How to Run
Clone this repository
git clone https://github.com/ShashwatPathak-01/churn-analysis.git

Install dependencies
pip install -r requirements.txt

Open the Jupyter notebook
jupyter notebook ChurnAnalysis.ipynb

## 📄 Report
A full analysis report is available in the repo:

Customer_Churn_Analysis_Summary.docx

## ✅ Future Improvements
Build a churn prediction model using classification algorithms

Add interactive visualizations using Plotly

Deploy a dashboard using Streamlit or Dash
