# USA Regional Sales Analysis

## 1. Overview

Managed end-to-end regional sales analytics, covering data ingestion, cleaning, exploratory analysis, and development of executive dashboards.

Turned transactional data into actionable insights that improved regional sales performance.

Used data ingestion and validation tools, along with BI platforms, to deliver executive reporting and interactive analytics.

---

## 2. Business Context

Sales leadership requires clear visibility into:

- Revenue distribution across regions
- Profitability by geography
- Category-level performance
- Time-based sales
- Margin leakage and inefficiencies

Core business questions addressed:

- Which region drives highest revenue?
- Which regions underperform on profitability?
- Are revenues concentrated in a product categories?
- Are there seasonal patterns?
- Where should management focus growth or cost optimization?

---

## 3. Architecture

**Data Flow:**

Raw Sales Data  
→ Python ingestion script (`ingestion_db.py`)  
→ Data validation and EDA (Jupyter)  
→ Power BI Dashboard  
→ Executive Insights  

Ensures reproducibility while maintaining clear separation of concerns.

---

## 4. Technology Stack

- Python
- Pandas
- NumPy
- Jupyter Notebook
   BI
- Logging-enabled ingestion pipeline

---

## 5. Repository Structure

```
USA-Regional-Sales-Analysis/
│
├── EDA (USA_Regional_Analysis).ipynb
├── EDA.ipynb
├── ingestion_db.py
├── ingestion_db.log
├── Final Dashboard.pbix
├── Dashboard (final).pbit
└── README.md
```

---

## 6. Data Processing

### Data Ingestion

- Automated structured loading via Python
- Execution logging for auditability
- Clean dataset prepared for analysis

### Data Cleaning

- Missing value handling
- Data type normalization
- Inconsistency removal
- Validation checks

All transformations are fully reproducible.

---

## 7. Exploratory Data Analysis

EDA focused on decision-relevant metrics:

- Revenue concentration by region
- Profit margin variance
- Category contribution analysis
- Time-series performance
- Outlier detection
- Distribution analysis

Findings informed dashboard KPI design.

---

## 8. Power BI Dashboard Capabilities

The interactive dashboard provides:

- Regional revenue comparison
- Profit and margin KPIs
- Category-level contribution breakdown
- Time-series trend visualization
- Interactive filtering
- Drill-down exploration

Designed for executive consumption.

---

## 9. Key Insights

1. Revenue distribution varies significantly across regions.
2. Some high-revenue regions show weaker profitability.
3. A limited number of categories drive the majority of sales.
4. Sales exhibit time-based variation.
5. Margin inconsistencies suggest cost inefficiencies in certain regions.

---

## 10. Business Value

This analysis enables:

- Regional performance benchmarking
- Profitability optimization
- Focused growth strategy
- Resource reallocation
- Automated executive reporting

---

## 11. How to Run

1. Run:

   ```bash
   python ingestion_db.py
   ```

2. Open:

   ```
   EDA (USA_Regional_Analysis).ipynb
   ```

3. Launch:

   ```
   Final Dashboard.pbix
   ```

   in Power BI Desktop.

---

## 12. Future Enhancements

- Predictive sales forecasting
- Regional clustering and segmentation
- Margin optimization modeling
- Automated ETL pipeline
- Cloud-hosted dashboard deployment

---

## 13. Summary

This project demonstrates a structured analytics workflow:

Data ingestion  
→ Data validation  
→ Exploratory analysis  
→ Executive visualization  

It converts raw transactional data into structured insights for business decision-making.
