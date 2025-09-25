# Godavari Valley Washim — Sales Analysis Dashboard
Excel-based sales analysis and dashboard for Godavari Valley Washim Farmer Producer Company Limited, including raw data, pivot tables, slicers, and visual charts.

# Sales Analysis Dashboard

## 📌 Overview
This project is an **Excel-based Sales Analysis Dashboard** built for  
**Godavari Valley Washim Farmer Producer Company Limited**.  
It provides insights into sales performance using raw transaction data,  
pivot tables, slicers, and interactive charts — all in a single, user-friendly dashboard.

---

## 🗂 Project Structure
| File/Folder | Description |
|-------------|-------------|
| `PROJECT_0.5.xlsx` | Main Excel workbook containing raw sales data, pivot tables, and dashboard |
| `README.md` | Project documentation |
| `assets/` *(optional)* | Screenshots or images of the dashboard for GitHub preview |

---

## 🛠 Tools & Techniques Used
- **Microsoft Excel (2016/2019/365)** – primary tool for data analysis & dashboard creation
- **Data Cleaning & Preparation:**
  - Removed duplicates, handled missing values
  - Standardized column names & formats (dates, numbers)
  - Applied data validation to avoid incorrect entries
  - Used text-to-columns and find/replace for data formatting
- **Pivot Tables** – aggregated sales by item, location, customer, and month
- **Pivot Charts** – created bar, column, and 3D pie charts for easy visualization
- **Slicers** – added interactive filtering for Item, Location, Month, and Day
- **Conditional Formatting** – highlighted key metrics (e.g., top sales, low performance)
- **Basic & Advanced Excel Formulas:**
  - SUMIFS, COUNTIFS, VLOOKUP/XLOOKUP for calculations
  - Derived calculated columns (e.g., total amount, average rate per MT)
- **Dashboard Design & Layout:**
  - Arranged charts and slicers in a clean, professional format
  - Added titles, legends, and data labels for clarity
  - Used consistent color scheme for better readability


---

## 🎯 Business Questions Answered
This dashboard helps answer:
- Which **items** contribute the most to total sales (by quantity & revenue)?
- Which **locations** are top-performing in terms of sales quantity?
- Who are the **top customers** by total purchase value?
- What is the **average rate per MT** for each item?
- What is the monthly trend of total purchase, total sales, and gross profit?

---

## 📊 Key Insights (Summary)
- **Top Item by Quantity:** Soyabean — 11,450 MT (major share of total sales)
- **Top Item by Revenue:** Soyabean — ₹49.47 Cr, followed by Chana — ₹37.69 Cr
- **Top Performing Locations:** Ro CSN, Shirvi, Kalmunri, Adgaon (together form bulk of sales)
- **Top Customer:** Goda Agro Tech Pvt. Ltd. — ₹3.52 Cr purchase value
- **Margins:** Gross profit is comparatively thin, indicating low per-unit margins


---

## 🚀 How to Use
1. Download and open `PROJECT_0.5.xlsx` in **Excel 2016+**.
2. Use the **slicers** (Item, Location, Month, Day) to filter data interactively.
3. To update data:
   - Add new rows in the `Sales` sheet.
   - Right-click a pivot table → **Refresh**, or click **Refresh All**.
4. Charts & KPIs on the dashboard will auto-update.

---

## 📂 Data Dictionary (Sales Sheet)
| Column | Description |
|--------|-------------|
| No | Serial number |
| Transaction Date | Date of transaction |
| Day | Day of the week |
| Month | Month name |
| Customer Name | Name of buyer |
| Item Name | Product sold (Soyabean, Chana, etc.) |
| UOM | Unit of measure |
| No.of Bags | Number of bags sold |
| Quantity | Total quantity in MT |
| Rate | Rate per MT |
| Amount | Total sale amount |
| Location | Location of sale |
| Division | Internal business division |

---

## 📌 Future Improvements
- Automate data updates using **Power Query** or Python (pandas + openpyxl)
- Add **KPI cards** for quick at-a-glance insights (e.g., total revenue, top item)
- Export dashboard to **Power BI** for more interactive visuals
- Include a **CSV version** of data for open-source analysis

---

## 📜 License
This project is open-sourced under the MIT License.  
You are free to use, modify, and share it with attribution.

---

## 👤 Author
**Tauheed Shaikh**  
*Finance Ops → Data Analytics | Learning SQL, Python, ML | Power BI Enthusiast*


