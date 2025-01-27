# Data Analysis and Visualization for Financial Transaction Data

## Project Overview

This project focuses on analyzing and visualizing financial transaction data to extract meaningful insights about user behavior, spending habits, and financial indicators. The dataset combines multiple data tables, consolidates them, and performs an in-depth analysis.

## Features

1. **Data Cleaning and Preparation**:
   - Standardized column names.
   - Parsed dates and monetary values.
   - Sorted and filtered invalid entries.

2. **Data Categorization**:
   - Categorized transactions into types (e.g., Mortgage Payment, Salary Deposit, Credit Card, etc.).
   - Classified merchants into spending categories (e.g., Groceries, Online Shopping).

3. **Analysis Objectives**:
   - Identify whether a user has a mortgage, credit card, or ongoing projects.
   - Determine the user’s salary and its approximate amount.
   - Identify mobile phone providers and monthly bills.
   - Analyze monthly and daily spending patterns.

4. **Visualizations**:
   - Daily inflows vs. outflows trends.
   - Monthly spending by category (e.g., Groceries, Online Shopping).
   - Top spending vendors.

## Files and Notebooks

1. **Creating DB.ipynb**:
   - Contains the code for merging and cleaning the raw dataset.
   - Outputs a unified dataset for analysis.

2. **Visualization.ipynb**:
   - Includes Python scripts for data categorization and creating visualizations.
   - Generates graphs for daily and monthly financial trends.

3. **TestDataAnalyst.xlsx**:
   - Source file with raw financial transaction data.

4. **Joined_database.xlsx**:
   - Merged dataset from multiple tables, used for analysis.

5. **Exagen-report.pdf**:
   - A detailed report summarizing key insights and findings from the analysis.

## Requirements

- Python 3.12+
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, OpenPyXL

## Usage

1. Open the `Creating DB.ipynb` notebook to preprocess and consolidate the raw data.
2. Use the `Visualization.ipynb` notebook to analyze and visualize the data.
3. Refer to `Exagen-report.pdf` for a comprehensive analysis report.

## Key Insights

1. The user has a mortgage, identified through regular mortgage payments in the transaction data.
2. Regular large deposits indicate the user receives a salary, averaging approximately $2,174 per pay period.
3. The user has an active credit card and a Verizon mobile account, with an average monthly phone bill of $104.99.
4. Monthly spending trends show that groceries and online shopping dominate expenditures, with Costco being the most frequented grocery vendor.

## Future Improvements

- Enhance categorization using machine learning models.
- Automate the detection of recurring bills and payments.
- Expand visualization capabilities for better data storytelling.

## Author

- **Mojdeh Hosseini**  
  Email: mojdeh.h.hosseini@gmail.com
