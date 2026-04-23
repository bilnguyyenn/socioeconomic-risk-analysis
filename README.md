# U.S. County-Level Obesity Trends & Socioeconomic Risk Factor Analysis

## Objective
This repository contains a data analysis project exploring the relationship between socioeconomic risk factors and public health outcomes across United States counties. The primary goal is to investigate how financial demographics and local food environments correlate with adult obesity rates, transforming raw demographic data into actionable public health insights.

## Methodology
* **Language:** Python
* **Libraries:** `pandas`, `requests` (for API data collection), `matplotlib`/`seaborn` (for visualization)
* **Techniques:** Data Cleaning, DataFrame Merging (via FIPS codes), API Integration, Quartile Binning, Correlation Analysis
* **Data Sources:** United States Census Bureau & USDA Food Environment Atlas

## Repository Contents
* `socioeconomic_risk_analysis.ipynb`: The core Jupyter Notebook containing the Python code for data parsing, cleaning, merging, and the derivation of key insights.
* `Project_Summary_One_Pager.pdf`: A high-level executive summary detailing the methodology, data sources, and final conclusions.
* `Project_Presentation.pptx`: The final slide deck used to present the data visualizations and public health findings.

## Key Insights
1.  **Income vs. Obesity Correlation:** Analysis revealed a moderate negative correlation between median household income and adult obesity rates. By segmenting counties into income quartiles, the data demonstrated a consistent drop in average obesity rates as community income tiers increased.
2.  **The "Food Swamp" Effect:** Surprisingly, areas classified as "food swamps" (possessing the highest ratio of fast-food restaurants to grocery stores) exhibited slightly lower average obesity rates than regions with greater grocery access, highlighting the complex, multi-variable nature of localized public health drivers.
