# Customer Churn Analysis

An end-to-end customer churn analysis project using Python, pandas, SQLite, and data visualizations. It cleans and combines customer, subscription, and support data, then explores churn patterns and related customer metrics.

## Project contents

- `data_raw/` — raw SQLite database and exported CSV
- `notebooks/01_data_cleaning_and_analysis.ipynb` — data cleaning, feature engineering, analysis, and exports
- `notebooks/02_data_visualization.ipynb` — visual exploration of the processed data
- `Final_Data_Insights/Data_Insights.ipynb` — churn visualizations by contract and plan type
- `Processed_data/processed/` — cleaned analysis CSV and SQLite database
- `portfolio/Customer_Churn_Analysis.ipynb` — portfolio version of the analysis

## Analysis

The notebooks examine:

- Overall churn and retention rates
- Churn by plan and subscription type
- Churn by state
- Average monthly charges and revenue associated with churn
- Customer tenure and support complaints
- Support escalations and churn
- Churn risk groups based on churn score

## Tools

- Python
- pandas and NumPy
- Matplotlib and Seaborn
- SQLite
- Jupyter Notebook

## Getting started

1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
