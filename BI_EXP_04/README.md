# Business Intelligence Lab – Experiment 4
## Transform Data to Suit BI Reporting Requirements & Design a KPI Dashboard using Tableau & Power BI

This repository contains the implementation of **Business Intelligence Experiment 4**, where Tableau and Power BI were used to transform raw COVID-19 data into a structured format suitable for BI reporting, and to design interactive dashboards with Key Performance Indicators (KPIs).

---

## 🎯 Objective

To transform COVID-19 data into a clean, structured format suitable for Business Intelligence (BI) reporting and to design interactive dashboards with Key Performance Indicators (KPIs) using **Tableau** and **Power BI**.

---

## 🛠️ Tools Used

- Tableau Desktop
- Microsoft Power BI Desktop
- Power Query
- Calculated Fields
- DAX Measures

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `TABLEAU EXP-4.twb` | Tableau workbook containing data transformation analysis and KPI dashboard |
| `Power BI EXP-4.pbix` | Power BI report with transformed data, KPI cards, and visualizations |
| `EX 4 (24BAD092).docx` | Lab record including pre-lab, in-lab, and post-lab exercises |

---

## 📊 Dataset

### COVID-19 Global Dataset

Sourced from inbuilt sources such as *Our World in Data* / CSV files containing country-level COVID-19 statistics.

### Fields Used

| Field | Description |
|-------|-------------|
| Date | Date of the report |
| Location | Country or region |
| New Cases | Daily reported cases |
| New Deaths | Daily reported deaths |
| People Vaccinated | Cumulative vaccinated count |
| Total Cases | Cumulative confirmed cases |
| Total Deaths | Cumulative deaths |
| Population | Total population of the country |

---

## 🔄 Data Transformation & Cleaning Steps

- Converted the *Date* column to a proper date format
- Handled missing/null values in *New Cases*, *Total Cases*, and other numeric fields
- Removed duplicate and unnecessary records
- Created calculated fields such as:
  - Daily Case Growth Rate
  - Case Fatality Rate
  - Vaccination Percentage
- Aggregated data by *Continent*, *Country*, and *Month* using SUM, AVERAGE, and MAX functions

---

## 📈 KPIs Designed

- ✅ Total Confirmed Cases
- ✅ Total Deaths
- ✅ Case Fatality Rate
- ✅ Vaccination Coverage (%)
- ✅ Daily Case Growth Rate

KPIs were computed using **DAX measures** in Power BI and **Calculated Fields** in Tableau.

---

# 📊 Power BI Implementation

### Visualizations Created

- 📈 Line Chart – Daily New Cases and Deaths
- 📊 Bar Chart – Country-wise Vaccination Progress
- 🗺️ Map – Regional Case Distribution
- 📌 KPI Cards – Total Cases, Total Deaths, Fatality Rate, Vaccination Coverage

### Dashboard Features

- Filters by continent and country
- Slicers by date range
- Interactive KPI cards
- Drill-down capable visuals

---

# 📈 Tableau Implementation

### Visualizations Created

- 📈 Line Chart – Daily New Cases and Deaths
- 📊 Bar Chart – Country-wise Vaccination Progress
- 🗺️ Map – Regional Case Distribution
- 📋 KPI Summary Dashboard

### Dashboard Features

- Interactive filters (continent, country)
- Date range interactivity
- KPI-driven summary view
- Data transformation validation

---

## 🚀 How to Open the Project

### Tableau

1. Open `TABLEAU EXP-4.twb`.
2. Load the COVID-19 dataset if prompted.
3. Explore the worksheets and KPI dashboard.

### Power BI

1. Open `Power BI EXP-4.pbix`.
2. Refresh the dataset if required.
3. View the interactive KPI report.

---

## 📚 Key Learning Outcomes

- Learned the role of data transformation in BI reporting.
- Applied common data cleaning techniques (removing duplicates, handling nulls, correcting inconsistencies, changing data types).
- Understood how Tableau and Power BI handle data aggregation using SUM, AVERAGE, COUNT, MIN, and MAX.
- Learned to design and compute KPIs using DAX (Power BI) and Calculated Fields (Tableau).
- Explored various chart types (bar, line, pie, scatter, map, heat map, KPI cards, gauge, funnel, waterfall, etc.) for effective visualization.
- Built interactive dashboards with filters and slicers for deeper data exploration.
- Understood the importance of publishing and sharing dashboards with stakeholders.

---

## 📈 Key Findings

- Data transformation improved the accuracy and consistency of the COVID-19 dataset.
- Converting date formats and handling missing values resolved most data quality issues.
- Calculated fields such as vaccination coverage and case fatality rate provided meaningful, decision-ready insights.
- Aggregating data by country and continent made regional comparisons easier.
- The **Vaccination Coverage KPI** offered the most valuable insight, clearly highlighting differences in pandemic response across countries.
- Interactive filters and slicers significantly improved the usability of both dashboards.

---

## 📷 Dashboard Preview

### Power BI Dashboard

<img width="999" height="570" alt="image" src="https://github.com/user-attachments/assets/7a968962-2009-4af9-bbdc-ec9e08d04fc7" />


### Tableau Dashboard

<img width="1001" height="502" alt="image" src="https://github.com/user-attachments/assets/82caf016-44b9-4924-9b45-93f10d577e7f" />


---

## ✅ Result

The COVID-19 dataset was successfully cleaned, transformed, and aggregated for BI reporting. KPIs such as Total Confirmed Cases, Total Deaths, Case Fatality Rate, Vaccination Coverage, and Daily Case Growth Rate were designed and visualized using Tableau and Power BI, resulting in interactive dashboards suitable for public health monitoring and communication.

---

## 👨‍💻 Author

**Priya Dharshini R**

- Register Number: **24BAD092**
- Department of Artificial Intelligence and Data Science

