## Repository Structure

```
USA-Regional-Sales-Analysis/
│
├── EDA (USA_Regional_Analysis).ipynb   # Exploratory Data Analysis
├── EDA.ipynb                           # Supporting analysis
├── ingestion_db.py                     # Data ingestion script
├── ingestion_db.log                    # Execution logs
├── Final Dashboard.pbix                # Power BI dashboard file
├── Dashboard (final).pbit              # Power BI template file
└── README.md                           # Project documentation
```

## 6. Data Processing

### 6.1 Data Ingestion
- Automated data loading using Python.
- Logging enabled for traceability.
- Structured data prepared for analysis.

### 6.2 Data Cleaning
- Missing value handling.
- Data type corrections.
- Removal of inconsistencies.
- Feature validation.

---

## 7. Exploratory Data Analysis (EDA)

Key analytical steps:

- Revenue distribution analysis
- Regional performance comparison
- Trend analysis over time
- Category-level contribution
- Outlier detection
- Summary statistics

Insights from EDA informed the dashboard design.

---

## 8. Power BI Dashboard Features

The Power BI dashboard includes:

- Regional revenue comparison
- Profit and sales KPIs
- Category breakdown
- Time-series trend analysis
- Interactive filtering by region and category
- Drill-down capability for deeper insights

The dashboard enables executive-level decision making with minimal manual analysis.

---

## 9. Key Insights

1. Certain regions consistently outperform others in total revenue.
2. Profit margins vary significantly across regions.
3. A small number of categories drive majority of revenue.
4. Seasonal or time-based patterns affect sales distribution.
5. Some regions show high revenue but lower profitability, indicating cost inefficiencies.

---

## 10. Business Impact

This analysis supports:

- Regional sales strategy optimization
- Targeted growth initiatives
- Profitability improvement planning
- Resource allocation decisions
- Executive reporting automation

---

## 11. How to Use

1. Run `ingestion_db.py` to process raw data.
2. Open `EDA (USA_Regional_Analysis).ipynb` for analysis walkthrough.
3. Open `Final Dashboard.pbix` in Power BI Desktop to explore the interactive dashboard.

---

## 12. Future Improvements

- Predictive sales forecasting
- Profit optimization modeling
- Regional clustering analysis
- Automated data pipeline
- Cloud deployment of dashboard

---

## 13. Conclusion

This project demonstrates end-to-end analytics workflow: ingestion, cleaning, exploration, and visualization. It converts raw transactional data into structured, decision-ready insights suitable for business leadership.
