
# 📊 Retail Sales Analysis using SQL

---

## 1. 📌 Background and Overview

This project focuses on analysing retail sales data to uncover actionable insights to support business decision-making. The dataset contains transactional-level data, including sales, quantity, pricing, and customer behaviour.

The goal of this project is to:

* Understand sales trends over time
* Identify top-performing products and regions
* Analyze customer purchasing behaviour
* Provide data-driven recommendations

---

## 2. 🗂️ Data Structure Overview

### Dataset Description

The dataset consists of the following key tables/files:

#### 📄 `store_sales.csv`

| Column Name  | Description             |
| ------------ | ----------------------- |
| order_id     | Unique order identifier |
| order_date   | Date of purchase        |
| product_id   | Product identifier      |
| quantity     | Units sold              |
| sales_amount | Total revenue           |
| price        | Price per unit          |
| customer_id  | Unique customer         |

#### 🧱 Data Model

* Fact Table: `store_sales`
---

## 3. 🧹 Data Cleaning

### Step 1:- To check for Duplicate 
* Check for Duplicates
 <img width="418" height="297" alt="image" src="https://github.com/user-attachments/assets/83f33850-0c99-48e1-a5c8-ad6505f2df3a" />
* Deleting Duplicates
 <img width="747" height="337" alt="image" src="https://github.com/user-attachments/assets/6cd7b895-810a-4cf2-97c2-3086ee595273" />

### Step 2:- Correction of Headers
* Checking Column Headers
 <img width="1148" height="220" alt="image" src="https://github.com/user-attachments/assets/61dd6a07-7623-47a6-8681-6434e27c263e" />
* After Correction
 <img width="1122" height="260" alt="image" src="https://github.com/user-attachments/assets/1a3c93b2-2f70-4e45-a96b-9acbbed3bf2f" />

 ### Step 3:- To check the Datatype
 * Check for Column datatype
<img width="435" height="469" alt="image" src="https://github.com/user-attachments/assets/6cf5d3f3-4df9-4b94-936f-8452daab0bd7" />

### Step 4:- To Check Null Values 
* Null Values
<img width="583" height="712" alt="image" src="https://github.com/user-attachments/assets/b3d8eb3a-5dd0-4414-a400-9fe4baeb2703" />
* Check for Nulls
<img width="1167" height="621" alt="image" src="https://github.com/user-attachments/assets/4f53f4b0-0310-4631-9308-14fde85b1b7d" />
* After Treating Nulls
<img width="1127" height="520" alt="image" src="https://github.com/user-attachments/assets/d8e8110c-b9eb-4096-95f8-f67a98092060" />

 ### Step 5:- To Check Gender Column 
 * Checking Gender Column
 <img width="311" height="251" alt="image" src="https://github.com/user-attachments/assets/a63554e8-0e7f-4465-9271-1afa6ffb79e8" />
 * After Updating
 <img width="310" height="285" alt="image" src="https://github.com/user-attachments/assets/af30171f-4984-46f2-9718-238c6d5f5bcb" />

 ### Step 6:- To Check Payment_mode Column
 
 * After Updating
<img width="333" height="296" alt="image" src="https://github.com/user-attachments/assets/19d01b18-c5e6-42e6-b45b-0000bc7c244d" />


## 4. 🔍 Insights Deep Dive

### 1. What are the top 5 best-selling products by quantity?
<img width="657" height="473" alt="image" src="https://github.com/user-attachments/assets/4fa3778e-8f1e-492e-a4a1-0d2b7651325e" />

### 2. Which products are most frequently cancelled?
<img width="681" height="445" alt="image" src="https://github.com/user-attachments/assets/530e8727-3d74-49c5-9b4a-9950c59b5159" />

### 3. What time of the day has the highest number of purchases?
<img width="647" height="478" alt="image" src="https://github.com/user-attachments/assets/70a31a21-b81a-4e54-8872-43f2e12dcc37" />

<img width="559" height="427" alt="image" src="https://github.com/user-attachments/assets/271f9266-8369-457f-8860-df4f46fd3717" />

### 4. Who are the top 5 highest spending customers?
<img width="570" height="340" alt="image" src="https://github.com/user-attachments/assets/ea94cbfe-d8d0-4d66-9c8a-48f593e03c86" />

### 5. Which product categories generate the highest revenue?
<img width="588" height="457" alt="image" src="https://github.com/user-attachments/assets/5a6e2b0c-26d8-4e1c-8e98-1722e2cdb0e9" />

### 6. What is the return/cancellation rate per product category?
<img width="763" height="339" alt="image" src="https://github.com/user-attachments/assets/e02dacc4-c0ee-4169-b348-43c7e9d8bcb2" />

<img width="745" height="420" alt="image" src="https://github.com/user-attachments/assets/982b9b5a-bc8d-4848-81f4-4e263c426740" />

### 7. What is the most preferred payment mode?
<img width="576" height="345" alt="image" src="https://github.com/user-attachments/assets/ac41bef7-51d2-41d8-abd0-135440b087bb" />

### 8. How does age group affect purchasing behaviour?
<img width="635" height="497" alt="image" src="https://github.com/user-attachments/assets/0c0a07e2-4709-40bb-804e-9770f08f6d5a" />

### 9. What’s the monthly sales trend?
<img width="535" height="465" alt="image" src="https://github.com/user-attachments/assets/37939f75-119a-468f-a4ed-5e55924968f3" />

<img width="664" height="616" alt="image" src="https://github.com/user-attachments/assets/b296f3a3-c745-47f0-9ef8-e7dcdbcd821d" />



## 5. 💡 Recommendations

Based on the analysis, the following recommendations are proposed:

* 🚀 Focus marketing efforts on top-performing products
* 📦 Optimize inventory for high-demand seasons
* 🎯 Target repeat customers with loyalty programs
* 📉 Reevaluate underperforming products
* 🌍 Expand operations in high-growth regions
---

## ⚙️ Tools & Technologies Used

* **SQL Server**
  
---

## 📌 Future Improvements

* Adding predictive analytics (sales forecasting)
* Integrating real-time data pipeline
* Build interactive dashboard with filters

---

## 📬 Contact

For any queries or collaboration:

* LinkedIn: [your-link](https://www.linkedin.com/in/santoshdharma001/)

---

## ⭐ If you found this project useful, give it a star!

---


