# 📊 Simple Sales Dashboard - Superstore Dataset

## 📝 Objective
The goal of this task is to design a **basic interactive dashboard** that visualizes sales performance across **product categories, regions, and time** using the Superstore Sales dataset. This helps business users gain quick insights into performance trends.

---

## 🛠 Tools Used
- **Power BI Desktop**
- (Optional) **Python (Pandas)** – for preliminary data cleaning

---

## 📁 Dataset
**Superstore_Sales.csv**  
Key columns used:
- `Order Date`
- `Region`
- `Category`
- `Sales`
- `Profit`

---

## 📌 Dashboard Features
- **Line Chart** – Monthly sales trends (`Month-Year`)
- **Bar Chart** – Sales by Region
- **Donut Chart** – Sales by Product Category
- **Slicer/Filter** – Interactive filtering by Region or Category

---

## 🔧 Steps to Reproduce
  
  **Import Dataset**
   - Load `Superstore_Sales.csv` into Power BI.

   **Data Transformation**
   - Create a new column for `Month-Year`:
     ```DAX
     MonthYear = FORMAT('Superstore_Sales'[Order Date], "MMM-YYYY")
     ```
   
     ```

   **Visuals Added**
   - **Line Chart**: `MonthYear` vs `Sales`
   - **Bar Chart**: `Region` vs `Sales`
   - **Donut Chart**: `Category` vs `Sales`

   **Add Slicer**
   - Insert a slicer with the field `Region` or `Category` for interactivity.

   **Export Dashboard**
   - Go to **File > Export > PDF** or take a screenshot.

---




