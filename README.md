# Assesment

# Trade Data Analysis
## Overview

This assignment focuses on analyzing trade data from the provided etrm_trades.csv file.
The tasks include data cleaning, exploration, and visualization to derive meaningful insights into trade patterns.

Files in this Assignment

etrm_trades.csv → Raw trade dataset containing trade details.

trade_analysis_report.pdf → Generated report with insights, graphs, and screenshots.

analysis_notebook.ipynb → Jupyter Notebook containing Python code for analysis.

supporting_images/ → Screenshots and visualizations used in the report.

## Steps Performed
1. Data Loading

Loaded trade data from etrm_trades.csv using pandas.

Verified dataset structure (rows, columns, dtypes).

2. Data Cleaning

Handled missing values where necessary.

Standardized column names for consistency.

3. Exploratory Data Analysis (EDA)

Identified number of trades, commodities, and trade IDs.

Calculated notional values and trade distributions.

4. Visualizations

Histogram: Distribution of notional values.

Commodity vs Trade ID Count: Bar chart to see trading activity per commodity.

Heatmap: Correlation of numerical fields.

5. Insights

Certain commodities dominate trade activity.

Notional value distribution shows concentration in specific ranges.

Positive correlation found between trade quantity and notional value.

Example Outputs
Histogram of Notional Values

Shows the frequency distribution of trade notionals.

## Heatmap

Highlights correlation between trade attributes.

Commodity vs Trade ID

Displays activity levels for different commodities.

## How to Run

Install dependencies:

pip install pandas matplotlib seaborn


Open the Jupyter Notebook:

jupyter notebook analysis_notebook.ipynb


Run cells sequentially to reproduce results.

Report (trade_analysis_report.pdf) will be generated automatically.

## Conclusion

This assignment demonstrated:

Reading and exploring CSV data with pandas.

Generating trade-related insights.

Creating professional visualizations.

Exporting results into a structured PDF report.
