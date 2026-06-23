# Stove Usage Analytics Dashboard - Power BI

An interactive Power BI report analysing stove usage patterns across households and geographic locations. Built to demonstrate data modelling, DAX measures, and dashboard design skills using Microsoft Power BI.

---

## Report Overview

The report is structured across **three pages**, each focused on a different analytical lens:

| Page | Focus | Key Visuals |
|---|---|---|
| **Dashboard** | High-level KPIs & trends | KPI cards, line chart, column charts, map, scatter chart, slicers |
| **Household** | Household-level analysis | Donut chart, waterfall chart, gauge, funnel |
| **Location** | Geographic breakdown | Treemap, decomposition tree, area chart, combo charts |

---

## Data Model

The report uses a **star schema** with the following tables:

- **`stove_usage_fact`** - Core fact table containing stove usage metrics
- **`household`** - Dimension table with household-level attributes
- **`location`** - Dimension table with geographic/regional data
- **`date`** - Date dimension enabling time-intelligence analysis

---

## Tools & Skills Demonstrated

- **Microsoft Power BI Desktop** - Report design and publishing
- **Power Query (M language)** - Data ingestion, transformation, and cleaning
- **DAX (Data Analysis Expressions)** - KPI measures and calculated columns
- **Star Schema Modelling** - Fact and dimension table relationships
- **Data Visualisation** - Maps, decomposition trees, waterfall charts, scatter plots, and more
- **Interactive Filtering** - Slicers and cross-filtering across pages

---

## Repository Contents

```
├── data
├── screenshots
├── semantic model
├── stove_analytics.pbix   # Power BI report file
└── README.md
```
