# Retail Sales Data Analysis (Python + Pandas)

## Project Overview
This project analyzes a curated subset of retail sales data to demonstrate a full analytics workflow in Python. The notebook walks through data cleaning, transformation, exploratory analysis, business questions, and visualization to generate actionable insights for decision-makers.

## Business Problem
Retail teams need to understand which product categories and customer segments drive revenue and profitability, how discounts impact margins, and whether sales are trending positively. This analysis answers those questions and surfaces opportunities for targeted growth and retention.

## Tools Used
- Python 3.9+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter (via `nbconvert` or Jupyter UI)

## Steps Performed
1. Data loading from a CSV file
2. Data cleaning: trim and standardize text fields, parse dates, clean numeric fields, and remove duplicates
3. Data transformation: create `order_month`, `ship_days`, `profit_margin`, and `sales_bucket`
4. Exploratory analysis: summary statistics and category/region/segment performance
5. Business questions: category leaders, discount impact, segment value, monthly trends, top customers
6. Visualizations: bar, line, scatter, and box plots

## Key Insights
- Technology drives the highest sales and strong profits, led by smartphones and accessories.
- Discounting shows a negative relationship with profit margin, suggesting aggressive discounts erode profitability.
- Consumer and Corporate segments contribute most of the revenue, while Home Office is smaller but steady.
- Sales trend upward into March, indicating early-year momentum.
- A small group of customers accounts for a large share of revenue, highlighting retention opportunities.

## How To Run The Project
1. Ensure Python 3.9+ is installed.
2. Install dependencies with `python3 -m pip install pandas numpy matplotlib seaborn jupyter`.
3. Execute the notebook with `python3 -m nbconvert --execute --to notebook --inplace sales_analysis.ipynb`.
4. Open the notebook in Jupyter or VS Code to view outputs and charts.

## Project Structure
- `sales_analysis.ipynb` - Main analysis notebook
- `data/retail_sales_sample.csv` - Sample retail sales dataset
- `README.md` - Project documentation
