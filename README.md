Apple Stock Price Analysis
This project investigates the macroeconomic factors influencing Apple's stock price from 2015 to 2024. The analysis leverages datasets related to Apple stock price, economic indicators (like the Federal Funds Rate, inflation, and GDP), and various data visualization and econometric techniques.

📁 File Structure
1. Aggregate_data.csv
Description: Consolidated data file combining all key macroeconomic indicators and Apple’s stock prices.
Contents:
Apple Stock Price
Fed Funds Rate
Inflation Rate
Real GDP Index
S&P 500 Index
2. Apple stock price.csv
Description: Historical Apple stock prices from 2015 to 2024.
Source: NASDAQ or other financial platforms.
3. FEDFUNDS.csv
Description: Federal Funds Rate data representing interest rate changes over the selected time period.
Source: Federal Reserve Bank of St. Louis (FRED).
4. Inflation rate.xlsx
Description: Monthly inflation rates in percentage format.
Source: U.S. Bureau of Labor Statistics (BLS).
5. sp500_index.csv
Description: Historical S&P 500 Index values representing broader market trends.
Source: S&P Global/NASDAQ.
6. Mini analytics_Apple stock vs macro.ipynb
Description: Jupyter Notebook containing:
Exploratory Data Analysis (EDA)
Data Cleaning and Preprocessing
Multiple Linear Regression models
Residual Analysis and Visualization
Business Insights and Visualizations
📊 Overview of Analysis
The project analyzes the relationships between Apple's stock price and macroeconomic factors:

Inflation: Assessing the impact of rising prices on stock performance.
Federal Funds Rate: Examining the influence of interest rates on stock prices.
GDP Index: Analyzing how economic growth correlates with Apple’s performance.
S&P 500 Index: Identifying market-wide trends affecting Apple’s stock.
🛠 Technologies & Libraries Used
Python (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn)
Jupyter Notebook for code development and documentation.
Excel for basic data storage and formatting.
🚀 How to Run the Project
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/yourproject.git
Install the required libraries:
bash
Copy code
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
Open the Jupyter Notebook:
bash
Copy code
jupyter notebook "Mini analytics_Apple stock vs macro.ipynb"
Run each cell sequentially to reproduce the analysis.
🔍 Insights
The most influential macroeconomic factors for Apple stock price.
The role of lagged stock prices in predicting future performance.
Visualizations that highlight relationships between Apple’s stock price and economic indicators.
📄 Conclusion
This project provides actionable insights for investment firms to:

Monitor economic indicators like GDP growth and inflation.
Use historical stock prices for predictive analysis.
Adjust portfolios based on economic trends.
