# Bank Churn Analysis Dashboard

## 📊 Overview

This Power BI dashboard provides an in-depth analysis of customer churn within a banking institution. The primary objective is to identify key patterns and insights behind customer attrition, enabling stakeholders to take proactive measures to improve customer retention.

---

## ❓ Business Questions Answered

- What is the overall churn rate?
- Which age groups are more likely to churn?
- How does customer tenure affect churn?
- Are churn rates different across countries?
- What product segments have the highest customer churn?
- Does gender play a role in customer churn?

---

## 🔍 Key Metrics

- *Total Customers:* 10,000  
- *Churned Customers:* 2,040  
- *Active Customers:* 7,960  
- *Churn Rate:* 20.37%

---

## 🧹 Data Cleaning Process

The raw dataset was cleaned using Power Query within Power BI Desktop. The following steps were taken:

- Removed duplicate records
- Handled missing values in critical columns like age, tenure, and product type
- Converted data types (e.g., age and tenure as integers)
- Standardized categorical fields (e.g., gender, country names)
- Filtered out irrelevant columns for dashboard KPIs
- Created calculated columns such as:
- Churn Rate %
- Customer Segments by Age/Tenure/Product Usage

---

## 🧩 Dashboard Features

- *Churn by Age Bracket*
- *Churn by Tenure Range*
- *Churn by Country*
- *Churn by Product Range*
- *Total Customer by Gender*
- *Interactive Filters* for gender and churn status

---

## 💡 Key Insights

1. *Age-based Churn Trends*: Young Professionals show the highest churn.
2. *Tenure Impact*: New customers are more likely to churn.
3. *Geographic Analysis*: Spain has relatively better retention.
4. *Product Engagement*: Single service customers churn the most.
5. *Gender Distribution*: Even distribution, with no major churn gap.

---

## 📁 Dataset

- *Source*: [Internal/External CSV or simulated data]
- *Attributes*: Age, Gender, Country, Tenure, Products, Churn status, etc.

---

## ⚙️ Tools Used

- Power BI Desktop (Data Cleaning + Visualization)
- Power Query (ETL process)

---

## 🛠️ How to Use

1. Open the .pbix file in Power BI Desktop.
2. Explore filters (gender, churn status).
3. Interpret visual patterns and take action.

---

## 📸 Preview

> ![Dashboard Preview](./bank_churn_report_preview.png)  
> (Insert your actual dashboard screenshot.)

---

## 👤 Author

*Lourdu Alphonse A*  
[GitHub Profile](https://github.com/LourduAlphonse)  

---

## 📄 License

This project is licensed under the [MIT License](LICENSE)
