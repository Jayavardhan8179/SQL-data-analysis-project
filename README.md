# 🌍 Energy Consumption SQL Project  
A complete SQL-based data analysis project exploring global energy production, consumption, emissions, GDP, and population trends.

---

## 📌 Project Overview  
This project analyzes worldwide energy consumption using a structured relational SQL database.  
It contains multiple interconnected tables covering:

- **Country**
- **Energy Consumption**
- **Energy Production**
- **Emissions**
- **GDP (PPP)**
- **Population**

The aim is to understand **global energy trends**, environmental impact, and economic relationships using advanced SQL queries.  
This project mirrors real-world data analytics tasks performed in the energy, sustainability, and global economics domains.

---

## 🎯 Purpose of the Project  
The objective of this SQL project is to:

- Analyze global and regional energy trends  
- Understand connections between **GDP, emissions, population, and energy usage**  
- Compare energy production vs consumption for each country  
- Identify the countries contributing most to emissions  
- Explore sustainability insights with multi-year real-world data  
- Strengthen SQL skills with complex JOINs, aggregations, subqueries, CTEs, and analytical functions  

This project helps develop strong problem-solving and analytical skills for Data Analyst and BI roles.

---

## 🛢️ Dataset Description  
The SQL database includes **6 core tables**, all linked through the `country` table:

| Table Name      | Description |
|-----------------|-------------|
| **country**     | Master table for countries (Primary Key) |
| **consumption** | Annual energy consumption by energy type |
| **production**  | Annual energy production by energy type |
| **emission_3**  | Emissions data including per-capita metrics |
| **gdp_3**       | GDP (PPP) values by country and year |
| **population**  | Population of each country by year |

All supporting tables include a **foreign key reference** to the `country` table, making this a well-normalized relational dataset.

---

## 🏗️ Database Schema

### ✔ Tables Included  
- country  
- consumption  
- production  
- emission_3  
- gdp_3  
- population  

### ✔ ER Diagram Overview  
Each country can have multiple yearly entries in:

- Emissions  
- Production  
- Consumption  
- Population  
- GDP  

This 1-to-many structure supports powerful analytical queries across years and categories.

---

## 🧠 Problem Statements / Analysis Questions  

### 🌎 **General & Comparative Analysis**
1. What is the total emission per country for the latest available year?  
2. Which are the top 5 countries by GDP?  
3. How does annual energy production compare with consumption?  
4. Which energy types contribute most to global emissions?  

### 📈 **Trend Analysis Over Time**
5. How have global emissions changed year over year?  
6. What is the GDP trend for each country?  
7. How has population growth affected total emissions?  
8. Has energy consumption increased or decreased in major economies?  
9. What is the average yearly change in per-capita emissions?  

### 📊 **Ratio & Per-Capita Analysis**
10. Emission-to-GDP ratio by country  
11. Energy consumption per capita per year  
12. Energy production per capita by country  
13. Highest energy consumption relative to GDP  

### 🌐 **Global Comparisons**
- Top 10 populated countries and their emission levels  
- Countries with the biggest decrease in per-capita emissions  
- Global emission share (%) by country  
- Global averages: GDP, emissions, population by year  

---

## 🧩 Skills Used  

### 🛠 SQL Skills
- Database creation & schema design  
- Primary and foreign key constraints  
- Data import and normalization  
- JOIN operations (INNER, LEFT, RIGHT)  
- GROUP BY and HAVING  
- Aggregate functions (SUM, AVG, MAX, MIN)  
- Subqueries & Nested queries  
- Window functions  
- Common Table Expressions (CTEs)  
- Data cleaning and transformation  

### 📊 Analytical Skills
- Trend analysis  
- Ratio & per-capita metrics  
- Cross-country comparative analysis  
- Identifying global energy patterns  
- Interpreting environmental and economic insights  

---

## 🚀 How to Use This Project

### **1️⃣ Create the Database**
```sql
CREATE DATABASE ENERGYDB;
USE ENERGYDB;
