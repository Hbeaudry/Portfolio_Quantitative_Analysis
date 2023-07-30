## Whale Analysis and Portfolio Performance

This repository contains a Jupyter Notebook named "whale_analysis.ipynb" that performs quantitative analysis on various investment portfolios and compares their performance with the S&P 500 market index. The analysis is carried out in three main sections: Data Preparation, Quantitative Analysis, and Sharpe Ratios, with an additional section on Custom Portfolio analysis.

## Data Preparation:
- CSV files containing historical financial data for each portfolio are read and converted into DataFrames using Pandas.
- Null values are identified and removed from the data.
- Daily returns are calculated from the closing prices of the S&P 500 market index.
- The Whale Returns, Algorithmic Returns, and S&P 500 Returns are combined into a single DataFrame, allowing for easy comparison of each portfolio's returns.

## Quantitative Analysis:
- Daily and cumulative returns for all portfolios are computed and visualized.
- Box plots are created to understand the distribution of returns for each portfolio.
- Standard deviation is calculated to assess the risk of each portfolio compared to the S&P 500.
- Annualized standard deviation is determined for each portfolio to facilitate longer-term risk analysis.
- Rolling standard deviation is computed and plotted using a 21-day window to observe changes in risk over time.
- Correlation analysis is conducted to identify portfolios that may have similarities with the S&P 500.
- Beta, a measure of a portfolio's sensitivity to market movements, is calculated and plotted for one selected portfolio.

## Sharpe Ratios:
- Sharpe ratios, a measure of risk-adjusted returns, are computed using daily returns.
- The Sharpe ratios are visualized using a bar plot to compare the performance of different investment strategies against the market (S&P 500) and the whale portfolios.

## Custom Portfolio:
- A custom portfolio is created using the Google Finance function.
- CSV files containing data for the custom portfolio are downloaded, and its returns are calculated.
- The custom portfolio's returns are added to the DataFrame, allowing for further analysis and comparison with other portfolios.

Overall, the notebook demonstrates a comprehensive analysis of investment portfolios and their performance relative to the S&P 500.
