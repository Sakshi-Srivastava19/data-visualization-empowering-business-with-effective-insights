#TATA GROUP- data-visualization-empowering-business-with-effective-insights
data visualization: empowering business with effective insights
# Retail Data Visualization - CEO & CMO Insights Dashboard

## 📊 Tool Used
Power BI (version X.X)  
File Format: `.pbix`

---

## 📁 Data Source
**Online Retail Dataset**  
[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail)

---

## 🧹 Data Cleaning Steps
Before building visuals, the following cleaning logic was applied using Power BI Query Editor:

1. **Filter out invalid data:**
   - Removed rows where `Quantity` < 1 (to exclude returns).
   - Removed rows where `UnitPrice` < 0 (data entry errors).

2. **Created new calculated column:**
   - `Revenue = Quantity * UnitPrice`

---

## 📌 Visuals Overview

### ✅ **Q1: Revenue Time Series - 2011 Only (CEO)**
- **Type:** Line Chart
- **Details:** Monthly revenue trend for 2011 to detect seasonal patterns.
- **Use:** Helps CEO forecast future performance and understand peak seasons.

---

### ✅ **Q2: Top 10 Countries by Revenue (excluding UK) (CMO)**
- **Type:** Clustered Bar Chart
- **Filters:**
  - Excluded `United Kingdom`
  - Applied `Top N filter` on `Country` based on Revenue
- **Details:** Shows top 10 international markets by revenue and quantity sold.

---

### ✅ **Q3: Top 10 Customers by Revenue (CMO)**
- **Type:** Sorted Bar Chart
- **Details:** Shows top 10 customers ranked by total revenue.
- **Use:** Helps identify VIP customers for targeted marketing.

---

### ✅ **Q4: Demand by Country (excluding UK) (CEO)**
- **Type:** Map Visual or Treemap
- **Filters:**
  - Excluded `United Kingdom`
- **Details:** Displays demand across all countries in one view.
- **Use:** Aids CEO in expansion planning based on product demand.

---

## 🔖 File Naming Convention
- Power BI File: `Retail_Dashboard.pbix`
- Each tab renamed as: `Q1`, `Q2`, `Q3`, `Q4` based on the respective questions.

---

## 🚀 Instructions to Run
1. Open `Retail_Dashboard.pbix` in Power BI Desktop.
2. Navigate to each tab (`Q1` to `Q4`) for visual insights.
3. Data model and transformations can be reviewed in **Power Query Editor**.

---

## 📬 Contact
Prepared by: *[SAKSHI SRIVASTAVA]*  
  

