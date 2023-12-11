
# Financial Data Analytics: AAPL, MSFT, PEP, TSLA, AMZN

This repository contains a Jupyter Notebook that provides an in-depth analysis of stock data from five major NASDAQ-listed companies - Apple (AAPL), Microsoft (MSFT), PepsiCo (PEP), Tesla (TSLA), and Amazon (AMZN) - covering a period from January 2020 to January 2023.

## Overview

The project aims to apply machine learning in finance by:
- Developing a momentum trading strategy.
- Backtesting the trading strategy.
- Evaluating and optimizing the strategy for better performance.
- Analyzing the post-COVID recovery across different industries.
- Constructing and optimizing a diverse stock portfolio.

## Key Features

1. **Data Acquisition**: Utilizes `yfinance` to fetch historical stock data.
2. **Pre-processing**: Involves cleaning and preparing the data for analysis.
3. **Momentum Strategy Development**: Implements a simple yet effective momentum trading strategy.To work on our momentum strategy for our 5 stocks, we calculate their risk measures, then inverse and normalise them so that the weightage given to each stock is inversely proportional to their risks. We then find the adjusted close for each day using the weighted sum for the stocks. (We take the respective weights for each stock, multiply it with the adjusted close for that day, and then add them to get the weighted adjusted close value for each day.)
4. **Backtesting**: Employs backtesting to evaluate the effectiveness of the trading strategy.
5. **Optimization**: Fine-tunes the strategy to enhance performance.
6. **Comparative Analysis**: Compares the recovery post-COVID among different stocks.
7. **Portfolio Construction**: Builds a diversified stock portfolio and optimizes it under various scenarios.

## Visualization and Insights

- Uses libraries like `matplotlib` and `seaborn` for visual analysis.
- Provides insights into the stock performance and strategy efficacy.

