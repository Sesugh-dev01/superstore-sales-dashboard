# Superstore Sales Dashboard

Analysis of 8,399 retail sales transactions to identify top-performing regions, product categories, and monthly revenue trends using Python.

![Superstore Dashboard](Screenshot.png)

## What I Did
- Loaded and cleaned 8,399 transactions across 21 columns
- Analysed total revenue by region, product category, and month
- Identified the top 10 best-selling products by revenue
- Mapped monthly sales trends from 2009 to 2012

## Key Findings
- The **West region** generated the highest total sales at **$3.6M**
- **Nunavut** had the lowest regional sales at **$116K** — a 31x gap, pointing to untapped regional opportunity
- **Office Supplies** had the highest order volume (4,610 orders) but lower average order value than Technology
- **Q4 consistently spiked** across all years — seasonal demand drives inventory decisions
- Technology had the highest average order value despite fewer orders than Office Supplies

## Business Recommendation
The West region is overperforming while several territories are significantly underleveraged. The business should investigate whether Nunavut's low sales reflect poor market fit, distribution gaps, or lack of local marketing — before expanding inventory investment in the West.

## Tools Used
Python · Pandas · Matplotlib · Jupyter Notebook

## Setup
```bash
pip install -r requirements.txt
jupyter notebook Sales_Dashboard.ipynb
```

## Dataset
[Sample Superstore dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) — Kaggle
