# CodeAlpha_Task-2_Stock-Portfolio-Tracker
Here is the second task assigned by CODEALPHA.

# Objective:

Create a stock portfolio tracking tool that allows users to add, remove, and track the performance of their stock investments.

# Key Insights:

The provided code calculates the value of a stock portfolio using the "yfinance library". It defines a portfolio with specific stocks and their quantities, then fetches the latest prices for these stocks using the "yfinance API". The code creates a DataFrame to store the portfolio details, including ticker symbols, shares owned, current prices, and total values. The fetch_current_prices function retrieves the most recent closing prices for the specified stocks. Finally, the code calculates the total value of the portfolio by multiplying the number of shares by their current prices and sums up the total value, displaying it along with the DataFrame containing the detailed portfolio information.
