# 📊 Sales Performance & Bottleneck Analysis Dashboard

---

## 🚀 Project Overview

This project focuses on analyzing regional sales data to identify key revenue drivers, bottlenecks, and business opportunities.
Using **SQL + Power BI**, the raw dataset is transformed into an interactive dashboard for better decision-making.

---

## 🎯 Objectives

* Analyze **monthly sales trends**
* Identify **high-performing & underperforming regions**
* Detect **cancellations & returns patterns**
* Evaluate **product and category performance**
* Provide **data-driven business insights**

---

## 🛠️ Tools & Technologies

* 🗄️ SQL (MySQL)
* 📊 Power BI
* 📁 CSV Dataset

---

## 📊 Dashboard Preview

### 🔹 Full Dashboard

<img width="1920" height="1080" alt="Screenshot 2026-04-10 115734" src="https://github.com/user-attachments/assets/02eb3ea9-39ea-4c7c-b5a8-4a146484c551" />


## 📂 Dataset Details

* OrderID
* Date
* CustomerID
* Region
* ProductName
* Category
* Quantity
* UnitPrice
* TotalAmount
* OrderStatus (Completed, Cancelled, Returned)
* SalesAgent

---

## 🧮 Key SQL Analysis

```sql
SELECT 
    DATE_FORMAT(Date, '%Y-%m') AS Month,
    SUM(TotalAmount) AS TotalSales
FROM RegionalSales2025
WHERE OrderStatus = 'Completed'
GROUP BY Month;
```

---

## 💡 Key Insights

* South & East regions generate higher revenue
* High cancellations and returns indicate operational issues
* Electronics category dominates sales
* Certain products show higher return rates

---

## 🔧 Suggested Actions

* Improve logistics to reduce cancellations
* Enhance product quality to minimize returns
* Focus marketing on low-performing regions
* Train underperforming sales agents

---

## 📌 Conclusion

This project demonstrates how data analytics can uncover hidden business insights and support strategic decision-making.

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share your feedback!
