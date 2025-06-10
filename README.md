# Azure ETL Sales Dashboard: ADF + Azure SQL + Power BI

This project demonstrates how to build a complete ETL pipeline using **Azure Data Factory**, **Azure SQL Database**, and **Power BI** — turning raw Excel data into insightful dashboards.

---

##  Project Overview

- **Source**: Global Superstore Excel file
- **Ingested with**: Azure Data Factory (ADF)
- **Stored in**: Azure SQL Database
- **Visualized with**: Power BI Dashboard
- **Hosted on**: Azure Blob Storage + GitHub

---

##  Folder Structure


---

## 🛠 Tech Stack

- Azure Blob Storage
- Azure Data Factory (ADF)
- Azure SQL Database
- Power BI
- GitHub (project publishing)

---

##  ETL Workflow

1. **Excel file** is uploaded to **Azure Blob Storage**
2. **ADF Data Flow**:
   - Reads the Excel
   - Parses columns
   - Converts types (dates, floats, integers)
3. **Loaded into Azure SQL Table**
4. **Power BI Dashboard** connects to Azure SQL and visualizes:
   - Trends
   - Top products
   - Profit analysis

---

##  Dashboard Insights

### Summary KPIs
- 💰 Total Sales
- 🧾 Total Orders
- 📈 Total Profit

### 📈 Trend Visuals
- Monthly Sales Trend (with moving average)
- Sales YoY / MoM

### 🏆 Product Insights
- Top 10 Products by Sales
- Profit by Category and Sub-Category

### 🌍 Market Breakdown
- Sales by Region and Country
- Segment and Ship Mode slicers

---

## 🧪 How to Run This

1. Clone this repo or download ZIP
2. Upload `superstore_clean.xlsx` to Azure Blob
3. Use exported ADF `.json` files to recreate pipeline
4. Create SQL table using script in `/sql`
5. Run pipeline to populate data
6. Open Power BI → Connect to Azure SQL → Load `SalesOrders` table

---

## 📸 Dashboard Snapshot

*![image](https://github.com/user-attachments/assets/ddfee7b3-6e4e-4767-b43d-2c21a61c293a)
*

---





