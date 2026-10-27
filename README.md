# Global-Superstore-Performance-Analysis-Power-BI
An interactive Power BI report that analyzes the sales, profit, and product performance of a global superstore from 2017 to 2020.

## 📌 Introduction

In this project, I analyze the performance of a global superstore using Power BI. The goal is to turn raw sales data into clear insights that help the business make better decisions: where to grow, where profit is lost, and which products to focus on.

## 📊 Key Numbers

| Total Sales | Total Profit | Orders | Profit Margin | Total Quantity |
|:---:|:---:|:---:|:---:|:---:|
| 2.30M | 598.6K | 5K | 26.06% | 38K |

## 📂 Data Source

- **Type:** open-source dataset in CSV format
- **Size:** 9,995 rows and 24 columns
- **Period:** 2017 to 2020
- **Content:** orders, customers, products, locations, sales, quantity, discount, and profit

## 🛠 Tools

- **Power BI Desktop:** Power Query, data modeling, DAX, dashboards
- **Excel / CSV:** first look at the data

---

## ⚙️ How the Analysis Was Made

### 1. Data Cleaning (Power Query)

- Loaded the CSV file and checked the quality of each column
- Set the correct data types (dates, decimals, whole numbers)
- Checked for duplicates and missing values
- Fixed text formatting and renamed columns with clear names
- Removed columns that were not needed

### 2. Data Modeling

- Created a **date table** to analyze the data by year, quarter, and month
- Linked the tables with **relationships**
- Added **calculated columns** where row-level values were needed
- Wrote **DAX measures** for the main indicators:
  - Total Sales
  - Total Profit
  - Profit Margin %
  - Total Quantity
  - Profit per Unit
  - Profit Last Year

### 3. Data Visualization

The report has 3 interactive dashboards, with slicers for **year** and **region**:

| Dashboard | What it shows |
|---|---|
| **Sales Performance** | Sales and profit over time, sales by category, sales by region |
| **Profitability** | Sales vs profit by sub-category, profit by segment, profit by region, margin by year |
| **Product Performance** | Sales by category and sub-category, top 10 products, bottom 10 by profit, margin by product |



##  Questions This Analysis Answers


1. How have sales and profit changed from 2017 to 2020?
2. Which region sells the most, and which region sells the least?
3. Which product category generates the most sales?
4. Which region and which customer segment bring the most profit?
5. How has the profit margin changed from year to year?
6. Which sub-categories sell a lot but make little profit?
7. What are the top 10 products by sales?
8. Which products make the least profit, and should we raise their prices or remove them?

---

## 💡 Key Insights

1. **The business is growing and getting more profitable.**
   Sales rose from 484K in 2017 to 733K in 2020, which is about 51% more. The profit margin also went up, from 23.41% to 27.43%.

2. **The East region makes the most profit, and the South makes the least.**
   The West sells the most, but the East earns more profit (31.85% of the total). The South is the weakest region, with only 17% of the profit.

3. **Some products sell well but keep very little profit.**
   The HON 5400 chairs have a margin of only 10.26%, and the letter opener only 7.70%. Many small items, like rubber bands and USB drives, earn almost nothing. Raising their prices or removing them could help.

---

## 📁 Project Structure

```
├── data/          # CSV dataset
├── dashboard/     # Power BI file (.pbix)
├── images/        # Dashboard screenshots
└── README.md
```

## ▶️ How to Use

1. Clone the repository: `git clone <your-repo-url>`
2. Open the `.pbix` file in **Power BI Desktop**
3. If asked, update the data source path to the CSV file in the `data/` folder
4. Use the year and region slicers to explore the dashboards

## 👤 Author

**Takfarines**
Data Analyst | SQL · Power BI · Excel
 https://github.com/mohtakfarinas-beep · mohtakfarines@gamil.com
Data Analyst | SQL · Power BI · Excel
 https://github.com/mohtakfarinas-beep · mohtakfarines@gamil.com
