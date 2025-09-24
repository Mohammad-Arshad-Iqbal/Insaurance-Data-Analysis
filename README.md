# Insurance Data Analysis (Power BI + SQL Server)


## 📝 Problem Statement  
Insurance companies deal with large volumes of policy, claim, and customer data. Managing this data effectively is challenging due to:  

- Lack of **real-time insights** into policy distribution and claim statuses  
- Difficulty in **tracking financial metrics** such as premium, claim, and coverage amounts  
- Limited visibility for **managers handling different policy types**  
- No structured way to analyze **customer feedback and sentiment**  

This project addresses these challenges by building an **interactive Power BI dashboard** connected to SQL Server, with role-based access and AI-driven sentiment analysis to help managers and decision-makers gain actionable insights.  

---
## Table of Contents
1. Objective
2. Dataset Description
3. Tools & Technologies Used
4. Project Workflow
5. Key Features
6. Dashboards & Reports
7. Insights & Results
8. Conclusion

## 1.Objective
The objective of this project is to:
- Import and clean insurance data
- Create interactive dashboards
- Analyze claims, policies, and sentiment from customer feedback
- Provide role-based insights for managers

## 2.Dataset Description
- Policy Information (Policy Number, Policy Type, Status)
- Customer Details (Age, Gender, Customer ID)
- Claim Details (Claim Number, Claim Amount, Status)
- Financials (Premium Amount, Coverage Amount)
- Feedback (Customer sentiment text)

## Tools & Technologies Used
- MS SQL Server → Data storage
- Power BI → Visualization & Dashboarding
- Power Query → ETL & Sentiment Analysis AI

## Project Workflow / Steps Performed
1. Imported raw data into MS SQL Server
2. Connected SQL Server to Power BI
3. Performed Data Profiling (column distribution, missing values, data types)
4. Created interactive dashboards in Power BI
5. Implemented Scheduled Refresh for automated updates
6. Created and assigned roles for managers (Home, Life, Auto, Travel, Health policies)
7. Applied Sentiment Analysis (AI) on customer feedback
   → Categorized into Excellent, Good, and Needs Improvement
## Key Features
- 📊 Role-based dashboards for managers
- 🔄 Automated data refresh
- 🤖 Sentiment analysis on customer reviews
- 🕵️ Drill-through feature for detailed analysis
- 📈 Interactive dashboards with claims, premium, and coverage insights
## Dashboards & Reports

### 1. Policy Overview Dashboard
<img width="1127" height="630" alt="Image" src="https://github.com/user-attachments/assets/df704663-9bf1-408c-8e21-a776edd4d8c4" />

### 2. Customer Sentiment Dashboard
<img width="1125" height="637" alt="Image" src="https://github.com/user-attachments/assets/8004d9cc-2498-4c4a-bc61-ec67958ba81d" />

## Insights & Results
- Premium Amount collected → 5.97M
- Coverage Amount → 600.23M
- Claim Amount → 16.90M
- Active Policies: 58.12% | Inactive Policies: 41.88%
- Claim Status → Rejected: 4.4K | Settled: 3.4K | Pending: 2.3K
- Sentiment Feedback → Excellent: 54, Good: 4, Needs Improvement: 39
## Conclusion
This project demonstrates how Power BI and SQL Server can be combined to create interactive 
dashboards and AI-powered insights. It helps insurance companies track performance, 
analyze customer sentiment, and provide role-based decision-making support.




