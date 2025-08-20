# 🏨 AtliQ Hotels Data Analysis Project

## 📌 About the Company
**AtliQ Grands** is a hotel chain operating in multiple cities across India.  
They have been in the hospitality industry for around **20 years** and own **Business and Luxury hotels**.

### 🌍 Hotel Locations
- Delhi  
- Mumbai  
- Bengaluru  
- Hyderabad  

### 🏠 Room Categories
- Standard  
- Elite  
- Premium  
- Presidential  

AtliQ Hotels accept bookings through both their **own website** and **third-party platforms**, making them accessible to a wide range of customers.

---

## 🔍 Business Problem
AtliQ Grands is facing **stiff competition** and has been **losing revenue and market share** to rivals.  
This project uses **data analytics** to uncover insights that can help improve revenue, occupancy, and overall performance.  

---

## 📊 Project Steps

### 1️⃣ Understand the Business Problem  
- Identify the challenges AtliQ Grands is facing.  
- Frame analysis goals around **occupancy, revenue, and booking patterns**.  

### 2️⃣ Data Collection and Understanding  
We worked with **5 CSV files**:  
- `dim_date.csv`  
- `dim_hotels.csv`  
- `dim_rooms.csv`  
- `fact_aggregated_bookings.csv`  
- `fact_bookings.csv`  

### 3️⃣ Data Cleaning and Exploration  
- Removed **negative values** from `no_guest` column.  
- Handled **outliers** in `revenue_generated` column.  
- Managed missing values and ensured consistency.  

### 4️⃣ Data Transformations  
- Created new calculated columns such as **Occupancy %** in `df_agg_bookings`.  
- Performed transformations for better aggregation and insights.  

### 5️⃣ Collect Insights  
Key business questions answered:  
- 📈 What is the **average occupancy rate** by room type and city?  
- 📅 How does occupancy vary on **weekdays vs weekends**?  
- 💰 What is the **revenue generated per city**?  
- 📊 What are the **monthly revenue trends**?  
- 🌐 How much revenue comes from **different booking platforms**?  

---

## 🛠 Skills & Tools Learned
- **Python Programming** → Data cleaning, transformation, analysis, visualization.  
- **Pandas Fundamentals** → Creating DataFrames, groupby, concat/merge, handling NA values, reading CSV files.  
- **Data Visualization** → Creating meaningful charts and bar plots for insights.  

---


