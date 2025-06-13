
# Task 8 – Sales Performance Dashboard (Power BI)

## 📊 Objective
Create an interactive dashboard using Power BI Web to visualize sales performance across products, regions, and time periods based on Superstore data.

---

## 📁 Dataset
**File Name**: `task 8 superstore data.csv`  
**Source**: [Sample Superstore Dataset]  
**Fields Used**:
- Order Date
- Sales
- Category
- Region
- Product Name
- Sub-Category

---

## 🧰 Tools Used
- Power BI Web (app.powerbi.com)
- CSV (Uploaded as dataset)

---

## 🔧 Steps Performed

1. **Data Cleaning**  
   - Created a new column `MonthYear` in the dataset using Python prior to Power BI import for consistent monthly grouping.

2. **Power BI Setup**
   - Uploaded the CSV to Power BI Web.
   - Converted `Order Date` to `MonthYear` format using DAX where necessary.
   - Formatted fields and relationships.

3. **Visualizations**
   - **Line Chart**: Sales over Months (X: MonthYear, Y: Sales)
   - **Bar Chart**: Sales by Region (X: Region, Y: Sales)
   - **Donut Chart**: Sales by Category (Category, Sales)
   - **Slicer**: Region or Category filter for interactivity

4. **Formatting**
   - Applied conditional formatting and color gradients to highlight top-performing segments.
   - Customized axis types and sort orders.
   - Added a final page with key insights in a formatted textbox.

---

## 📌 Key Insights

- The West region recorded the highest sales, particularly in Q3.
- Technology was the top revenue-generating category across all regions.
- Peak sales occurred in November and December, likely due to holiday season demand.
- The South region had the lowest sales contribution, indicating scope for regional strategy changes.
- Furniture had high-value sales but lower frequency compared to Office Supplies.
- Sales growth was generally upward from Q2 to Q4 with dips in April and July.

---

