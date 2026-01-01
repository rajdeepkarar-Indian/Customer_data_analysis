# 📊 Customer Data Analysis for Business Insights

## 📌 Project Overview
This project performs an end-to-end **customer data analysis** to derive meaningful
business insights using **Python**.  
It focuses on understanding customer behavior, purchase patterns, segmentation,
and revenue contribution using **RFM analysis** and data visualization.

---

## 🛠️ Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib (`plt`)  
- Seaborn (`sns`)  
- `datetime` & `timedelta`

---

## 📂 Datasets Used
### 1. Customer Master Data
Contains customer demographic information:
- CustomerID  
- Name  
- Gender  
- Age  
- City  
- Marital Status  
- Number of Children  
- Join Date  

### 2. Customer Transaction Data
Contains transactional details:
- CustomerID  
- Transaction Date  
- Transaction Amount  

---

## 🔍 Steps Performed in Analysis
1. Data loading and inspection  
2. Data cleaning and type conversion  
3. Date handling using `datetime` and `timedelta`  
4. Merging customer and transaction datasets  
5. RFM (Recency, Frequency, Monetary) calculation  
6. RFM scoring and customer segmentation  
7. Data visualization using Matplotlib & Seaborn  
8. Business insights and summary reporting  

---

## 📈 Key Analysis & Visualizations
- Customer count by RFM segment  
- Revenue contribution by segment  
- Recency vs Monetary scatter plot  
- Pareto (80/20) analysis of customers  
- Segment-wise customer and revenue analysis  

---

## 🧠 Key Business Insights
- Identified **Loyal and Champion customers** contributing the highest revenue  
- Detected **At-Risk and Lost customers** for retention strategies  
- Observed that a small percentage of customers generate a large share of revenue  
- Helped understand customer engagement through recency and frequency metrics  

---

## ▶️ How to Run the Project
1. Clone the repository
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
