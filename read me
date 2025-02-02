Financial Ratio Analysis Tool
This repository contains a Python script that retrieves financial data for specified companies using the yfinance library, calculates key financial ratios, and compares them against industry standards. The tool also provides visualizations of the ratios over time.

Features
Retrieve Financial Data: Fetches balance sheet and income statement data for specified companies using the yfinance library.

Calculate Financial Ratios: Computes key financial ratios such as:

Current Ratio

Gross Profit Ratio

Return on Investment (ROI)

Compare with Industry Standards: Allows users to input industry standards for each ratio and compares the company's performance against these benchmarks.

Visualize Data: Generates plots to visualize the trends of financial ratios over time.

Installation
To use this tool, you need to have Python installed on your system. Follow these steps to set up the environment:

Clone the repository:

bash
Copy
git clone https://github.com/your-username/financial-ratio-analysis.git
cd financial-ratio-analysis
Install the required libraries:

bash
Copy
pip install -r requirements.txt
The requirements.txt file should include:

Copy
pandas
yfinance
matplotlib
Usage
Run the script:

bash
Copy
python financial_analysis.py
Input the required data:

Industry Standards: You will be prompted to enter the industry standards for the following ratios:

Current Ratio

Gross Profit Ratio

Return on Investment

Starting Fiscal Year: Enter the starting year for the analysis.

Number of Years: Specify the number of years to retrieve data for.

Company Tickers: Enter the ticker symbols of the companies you want to analyze, separated by commas (e.g., AAPL, GOOGL).

View the results:

The script will output a DataFrame containing the calculated ratios for each company and fiscal year.

It will also generate plots for each ratio, showing the trends over time.

Finally, it will compare each company's ratios against the industry standards and print the results.

Example Output
DataFrame Output
Copy
   Company Fiscal Year  current_ratio  gross_profit_ratio  return_on_investment
0    AAPL  2023-09-30       0.988012            0.441311              0.616127
1    AAPL  2022-09-30       0.879356            0.433096              0.666994
2    AAPL  2021-09-30       1.074553            0.417794              0.549839
3    AAPL  2020-09-30            NaN                 NaN                   NaN
4   GOOGL  2023-12-31       2.096585            0.566250              0.249942
5   GOOGL  2022-12-31       2.377994            0.553794              0.222943
6   GOOGL  2021-12-31       2.928113            0.569398              0.287482
7   GOOGL  2020-12-31       3.066756            0.535784              0.171084
8   GOOGL  2019-12-31            NaN                 NaN                   NaN
Comparison with Industry Standards
Copy
AAPL in 2023-09-30 00:00:00: current_ratio is below industry standard (Company: 0.9880116717592975, Industry: 1.5).
AAPL in 2023-09-30 00:00:00: gross_profit_ratio is above industry standard (Company: 0.4413112957720756, Industry: 0.4).
AAPL in 2023-09-30 00:00:00: return_on_investment is above industry standard (Company: 0.6161268397415945, Industry: 0.1).
...
Plots
The script will generate plots for each ratio, showing the trends over time for each company.

Code Structure
Initialising Libraries: Import necessary libraries (pandas, yfinance, matplotlib).

Retrieving Fiscal Dates: Function to fetch fiscal year-end dates for a given company.

Retrieving Financial Data: Function to retrieve balance sheet and income statement data.

Calculating Ratios: Functions to calculate:

Current Ratio

Gross Profit Ratio

Return on Investment

Calculating Ratios for Multiple Companies: Function to compute ratios for a list of companies.

Comparing with Industry Standards: Function to compare company ratios with user-provided industry standards.

Plotting: Function to visualize the ratios over time.

Main Execution Block: Handles user input, executes the analysis, and displays results.

Contributing
Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
yfinance for providing an easy-to-use API for financial data.

pandas for data manipulation and analysis.

matplotlib for data visualization
