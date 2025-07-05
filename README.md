# 🛒 Blinkit Grocery Sales & Outlet Performance Dashboard

A Power BI dashboard analyzing Blinkit's grocery sales, profit margins, product categories, and store performance across various city tiers and outlet types.

---

## 📌 Project Objective

To uncover sales patterns, profitability trends, and category performance across different store types, outlet sizes, and regions. The dashboard provides a comprehensive view of how Blinkit’s retail operations perform.

---

## 🛠 Tools & Technologies

- **Power BI** – Dashboard development & DAX  
- **Power Query** – Data cleaning & transformation  
- **Excel / Google Sheets** – Data source  
- **DAX** – KPI calculations  

---

## 📊 Dataset

The dataset includes product type, outlet size, city tier, sales, and profit data.

📄 [Click here to view the dataset (Google Sheets)](https://docs.google.com/spreadsheets/d/1zMoqDjJc9LD9g__K_7FchFot3f-sH-HU/edit?usp=sharing)

---
## 📊 Key Insights

🏪 Supermarket Type1 stores dominate in total sales across Tier 1 cities

🍞 Categories like Baking Goods and Breakfast lead in revenue

💸 Profit margins are below the ideal 50% target

🏙️ Older outlets in Tier 2 cities show stable sales despite small size

📈 Dashboard reveals profit gaps between outlet types and city tiers

---
## 📄 Project Files

- 📊 
 [Click here to view the Smart City Analysis Dashboard (PDF)](https://github.com/Anziya-AS/Sales-Profitability-Insights-BlinkIT-Retail-Analysis/raw/main/BlinkIT%20Dashboard.pdf )  
 
- 📂 [Power BI File (.pbix)](https://github.com/Anziya-AS/Sales-Profitability-Insights-BlinkIT-Retail-Analysis/blob/main/blankit.pbix)

---

## 🧠 Key DAX Measures

```DAX
-- Total Sales
Total Sales = SUM('Sales Data'[Sales])

-- Total Profit
Total Profit = SUM('Sales Data'[Profit])

-- Profit Margin
Profit Margin = DIVIDE([Total Profit], [Total Sales])

-- Average Sales per Outlet
Average Sales = AVERAGE('Sales Data'[Sales])
---

## 📂 Project Structure
BlinkIT-Grocery-Dashboard/
├── Blinkit_Grocery_Dashboard.pbix
├── Blinkit_Grocery_Dashboard.pdf
├── BlinkIT_Dashboard.png
├── README.md

---

## 👩‍💻 Created By

**Anziya A S**  
📍 Kerala, India  
💼 Data Analyst  
📫 anziyaanzarr90@gmail.com  
🌐 [GitHub Profile](https://github.com/Anziya-AS)

