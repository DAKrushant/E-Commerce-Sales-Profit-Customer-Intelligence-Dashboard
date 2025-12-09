# 📊 E-Commerce Sales, Profit & Customer Intelligence Dashboard  
**By: Krushant Shah**

A clean and professional Power BI dashboard designed to analyze e-commerce performance across sales, profitability, customer behavior, and customer value. The project follows industry best practices in data modeling, DAX, Power Query transformation, and interactive UX design.

---

## 🖼 Dashboard Preview

### **📌 Page 1 — E-Commerce Sales & Profitability Dashboard**
![E-Commerce Sales & Profit](Ecom Dashboard Screen Shot/Ecom Sales & Profit.png)


---

### **📌 Page 2 — Customer & Segment Analysis**
![Customer & Segment Analysis](Ecom Dashboard Screen Shot/customer_segment_analysis.png)

---

### **📌 Page 3 — Customer Details (Drillthrough Page)**
![Customer Details](Ecom Dashboard Screen Shot/customer_details.png)

---

## 🚀 Project Overview
This dashboard helps stakeholders:

- Track sales and profit trends  
- Analyze customer behavior and segmentation  
- Identify high-value and repeat customers  
- Understand category and region performance  
- Access detailed customer history through drillthrough  

It provides a complete 360° analytical view of the e-commerce business.

---

## 🧩 Data Model

### **Fact Table**
- `Fact_sales` → SalesAmount, Profit, OrderDate, CustomerID, ProductID, Quantity, Channel, PaymentType

### **Dimension Tables**
- `Dim_customers` → Customer profile, city, state, signup date, segment  
- `Dim_products` → Category, subcategory, brand, product attributes  
- `Dim_Date` → Full calendar table (Year, Month, Quarter, etc.)

Dataset size: **~1,000–2,000 rows**  
The model follows a **Star Schema** for clarity, performance, and scalability.

---

## 🛠 Data Preparation (Power Query)
- Corrected incorrect column data types  
- Removed duplicates and invalid rows  
- Cleaned and standardized text fields  
- Created Year, Month, Quarter, and Month-Year columns  
- Ensured proper key relationships before loading into the model  

---

## 📘 Key DAX Measures
Includes essential business KPIs:

- Total Sales  
- Total Profit  
- Total Orders  
- Average Order Value (AOV)  
- Total Customers  
- New Customers  
- Active Customers  
- ARPU (Average Revenue Per User)  
- Customer LTV (Lifetime Value)  
- Repeat Customer %  

Full DAX logic is included in the Power BI file.

---

## 📄 Dashboard Pages

### **1️⃣ Sales & Profit Analysis**
- KPI cards  
- Monthly sales trend  
- Sales & profit by category  
- Region & channel performance  
- Slicers for Year, Category, State  

### **2️⃣ Customer & Segment Analysis**
- Customer KPIs  
- Revenue by segment  
- New customer trend  
- Top 20 customers  
- State-wise performance  
- Repeat vs new customer breakdown  

### **3️⃣ Customer Details (Drillthrough Page)**
- Customer profile  
- LTV, Orders, AOV  
- Monthly spending trend  
- Full order history  

---

## 🔍 Key Insights
- Premium segments generate the highest revenue  
- Repeat customers form a major share of total sales  
- Some


