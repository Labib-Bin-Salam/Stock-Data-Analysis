# Stock Data Analysis

## Project Overview
This project involves a comprehensive analysis of stock data for four major technology companies: Apple (AAPL), Alphabet (GOOG), Microsoft (MSFT), and Netflix (NFLX). The analysis progresses from basic descriptive statistics to more complex time-series analysis, correlation studies, and a final risk-vs-return assessment. The goal is to derive meaningful insights into the performance, volatility, and inter-stock relationships to inform potential investment strategies.

## Problem Statement
In a dynamic market, investors need to understand the characteristics of individual stocks and how they relate to each other. This project addresses the challenge of interpreting raw stock data to identify key performance metrics, assess risk, and evaluate diversification opportunities.

## Project Objective
The primary objectives of this project are to:
1.  **Analyze Descriptive Statistics:** Calculate and interpret key metrics such as mean, standard deviation, and price ranges for each stock.
2.  **Conduct Time Series Analysis:** Visualize and interpret the price movements of each stock over time to identify trends and periods of high volatility.
3.  **Evaluate Volatility:** Quantify and compare the volatility of each stock using standard deviation and visualize it for a clear comparison.
4.  **Study Inter-stock Correlation:** Determine how the prices of the four stocks move in relation to one another to understand potential benefits for portfolio diversification.
5.  **Perform Risk vs. Return Analysis:** Plot the average daily return against the risk (standard deviation) to evaluate the risk-adjusted performance of each stock.

---

### Column Dictionary

| Column Name | Description |
| :--- | :--- |
| `Date` | The date of the trading day. |
| `Ticker` | The stock ticker symbol (e.g., AAPL, GOOG, MSFT, NFLX). |
| `Close` | The closing price of the stock on the given date. |
| `Open` | The opening price of the stock on the given date. |
| `High` | The highest price of the stock on the given date. |
| `Low` | The lowest price of the stock on the given date. |
| `Volume` | The total number of shares traded on the given date. |

---

## Key Insights from the Analysis

Based on the descriptive statistics, time-series visualizations, correlation matrix, and risk vs. return analysis, the following key insights were derived:

* **Risk and Volatility:** There is a significant difference in the volatility of the stocks. NFLX and MSFT were found to be far more volatile than AAPL and GOOG. NFLX had the highest standard deviation and showed the most dramatic price swings, confirming its status as the riskiest stock in the dataset.
* **Performance vs. Risk:** For the analyzed period, higher risk did not consistently lead to higher returns. MSFT delivered a positive average daily return despite its high volatility, making it an attractive option for risk-tolerant investors. In contrast, NFLX, while the riskiest, yielded a negative average daily return, indicating that its high volatility did not translate to positive gains during this specific timeframe.
* **Market Trends:** The time series analysis revealed that AAPL and GOOG were relatively stable but experienced a slight overall decline, resulting in negative average daily returns. This suggests a challenging market environment for these stocks during the period of analysis.
* **Portfolio Diversification:** The correlation matrix showed a strong positive correlation among AAPL, GOOG, and MSFT. This indicates that these stocks tend to move in tandem, and combining them may not provide significant diversification benefits. NFLX had a weaker correlation with the other three, suggesting it could potentially serve as a diversifying asset, although its high risk and negative return would be a critical consideration.

---

## Conclusion

This project successfully met its objectives by systematically analyzing the provided stock data. The final risk vs. return analysis effectively summarized the findings, highlighting the classic trade-off and revealing a nuanced picture where only one of the high-risk stocks (MSFT) yielded a positive return. The insights gained from this analysis are essential for understanding each stock's individual characteristics and their collective behavior, which is fundamental for making informed decisions regarding investment and portfolio management.
