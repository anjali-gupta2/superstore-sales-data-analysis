# superstore-sales-data-analysis
an interactive power BI dashboard and SQL analytics project for superstore sales data
# Superstore Sales Analytics & Executive Dashboard

## 📌 Project Overview
This end-to-end Data Analytics project focuses on analyzing the sales performance and profitability of a retail Superstore dataset. The goal is to clean messy transactional data, store it efficiently in a relational database, and build an interactive executive dashboard for business stakeholders.

---

## 🛠️ Tech Stack & Methodology

### 1. Data Cleaning (Microsoft Excel)
* Handled column width constraints and corrected timestamp visual formatting (`###` errors).
* Standardized text categorical features to prevent structural duplication.
* Exported the final dataset into a clean Comma-Separated Values (`.csv`) schema.

### 2. Database Management & ETL (MySQL Server)
* Designed a relational table structure with optimized data types (`VARCHAR`, `INT`, `DECIMAL`).
* Resolved complex data-loading pipeline bugs:
  * Handled the mixed date format issue (`MM/DD/YYYY` vs `DD-MM-YYYY`) using custom date conversion logic.
  * Overcame default security restrictions (`--secure-file-priv`) by staging data via the official system uploads path.
  * Handled anomalous blank data cells by writing conditional scripts to cast empty strings as integer `0` placeholders.

### 3. Data Visualization & UX (Power BI Desktop)
* Engineered an interactive executive-level operational dashboard.
* Maintained clean whitespace layout boundaries using a professional grid design pattern.
* Implemented modern **Tile Slicers** to enable instantaneous dynamic segment filtering (Consumer, Corporate, Home Office).

---

## 📊 Key Business Insights Uncovered
* **Revenue Drivers:** The *Technology* and *Furniture* product categories generate the highest gross sales revenue for the business.
* **Profit Hotspots:** Geographically, the *West* and *East* shipping zones (specifically heavy clusters in California and New York) are yielding maximum profit margins.
* **Core Customer Base:** The *Consumer* segment represents the highest density of retail transaction volumes.

---

## 📂 Repository Contents
* `superstore.csv`: The cleaned transactional raw dataset used for analysis.
* `Superstore_Sales_Dashboard.pbix`: The final Power BI production dashboard file.
*
