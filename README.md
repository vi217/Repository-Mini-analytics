Analyzing the Impact of Macroeconomic Factors on Apple Stock Performance (2015–2024)
Project Overview
This project investigates the relationship between macroeconomic indicators and Apple Inc.'s stock price from 2015 to 2024. By applying multiple linear regression models and time series analysis, we uncover how factors like Real GDP Index, Inflation, and historical stock trends influence Apple’s stock price. The findings provide actionable insights for investment firms and financial analysts to optimize portfolio strategies.

Objectives
Identify which macroeconomic factors most influence Apple's stock price.
Examine how historical trends predict future stock values.
Provide actionable insights for portfolio adjustments in response to economic indicators.
Data Sources
Apple Stock Price: NASDAQ
S&P 500 Index: NASDAQ
Federal Funds Rate: Federal Reserve Economic Data (FRED)
Inflation Rate (CPI): U.S. Bureau of Labor Statistics
Monthly Real GDP Index: S&P Global
Data was aggregated, cleaned, and standardized for consistency and accuracy.

Files
Apple stock price.csv
Contains historical closing prices of Apple stock from 2015–2024.

FEDFUNDS.csv
Data on Federal Funds Rate provided by FRED.

Inflation rate.xlsx
Contains monthly Consumer Price Index (CPI) changes to measure inflation.

sp500_index.csv
S&P 500 index historical closing prices for benchmarking performance.

Aggregate_data.csv
Combined dataset integrating all macroeconomic indicators with Apple stock prices.

Mini analytics_Apple stock vs macro.ipynb
The main Python notebook implementing:

Data cleaning and EDA
Multiple regression models
Residual and autocorrelation analysis
Visualizations (trends, scatter plots, residual diagnostics)
Tools & Libraries
The following Python libraries were used for analysis and visualization:

Pandas: Data manipulation and cleaning
NumPy: Numerical operations
Matplotlib & Seaborn: Visualizations (line charts, scatter plots, regression lines)
Statsmodels: Regression modeling and summary statistics
Sklearn: Variance Inflation Factor (VIF) for multicollinearity checks
SciPy: Correlation analysis
Key Visualizations
Scatter plots with regression lines: Visualize relationships between Apple's stock price and macroeconomic variables.
Trend analysis: Line graphs showing historical trends for Apple’s stock price, Real GDP, and Inflation.
Residual analysis: Scatter plots for model diagnostics.
Key Findings
Real GDP Index positively influences Apple’s stock price, aligning with economic expansion trends.
Inflation negatively impacts Apple’s stock price, suggesting reduced consumer spending during high inflation periods.
Lagged stock price is a strong predictor of Apple’s future performance, supporting momentum strategies.
How to Run
Clone the repository:
bash
Copy code
git clone https://github.com/username/repository-name.git
cd repository-name
Install required libraries:
bash
Copy code
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
Open Mini analytics_Apple stock vs macro.ipynb in Jupyter Notebook or a similar Python environment.
Run each cell sequentially to reproduce the analysis and visualizations.
Conclusion
This project highlights the importance of macroeconomic indicators in predicting Apple’s stock price. Real GDP and inflation rates provide actionable signals for long-term investments, while historical trends enable short-term predictive strategies.

For further analysis, consider extending the model using ARIMA or VAR techniques for time series forecasting.
