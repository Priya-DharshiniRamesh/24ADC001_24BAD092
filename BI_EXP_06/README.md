# Business Intelligence Lab – Experiment 6
## Integrate Data from Various Sources for Comprehensive Analysis using Tableau & Power BI

This repository contains the implementation of **Business Intelligence Experiment 6**, where Tableau and Power BI were used to connect, combine, and model data from multiple disparate sources — Retail Sales data and Regional Sales Targets — to build a unified, comprehensive dashboard.

---

## 🎯 Objective

To connect to, combine, and model data from multiple disparate sources in **Tableau** and **Power BI** to create a unified, comprehensive dashboard for holistic analysis.

---

## 🛠️ Tools Used

- Tableau Desktop
- Microsoft Power BI Desktop
- Power Query
- Data Relationships
- DAX Measures

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `TABLEAU EXP-6.twb` | Tableau workbook integrating Sales Data and Regional Targets |
| `Power BI EXP-6.pbix` | Power BI report with a modeled relationship between both datasets |
| `EX 6 (24BAD092).docx` | Lab record including pre-lab, in-lab, and post-lab exercises |

---

## 📊 Datasets

### Dataset 1: Retail Sales Data (CSV)

| Field | Description |
|-------|-------------|
| Order ID | Unique identifier for each order |
| Order Date | Date of the sales transaction |
| Region | Sales region |
| Sales | Sales revenue from the order |

### Dataset 2: Regional Sales Targets (Excel)

| Field | Description |
|-------|-------------|
| Region | Sales region (key used for relationship) |
| Sales Target | The sales goal for the region |
| Target Year | The year for which the target is set |

---

## 🔄 Data Preparation, Integration & Modeling

- Checked and corrected inconsistencies in region names across sources (e.g., "N. America" vs. "North America")
- Ensured correct data types (Sales Amount as numeric, Order Date as date)
- Handled missing values as needed
- **Tableau:** established a relationship between the Sales Data and Regional Targets tables using the common **Region** field. The relationship was used to integrate data from both sources for analysis.
- **Power BI:** created a relationship in Model view between the two tables on the *Region* column, with defined cardinality (many-to-one)

---

## 📐 Calculated Fields / Measures

- **Target Achievement %** = (SUM(Sales) / SUM(Sales Target)) × 100
- **Sales vs. Target Variance** = SUM(Sales) − SUM(Sales Target)

---

# 📊 Power BI Implementation

### Visualizations Created

- 📌 KPI Cards – Total Sales, Overall Target Achievement %
- 🎯 Gauge/Bullet Chart – Sales Performance vs. Target by Region
- 📊 Combined Bar Chart – Actual Sales vs. Target Sales by Region
- 🗺️ Map – Sales vs. Target Variance by Region

### Dashboard Features

- Cross-filtering across both data sources
- Relationship-based data model (many-to-one on Region)
- Highlights over/underperforming regions
- Interactive KPI summary

---

# 📈 Tableau Implementation

### Visualizations Created

- 📌 KPI Summary – Total Sales, Overall Target Achievement %
- 🎯 Bullet Chart – Sales Performance vs. Target by Region
- 📊 Combined Bar Chart – Actual Sales vs. Target Sales by Region
- 🗺️ Map – Sales vs. Target Variance by Region

### Dashboard Features

- Relationship created between Sales Data and Regional Sales Targets using the **Region** field
- Filters that update visuals from both integrated sources
- Data integrity validation through cross-checking

---

## 🚀 How to Open the Project

### Tableau

1. Open `TABLEAU EXP-6.twb`.
2. Load both the Sales Data (CSV) and Regional Targets (Excel) sources if prompted.
3. Explore the integrated dashboard and variance visuals.

### Power BI

1. Open `Power BI EXP-6.pbix`.
2. Refresh the dataset if required.
3. View the Model view relationship and the combined dashboard.

---

## 📚 Key Learning Outcomes

- Understood data integration in the context of Business Intelligence.
- Learned how to create relationships between multiple data sources in Tableau and data models in Power BI.
- Understood relationships and cardinality (one-to-one, one-to-many, many-to-many) in Power BI's data model.
- Recognized the importance of consistent naming conventions and correct data types when integrating multiple sources.
- Identified common data integration challenges: missing/inconsistent data, mismatched formats, duplicate records.
- Built calculated fields/measures that leverage multiple integrated datasets.
- Designed a comprehensive dashboard combining data from two disparate sources.

---

## 📈 Key Findings

- Integrating the Regional Sales Targets with the Sales data enabled comparison of actual performance against planned goals, not just raw sales figures.
- A relationship on the common *Region* field allowed Tableau and Power BI to combine both sources without merging the underlying data.
- Matching region names accurately across both datasets was the main challenge; careful data cleaning resolved this before modeling.
- Variance calculations (Sales vs. Target) made it easy to identify over- and underperforming regions for better resource allocation.
- The integrated dashboard provided deeper, context-rich insights that were not possible using a single data source alone.

---

## 📷 Dashboard Preview

### Power BI Dashboard

<img width="952" height="532" alt="image" src="https://github.com/user-attachments/assets/b3da4166-e7f3-4e2e-818f-9a0fcf1b54cf" />


### Tableau Dashboard

<img width="987" height="499" alt="image" src="https://github.com/user-attachments/assets/36b6b37a-ed5a-4b4d-9831-6d1a401b7d67" />



---

## ✅ Result

The retail sales and regional targets datasets were successfully connected, cleaned, and integrated in both Tableau and Power BI. By creating relationships between the sources, a unified data model was built. The resulting comprehensive dashboard visualized sales performance against set targets, enabling variance analysis and providing deeper, context-rich insights into regional performance that were not possible with a single data source.

---

## 👨‍💻 Author

**Priya Dharshini R**

- Register Number: **24BAD092**
- Department of Artificial Intelligence and Data Science
