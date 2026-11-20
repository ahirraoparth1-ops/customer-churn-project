# Customer Churn Analysis

An exploratory customer churn portfolio project using Python, pandas, SQLite, and data visualizations. The project combines customer, subscription, and support data to identify churn patterns and suggest areas for further investigation.

## Business question

Which customer segments show higher churn, and what should the business investigate?

## Project contents

- `data_raw/` — raw SQLite database and exported CSV
- `notebooks/01_data_cleaning_and_analysis.ipynb` — data cleaning, feature engineering, and analysis
- `notebooks/02_data_visualization.ipynb` — visual exploration of processed data
- `Final_Data_Insights/Data_Insights.ipynb` — It is the final Insights of customer Churn
- `Processed_data/processed/` — processed analysis CSV and SQLite database


## Project workflow

1. Clean and combine customer, subscription, and support data.
2. Calculate churn and retention rates.
3. Compare churn across contract, plan, subscription, and state segments.
4. Review cancellation reasons, monthly charges, tenure, support complaints, and escalations.
5. Summarize insights and recommend follow-up actions.

## Key insights

- **Overall churn:** 6 of 21 customers churned, for an observed churn rate of **28.6%**.
- **Contract type:** Monthly-contract customers had a **55.6% churn rate** (5 of 9), compared with **8.3%** for annual-contract customers (1 of 12).
- **Plan type:** Basic-plan customers had a **60% churn rate** (3 of 5).

These are exploratory results from a small sample. They indicate where to investigate, not proven causes of churn or results that can be generalized to a larger customer base.

## Recommended action items

1. **Investigate the monthly-contract experience.** Review cancellation reasons, onboarding, pricing, and service issues for monthly customers. Test whether a renewal reminder or a suitable longer-term plan improves retention.
2. **Review the Basic plan.** Check whether Basic customers report specific feature gaps, pricing concerns, or support problems. Consider targeted improvements or plan recommendations based on customer needs.
3. **Use support data to guide follow-up.** Examine complaints and escalations among churned customers to identify recurring issues that can be addressed.
4. **Validate the patterns with more data.** Repeat the analysis on a larger, more representative dataset and compare churn rates over time before making major business decisions.
5. **Track results.** Monitor churn by contract and plan type after any retention changes to see whether the rates improve.

## Tools

- Python: pandas and NumPy
- Visualization: Matplotlib and Seaborn
- Database: SQLite
- Notebooks: Jupyter

## Getting started

1. Clone or download the repository.
2. Install Python and Jupyter Notebook.
3. Install the required packages:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
