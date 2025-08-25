# Analysis-of-Product-Sales
Product sales data: cleaning, analysis, and visualization using Python

## 📖 Objective
The goal of this project is to **predict product sales over time** using a **linear regression model**.  
By analyzing historical sales data, the project seeks to identify trends, forecast future demand, and support decision-making in inventory and sales strategy.

## 🛠️ Tools & Technologies
- **Python (Jupyter Notebook):** For analysis, modeling, and visualization.
- **pandas:** For structuring, cleaning, and manipulating tabular data.
- **Power Query:** Data cleaning (removing nulls, filtering erroneous rows, ensuring consistency).
- **Power BI:** Visualization and analysis of the cleaned dataset.

## 📊 Dataset
- **Source:** Synthetic dataset created for learning purposes.  
- **Structure:** ~100 rows with features including:
  - `Date_sale` → sales period
  - `Branch` → diferent branches
  - `Product` → product type
    `Quantity_Sold` → number of units sold  
  - `Unit_price` → price of units  
  - `Total_value` → total sales value  

## 🔎 Process
1. **Data Cleaning**  
   - Handled missing values.  
   - Replaced null prices with average values by product category.  
   - Removed duplicates and ensured consistent formats.  

2. **Exploratory Data Analysis (EDA)**  
   - Quantity sold per product, month  and branch.
   - Value sold per product, month and branch.
   - Best-selling product
   - Branch that sold the most
   - Month with the best sales

## 📈 Results
- Clear positive correlation between units sold and sales value.  

## 📂 Repository Structure
-	Raw dataset -> Prueba_python.csv
-	Cleaned dataset -> sales_complete.csv
-	Jupyter Notebook with Python code -> Sales.ipynb
-	Power BI Dashboard -> sales_produts Dashboard.pbix / sales_produts Dashboard PDF.pdf
-	Data Insights Presentation -> PT Analysis of Product Sales.pdf
