# E-Commerce Sales Analysis & Customer Segmentation

Data Science Analyst - E-Commerce Internship (6-week project)
**Author:** Kriti Harsh

## Project Overview

This repository documents a 6-week data science project analyzing e-commerce transaction data to surface sales trends, seasonality, and customer purchasing behavior, culminating in customer segmentation, sales forecasting, and an A/B testing design.

**Dataset:** [Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
(UCI Machine Learning Repository) - ~1 million transactions from a UK-based online retailer, Dec 2009-Dec 2011.

## Repository Structure

```
.
├── docs/           Weekly deliverable reports (Word docs / PDFs)
├── notebooks/      Jupyter notebooks for each stage of analysis
├── src/            Reusable Python scripts (cleaning, feature engineering)
├── data/           Data folder (raw data not committed - see note below)
└── README.md
```

> **Note on data:** The raw dataset is not committed to this repository due
> to size. Download it from the UCI link above and place the file(s) in
> `data/raw/`. See `notebooks/01_data_acquisition.ipynb` for the exact
> loading steps.

## Weekly Progress

| Week | Deliverable | Status |
| --- | --- | --- |
| 1 | Market Analysis, Strategic Planning & Dataset Scoping | Complete |
| 2 | Data Collection, Cleaning, and Exploratory Analysis | Pending |
| 3 | Customer Segmentation and Behavioral Analysis | Pending |
| 4 | Predictive Modeling and Sales Forecasting | Pending |
| 5 | A/B Testing Strategy Design | Pending |
| 6 | Comprehensive Reporting and Visualization | Pending |

## Tools & Libraries

- Python (pandas, NumPy)
- scikit-learn (K-means clustering, forecasting utilities)
- Matplotlib, Seaborn
- Jupyter Notebook

## Methodology Summary

1. **Acquire** - load and structurally validate the raw transaction data.
2. **Clean** - handle cancellations, negative quantities, missing customer IDs, duplicates, and date formatting.
3. **Explore** - visualize revenue trends, seasonality, top products/
   categories, and country distribution.
4. **Segment / Analyze** - RFM scoring and K-means clustering to produce interpretable customer segments; sales forecasting; A/B testing design.
5. **Report** - synthesize findings into a final narrative report with visualizations and business recommendations.

Full detail for each stage is in the corresponding weekly report under
`docs/`.
