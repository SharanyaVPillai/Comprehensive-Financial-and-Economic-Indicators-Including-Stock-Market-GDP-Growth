# Comprehensive-Financial-and-Economic-Indicators-Including-Stock-Market-GDP-Growth
1. Project Overview
   This project analyzes the relationship between economic indicators, particularly GDP growth, and financial indicators such as stock market performance. Python libraries including Pandas are used for data     cleaning and analysis, while Matplotlib and Seaborn are used for data visualization. The objective is to understand how economic growth influences stock market trends.

2. Tools Used 
   • Pandas – Data cleaning and manipulation 
   • Matplotlib – Basic data visualization 
   • Seaborn – Advanced and statistical visualizations

3. Dataset
   Source: (https://deepdatalake.com/datasets.php.)
   Description: The dataset contains structured sales information with the following key columns: 
      This dataset contains 24 columns and 3000 rows.

           Date: Date on which the data was recorded
           Stock Index: Name of the stock market index (Dow Jones, S&P 500, NASDAQ)
           Open Price: Opening price of the stock index
           Close Price: Closing price of the stock index
           Daily High: Highest price of the index during the day
           Daily Low: Lowest price of the index during the day
           Trading Volume: Total number of shares traded
           GDP Growth (%): Growth rate of the economy
           Inflation Rate (%): Percentage increase in prices
           Unemployment Rate (%): Percentage of unemployed labor force
           Interest Rate (%): Central bank interest rate
           Consumer Confidence Index: Measure of consumer optimism
           Government Debt (Billion USD): Total government debt
           Corporate Profits (Billion USD): Profits earned by corporations
           Forex USD/EUR: Exchange rate between USD and EUR
           Forex USD/JPY: Exchange rate between USD and JPY
           Crude Oil Price (USD per Barrel): Price of crude oil
           Gold Price (USD per Ounce): Price of gold
           Real Estate Index: Index representing real estate market performance
           Retail Sales (Billion USD): Total retail sales value
           Bankruptcy Rate (%): Percentage of bankruptcies
           Mergers & Acquisitions Deals: Number of M&A deals
           Venture Capital Funding (Billion USD): Amount of venture capital investment
           Consumer Spending (Billion USD): Total consumer expenditure

4. Steps Followed 
      1. Imported the dataset using Pandas. 
      2. Cleaned the data by: 
         o Removing missing and duplicate values 
         o Converting date and numeric columns to proper formats 
      3. Performed exploratory data analysis (EDA) using Pandas. 
      4. Created visualizations using Matplotlib and Seaborn, such as: 
         o Line charts for Stock Close Price Over Time
         o Bar plot for Average GDP Growth by Stock Index 
         o Heatmaps for pattern analysis
         o Histogram – Distribution of Daily Stock Returns
         o Box Plot – Effect of Stock Index on Returns
         o Scatter Plot – GDP Growth vs Stock Returns
         o Subplots – Multiple Economic Indicators
      6. Interpreted the results to extract meaningful insights.

5. Key Insights
        o GDP growth shows significant variability over time, with periods of both economic expansion and contraction.
        o Stock market indices exhibit cyclical movements rather than a constant upward trend.
        o No strong linear relationship is observed between GDP growth and short-term stock market returns.
        o Daily stock returns are mostly centered around zero, with occasional extreme values indicating market volatility.
        o Macroeconomic indicators influence market behavior, but stock market performance is driven by multiple factors beyond GDP growth alone.

6. Visualizations
         o Line charts for Stock Close Price Over Time
         o Bar plot for Average GDP Growth by Stock Index 
         o Heatmaps for pattern analysis
         o Histogram – Distribution of Daily Stock Returns
         o Box Plot – Effect of Stock Index on Returns
         o Scatter Plot – GDP Growth vs Stock Returns
         o Subplots – Multiple Economic Indicators
   <img width="1481" height="745" alt="Screenshot 2026-01-07 112418" src="https://github.com/user-attachments/assets/b9f9853e-24bc-4c2a-8c6b-768616608fa1" />

7. Files Included
       Comprehensive Financial and Economic Indicators Including Stock Market & GDP Grow.csv - Raw dataset
       Main Project Final.ipynb - Pandas analysis and visualizations
       README.md – Project description and usage instructions

8. How to Use 
       1. Open Main Project Final.ipynb using Jupyter Notebook or JupyterLab. 
       2. Run the notebook cells step by step to view data cleaning, analysis and visualizations. 
       3. Modify the code to explore additional insights if needed.

9. Conclusion
       This project demonstrates how Python libraries such as Pandas, Matplotlib, and Seaborn can be effectively used to analyze financial and economic data. Through exploratory data analysis and visualization,          the project examined the relationship between GDP growth and stock market performance. The insights gained from this analysis highlight that stock market movements are influenced by multiple factors and           are not solely dependent on economic growth. Overall, this project shows how data-driven analysis can help in understanding market behavior and support informed financial decision-making.
   

   
