Financial Ratios Analysis Tool

This repository provides a Python-based tool for retrieving and analyzing financial ratios of publicly traded companies using historical financial data from Yahoo Finance. The tool focuses on calculating three key financial ratios — Current Ratio, Gross Profit Ratio, and Return on Investment — and comparing them to industry standards.

Features

Retrieve historical financial data: Automatically pulls balance sheet and income statement data for specified companies.

Calculate financial ratios: Computes Current Ratio, Gross Profit Ratio, and Return on Investment.

Compare against industry standards: Assess company performance relative to user-defined benchmarks.

Visualization: Generate line plots to visualize ratio trends over time.

Getting Started

Prerequisites

Ensure you have the following libraries installed:

pandas for data manipulation

yfinance for fetching financial data

matplotlib for plotting

Install them using pip if necessary:

pip install pandas yfinance matplotlib

Usage

Retrieve Fiscal Year Dates:

balance_sheet_dates, income_statement_dates = get_last_n_fiscal_year_dates('AAPL', 2023, 5)

Fetch Financial Data:

balance_sheet_data, income_statement_data = get_financial_data('AAPL', balance_sheet_dates)

Calculate Financial Ratios:

current_ratio = calculate_current_ratio(balance_sheet_data)
gross_profit_ratio = calculate_gross_profit_ratio(income_statement_data)
roi = calculate_return_on_investment(balance_sheet_data, income_statement_data)

Calculate Ratios for Multiple Companies:

companies = ['AAPL', 'GOOGL']
results_df = calculate_ratios_for_companies(companies, 2023, 5, ['current_ratio', 'gross_profit_ratio', 'return_on_investment'])
print(results_df)

Compare with Industry Standards:

industry_standards = {'current_ratio': 1.5, 'gross_profit_ratio': 0.4, 'return_on_investment': 0.1}
compare_with_industry(results_df, industry_standards)

Plot Financial Ratios:

plot_ratios(results_df)

Example Execution

Run the script and input the required parameters:

python financial_ratios.py

You’ll be prompted to enter:

Industry standards for the ratios

Starting fiscal year

Number of years to retrieve

Company tickers (comma-separated)

Error Handling

Make sure to input valid numeric values where prompted.

Ensure company tickers are correct and active on Yahoo Finance.

Contribution

Feel free to fork this repository and submit pull requests. Contributions for additional financial ratios or other improvements are welcome!

License

This project is licensed under the MIT License.

Let me know if you'd like me to tweak anything! What do you think?

