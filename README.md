# 🥤 Coca-Cola USA Retailer Sales Dashboard

## 📌 Project Overview

This project presents an interactive **Microsoft Excel sales dashboard** for analyzing Coca-Cola beverage sales across US regions and retail partners. It transforms a retailer sales dataset into an executive reporting view that highlights sales performance, units sold, average unit price, operating profit, brand performance, retailer comparisons, and quarterly trends.

The dashboard is designed to help users explore how sales are distributed across beverage brands and retailers, compare 2022 with 2023, and review quarterly sales and operating profit margin.

> **Dashboard Preview:**
>
> <img width="1324" height="961" alt="Excel_CocaCola_Sales_Dashboard" src="https://github.com/user-attachments/assets/16bdc2ff-f056-4dea-81e4-f1227cfe83a6" />
>
> *The dashboard includes four KPI cards, a Region slicer, brand and retailer sales comparison tables, and a quarterly sales and operating profit margin chart.*

---

## 🗂️ Workbook Architecture

The workbook, `Excel_CocaCola_Sales_Dashboard.xlsx`, is organized into three worksheets:

1. **Data** – The source dataset containing retailer, retailer ID, invoice date, region, state, city, beverage brand, price per unit, units sold, total sales, operating profit, and operating margin.
2. **Analyze** – The analysis layer containing PivotTables for the headline KPIs, sales by beverage brand, sales by retailer, and quarterly sales and average operating margin.
3. **Dashboard** – The presentation layer containing the KPI cards, regional filter, year-over-year comparison tables, and quarterly combination chart.

---

## 🔄 Data Structure & Preparation

The `Data` worksheet contains **9,648 records** across **12 fields**, covering invoice dates from **January 1, 2022 through December 31, 2023**. The source data is formatted as an Excel table (`Table1`), providing a structured range for analysis.

The dataset includes the following analytical dimensions and measures:

- **Retailer details:** Retailer and Retailer ID.
- **Geography:** Region, State, and City.
- **Time:** Invoice Date.
- **Product:** Beverage Brand.
- **Sales measures:** Price per Unit, Units Sold, and Total Sales.
- **Profitability measures:** Operating Profit and Operating Margin.

The workbook uses the supplied dataset as its source. This README does not assume additional cleaning steps—such as removing duplicates, imputing missing values, or applying lookup-based transformations—that are not documented in the workbook.

---

## 📊 Key Metrics & Executive KPIs

The dashboard presents four headline metrics:

- **Total Sales:** The sum of sales across the dataset.
- **Units Sold:** The total quantity of beverage units sold.
- **Average Price:** The average price per unit.
- **Total Operating Profit:** The total operating profit generated.

### Regional, Brand & Retailer Analysis

- **Regional filtering:** The Region slicer provides five filter options: Midwest, Northeast, South, Southeast, and West.
- **Beverage brand performance:** Compares sales for Coca-Cola, Dasani Water, Diet Coke, Fanta, Powerade, and Sprite across 2022 and 2023.
- **Retailer performance:** Compares Amazon, BevCo, FizzyCo, Target, Walmart, and West Soda across the same two years.
- **Year-over-year variance:** Displays the difference between 2023 sales and 2022 sales for each brand and retailer.

### Quarterly Sales & Operating Profit Margin

The combination chart brings together two quarterly measures:

- **Quarterly Sales:** Displays total sales by quarter for 2022 and 2023 using columns.
- **Operating Profit Margin:** Displays average operating margin by quarter using a line.
- **Year comparison:** Presents Q1–Q4 for both years to make changes in sales and margin easier to review.

---

## 🖥️ Dashboard Features & User Experience

- **Executive KPI Cards:** Four prominent cards summarize Total Sales, Units Sold, Average Price, and Total Operating Profit.
- **Interactive Region Slicer:** Filters the dashboard by the five available US regions.
- **Sales by Beverage Brand:** A comparison table shows 2022 sales, 2023 sales, and variance for each beverage brand.
- **Sales by Retailer:** A second comparison table presents the same year-over-year measures for each retailer.
- **Conditional Formatting:** Variance values use in-cell data bars to make the size of year-over-year changes easier to scan.
- **Quarterly Combination Chart:** Combines sales columns with an operating profit margin line, using separate value scales.
- **Coca-Cola-Inspired Visual Design:** Uses a dark-blue dashboard background and headers, light-blue KPI cards, white text, and Coca-Cola branding.

---

## 🔎 Snapshot of Workbook Results

The following figures are the overall values visible in the supplied workbook before applying a different Region filter:

| KPI | Workbook value |
|---|---:|
| Total Sales | $12,016,665 |
| Units Sold | 24,788,610 |
| Average Price per Unit | $0.45 |
| Total Operating Profit | $4,722,497 |

The analysis sheet also shows total sales of approximately **$2.42 million in 2022** and **$9.59 million in 2023**. These are workbook snapshot values; slicer selections can change the figures displayed in the dashboard.

---

## 🛠️ Tools & Excel Features Used

- **Microsoft Excel:** Workbook development, data organization, analysis, and dashboard presentation.
- **Excel Tables:** Structured storage of the retailer dataset.
- **PivotTables:** Aggregation of KPI totals, brand sales, retailer sales, and quarterly measures.
- **PivotChart / Combination Chart:** Visualization of quarterly sales and operating profit margin.
- **Slicers:** Interactive regional filtering.
- **Cell Formulas:** Dashboard comparison values and year-over-year variance calculations linked to the analysis worksheet.
- **Conditional Formatting:** Data bars for visual comparison of variance values.
- **Dashboard Formatting:** KPI cards, aligned tables, chart styling, and a consistent Coca-Cola-inspired color palette.

---

## ⚙️ How to Use

1. Download `Excel_CocaCola_Sales_Dashboard.xlsx`.
2. Open the workbook in desktop **Microsoft Excel** for the intended PivotTable, chart, and slicer experience.
3. Navigate to the **Dashboard** worksheet.
4. Use the **Region** slicer to select a region and explore the filtered results.
5. Compare 2022 and 2023 sales by beverage brand and retailer.
6. Review the quarterly sales and operating profit margin chart.
7. Navigate to **Data** to inspect the source records and **Analyze** to review the supporting PivotTables.

*Note: The workbook contains PivotTables and slicer functionality. If the workbook is opened in software other than desktop Excel, some interactive features or formatting may behave differently.*

---

## 🎓 Learning Resource

The dashboard was developed with reference to the following YouTube tutorial:

[Watch the Excel dashboard tutorial](https://www.youtube.com/watch?v=GW6ZjK_9H6A)


