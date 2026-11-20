# Customer Churn Analysis

An exploratory, end-to-end customer churn portfolio project using Python, pandas, SQLite, and data visualizations. The project cleans and combines customer, subscription, and support data, then explores churn patterns and related customer metrics.

## Business question

Which customer segments show higher churn, and what should the business investigate?

## Project contents

- `data_raw/` — raw SQLite database and exported CSV
- `notebooks/01_data_cleaning_and_analysis.ipynb` — data cleaning, feature engineering, analysis, and exports
- `notebooks/02_data_visualization.ipynb` — visual exploration of the processed data
- `Final_Data_Insights/Data_Insights.ipynb` — churn visualizations by contract and plan type
- `Processed_data/processed/` — cleaned analysis CSV and SQLite database
- `portfolio/Customer_Churn_Analysis.ipynb` — portfolio version of the analysis

## Project workflow

1. Clean and combine customer, subscription, and support data.
2. Calculate churn and retention rates.
3. Compare churn across contract, plan, subscription, and state segments.
4. Review cancellation reasons, monthly charges, tenure, support complaints, and escalations.
5. Summarize findings and identify follow-up questions for the business.

## Early findings

The working sample contains 21 customers, of whom 6 churned (28.6%). Monthly-contract customers had a 55.6% churn rate (5 of 9), compared with 8.3% for annual-contract customers (1 of 12). Basic-plan customers had a 60% churn rate (3 of 5).

These are exploratory results from a small sample, not conclusions about the broader customer base.

## Tools

- Python: pandas and NumPy
- Data visualization: Matplotlib and Seaborn
- Database: SQLite
- Environment: Jupyter Notebook

## Getting started

1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
