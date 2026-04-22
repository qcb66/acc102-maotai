Kweichow Moutai Financial Performance Analysis (2019–2024)
##1.Problem & User
This project analyzes key financial ratios of Kweichow Moutai from 2019 to 2024 to identify profitability, leverage, and operational efficiency trends. It is designed for students, investors, and analysts seeking a clear, data-driven view of the company’s financial health.
##2.Data
Source: Self-collected annual financial data from Kweichow Moutai’s public filings (2019–2024).
Access Date: April 2026.
Key Fields:
year: Fiscal year
revt: Total revenue (in 100 million RMB)
ni: Net income (in 100 million RMB)
at: Total assets
lt: Total liabilities
che: Cash and cash equivalents
cogs: Cost of goods sold
invt: Inventory
##3.Methods (main Python steps)
1.Data Loading & Preparation: Imported raw financial data into a pandas DataFrame.
2.Data Cleaning: Filtered the dataset to retain only the columns required for analysis.
3.Financial Ratio Calculation:
Net Profit Margin: (Net Income / Revenue) * 100
Return on Equity (ROE): (Net Income / (Total Assets - Total Liabilities)) * 100
Debt-to-Asset Ratio: (Total Liabilities / Total Assets) * 100
Inventory Turnover: Cost of Goods Sold / Year-End Inventory
4.Data Visualization: Created a 2x2 grid of line charts using Matplotlib to plot trends in all four ratios over the 6-year period.
##4.Key Findings
Consistently High Profitability: Kweichow Moutai’s net profit margin remained very high (above 48%) and stable over the period, demonstrating strong pricing power and cost control.
Strong and Stable ROE: Return on Equity stayed consistently above 30%, reflecting efficient use of shareholder capital to generate profits.
Ultra-Low Leverage: The debt-to-asset ratio remained extremely low (below 20%), indicating a conservative financial structure with minimal reliance on debt.
Declining Inventory Turnover: Inventory turnover showed a gradual downward trend, suggesting slower inventory movement, potentially due to intentional aging of premium liquor products.
Steady Revenue and Profit Growth: Both top-line revenue and bottom-line net income grew consistently year-over-year from 2019 to 2024.
##5.How to run
1.Environment Setup: Ensure you have Python 3 installed with the required libraries
2.Open the Notebook: Launch Jupyter Notebook or VS Code and open the provided .ipynb file.
3.Run All Cells: Execute the code cells in sequence. The script will automatically generate the dataset, clean the data, calculate the ratios, and display the final visualization.
##6.Product link / Demo
[1111_副本.ipynb](https://github.com/user-attachments/files/26963635/1111_.ipynb)
https://github.com/user-attachments/assets/dd01aa04-49fd-4448-8c7e-ecfb358093c5
##7.Limitations & next steps
Limitations: The analysis uses simplified year-end inventory instead of average inventory for turnover calculation, which may slightly understate efficiency.
External factors like macroeconomic conditions, regulatory changes, or industry competition are not included in this purely quantitative analysis.
The dataset is limited to the 2019–2024 period.
Next Steps: Extend the dataset to include more historical years and quarterly data.
Perform a peer-group comparison with other major Chinese liquor companies.
Add additional ratios (e.g., current ratio, quick ratio) to further assess liquidity.
Incorporate market data (stock price, P/E ratio) to link financial performance to market valuation.





















