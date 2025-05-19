# 📊 Customer & Sales Data Analysis – Mini Project

![Data Analysis](https://img.shields.io/badge/Data--Driven-Business--Insights-blue)
![Excel](https://img.shields.io/badge/Excel-Power--Query-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 🧠 Project Aim

This project aims to extract valuable business insights from raw customer and sales data by performing **data cleaning**, **transformation**, **analysis**, and **visualization** using Microsoft Excel. It also identifies potential **cross-selling opportunities** based on customer behavior and product demand.

---

## 📌 Project Overview

The project was part of a Business Analyst Internship assignment. It involved working with a real-world dataset consisting of customer profiles, purchase behavior, and product information. The goal was to prepare the dataset for analysis, answer key business questions, and create actionable insights that support business decisions and sales strategies.

---

## 🎯 Project Objectives

- Clean and validate customer data (emails, phone numbers, duplicates, etc.).
- Analyze customer distribution by region, state, and industry.
- Calculate average purchases by segment (Retail, Wholesale, etc.).
- Identify top-performing products by revenue.
- Explore cross-sell opportunities using product association logic.
- Present findings through clear visuals and summaries.

---

## 🛠️ Tools & Technologies Used

| Tool              | Purpose                                  |
|-------------------|-------------------------------------------|
| 🟢 **Microsoft Excel**  | Data cleaning, transformation, charts |
| 🟦 **Power Query**      | Advanced data shaping and cleanup     |
| 📈 **Pivot Tables**     | Aggregation and analysis              |
| 📊 **Excel Charts**     | Visual representation of insights     |
| 🧪 **Excel Formulas**   | Data validation and logic (IF, LEN, SEARCH, SUBSTITUTE, etc.)

---

## 📂 Dataset Information

- Format: `.xlsx` Excel Workbook  
- Key Columns: `Customer_ID`, `Customer_Name`, `Email`, `Phone_Number`, `State`, `Region`, `Industry`, `Product_Name`, `Purchase_Date`, `Total_Purchase`, `Revenue`  
- Records: ~25,000+ entries  
- Source: Internal business customer and sales data (Assignment)

---

### 🔁 ETL Process (Extract – Transform – Load)

---

#### ✅ 1. Extract
- Imported the raw `.xlsx` dataset provided as part of the Business Analyst internship assignment.
- Loaded the dataset into **Microsoft Excel** and **Power Query** for structured transformation and data preparation.

---

#### 🔧 2. Transform (Data Cleaning & Standardization)

The transformation process focused on ensuring the dataset was accurate, consistent, and analysis-ready using Excel formulas and Power Query.

---

##### 📧 Email Address Cleaning & Validation
- Identified and corrected emails missing the `@` symbol before domain names (e.g., `usergmail.com` → `user@gmail.com`).
- Replaced invalid domain patterns such as `@gmailcom`, `@yahoocom`, and `@outlookcom` with proper formats like `@gmail.com`.
- Fixed incorrect domain characters like `@.` using:

---

##### 📞 Phone Number Standardization
- Cleaned phone numbers by removing symbols like dashes -, spaces, and brackets () using substitute function
- Validated phone numbers to match Indian mobile number standards like Must be exactly 10 digits and Must start with digits 6 to 9 using if and len function

---

##### 🧹 Additional Data Cleaning
- Removed duplicate records using Power Query > Remove Duplicates.
---

##### 📥 3. Load
- Loaded the cleaned dataset back into Excel.
- Created:Pivot Tables for customer and product analysis
- Charts for visual storytelling (bar, pie, line)

---

## 📊 Dashboard Preview

Here are some of the charts created during the project:

![image](https://github.com/user-attachments/assets/c059c3d6-3903-453a-994b-d3bd4c8ea70e)


## 🔗 Cross-Selling Product Matrix

Although the original dataset didn't include transaction-level combinations, we inferred cross-sell opportunities using product purchase volumes and logical associations:

| Product A         | Potential Cross-Sell Products         |
|-------------------|----------------------------------------|
| **Laptop**        | Software Suite, Cloud Subscription     |
| **Monitor**       | Printer, Cloud Subscription            |
| **Smartphone**    | Cloud Subscription, Tablet             |
| **Tablet**        | Software Suite                         |

📌 **Recommendation**: Bundle offers and upsell strategies can be implemented based on this matrix.

---

## 📌 Key Insights

- 📍 **West & North India** had the highest customer concentration.
- 🏢 **Education** was the leading industry segment by customer count.
- 💰 **Retail customers** had the highest average total purchases.
- 🖥️ **Monitors** and **Smartphones** were the top-revenue-generating products.
- 🔗 Logical product pairings suggest strong **cross-sell potential** in bundling strategies.

---

## 💼 Business Impact

- 🧹 Improved data quality ensures better CRM integration and reporting.
- 📊 Enhanced understanding of sales patterns and regional behavior.
- 🔁 Identified key product pairings that can drive **sales growth through cross-selling**.
- 📈 Actionable insights help optimize marketing and inventory strategies.

---

## 📌 Significance of the Project

This project showcases how structured Excel-based analysis can provide deep business insights without needing advanced tools. It demonstrates practical applications of data cleaning, transformation, and visualization—all critical skills for a Business Analyst. The ability to identify sales trends and customer behavior empowers companies to make smarter decisions and boost revenue.

---

## 📝 Author

**Vandana**  
💼 Business Analyst Intern  
📧 godabavandana@gmail.com  

