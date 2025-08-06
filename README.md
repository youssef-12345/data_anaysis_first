# Power BI Sales & Customer Performance Dashboard

## 📌 Overview
This project presents an interactive **Power BI Dashboard** that analyzes **sales performance, customer segmentation, and product insights** over multiple years.  
The dataset powering this dashboard is sourced from a **custom-built Data Warehouse**, which I previously developed as part of an ETL pipeline project.  

---

## 🗂 Data Model
The Power BI model is built on **Star Schema** principles:
- **Fact Table**: `FactSales` – contains transactional data such as sales amount, order quantity, and dates
- **Dimensions**:
  - `Product_View` – product details, category, performance segmentation, lifespan
  - `Customer_View` – customer details, segmentation, and behavior patterns

The **Fact Table** acts as the central table to establish relationships between dimensions in Power BI.

---

## 📊 Dashboard Features
- **Sales Analysis**
  - Sales by category (Bikes, Accessories, Clothing)
  - Sales by age group and performance segment
- **Customer Analysis**
  - Segmentation into VIP, Regular, and New
  - Monthly spending trends by age group
  - Customer lifespan and order behavior
- **Product Analysis**
  - High-Performer, Mid-Range, and Low-Performer classification
  - Product lifespan and category-based revenue

---

## 🛠 Tools & Technologies
- **SQL Server** for Data Warehouse design and ETL processes  
- **Power BI** for interactive dashboards and reporting  
- **DAX** for KPIs and measures  

---

## 📂 Dataset
The dataset used in this dashboard was extracted from **SQL Views** and the **Fact Table**:
- `FactSales.csv` – transactional data for sales
- `Product_View.csv` – product-related details
- `Customer_View.csv` – customer-related details

**Export Method**: Data was extracted from SQL Server using `SELECT *` statements and exported as CSV files.

---

## ✅ How to Use
1. Clone this repository
2. Download the dataset from the `dataset` folder
3. Open the `.pbix` file in Power BI Desktop
4. Connect to the provided sample dataset or your own

---

## 📸 Screenshots
(Add screenshots of your dashboard pages here)

---

## 📬 Contact
For any questions or collaborations:
**LinkedIn**: [Your LinkedIn Profile Link]  
