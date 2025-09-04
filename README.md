# 📊 Power BI Sales & Returns Dashboard

A Power BI project focused on **DAX mastery**, **filter context**, and **time intelligence**.  
The goal is to create a **Matrix-only dashboard** for analyzing **Sales**, **Returns**, and **Customer Insights** using a well-structured data model.

---

## 🗂️ Data Model
This project follows a **Star Schema** with 2 Fact tables and 4 Dimension tables.

| **Table Type** | **Table Name**    | **Purpose** |
|----------------|-------------------|-------------|
| Fact           | `Sales_Fact`      | Sales transactions |
| Fact           | `Returns_Fact`    | Product returns |
| Dimension      | `Customer_Dim`    | Customer details |
| Dimension      | `Product_Dim`     | Product categories |
| Dimension      | `Region_Dim`      | Geography data |
| Dimension      | `Date_Dim`        | Calendar details |

---

## 🌟 Core Tasks

### **1. Calculated Columns**
- Profit calculation per sale  
- Return flag: *Returned* or *Not Returned*  
- Customer full name by combining first & last names  

### **2. Measures**
- Total Sales, Cost, and Profit  
- Return Rate (%)  
- Average Sale per Transaction  

### **3. Quick Measures**
- Year-over-Year (YoY) Sales Growth  
- Month-over-Month Sales Difference  

### **4. Filter Context**
Use:
- `ALL()` → Remove filters  
- `FILTER()` → Custom filter logic  
- `CALCULATE()` → Modify filter behavior  

---

## ⏳ Time Intelligence
- `TOTALYTD()` → Year-to-date totals  
- `SAMEPERIODLASTYEAR()` → Compare to previous year  
- `DATESINPERIOD()` → Rolling analysis  
- Running totals using `DATESBETWEEN()`

---

## 📊 Output Requirement
All results must be displayed **only in Matrix visuals**, grouped by:

- Region  
- Month  
- Product Category  
- Customer Segment  

⚠️ *No other visual types are allowed.*

---

## 📝 Learning Outcomes
- Build and manage **calculated columns** & **DAX measures**  
- Understand **filter context** deeply with `CALCULATE()`  
- Apply **time intelligence** functions for trend analysis  
- Create a clean, **Matrix-only Power BI dashboard**

---

## 📁 Report View
<img width="1915" height="997" alt="Screenshot 2025-09-05 022448" src="https://github.com/user-attachments/assets/81985726-673c-437d-a6de-6259f18af460" />

