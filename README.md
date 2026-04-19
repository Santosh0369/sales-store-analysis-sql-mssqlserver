
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

## 3. 📈 Executive Summary

### Key Findings:

* 💰 Total Revenue: **$XXX,XXX**
* 📦 Total Orders: **X,XXX**
* 📊 Average Order Value: **$XX**
* 🏆 Top Category: *Electronics*
* 📅 Peak Sales Month: *December*

### Business Impact:

* Identified high-performing products contributing to ~XX% of revenue
* Seasonal trends show significant spikes during festive periods
* Customer segmentation highlights repeat buyers as major revenue drivers

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
 <img width="450" height="256" alt="image" src="https://github.com/user-attachments/assets/37fac5bc-6dce-4036-b18a-1113348ad024" />


## 4. 🔍 Insights Deep Dive

### 



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


