This project analyzes historical stock data for six major technology companies: Apple (AAPL), Google (GOOG), Microsoft (MSFT), Amazon (AMZN), Netflix (NFLX), and Tesla (TSLA). By leveraging various Python libraries such as Pandas, YFinance, and Seaborn, the project gathers data, performs analysis, and generates visualizations to provide insights into stock performance over a one-year period.

Project Overview:

Data Collection

Using yfinance, the project collects daily stock data for the six technology companies between two specified dates. Data includes:

Open, High, Low, and Close prices

Adjusted Close prices

Volume of stock traded

Analysis Performed:

Descriptive Statistics: Calculated for each stock to summarize their performance metrics, including mean, standard deviation, and maximum/minimum values.

Closing Prices: Visualization of the stock’s adjusted closing prices to track overall price trends.

Volume Analysis: Insights into how the volume of stock traded fluctuates over time.

Moving Averages: The moving average for 7, 30, and 90-day periods was computed to smooth stock price trends.

Daily Returns: Calculation and visualization of daily return percentages for each stock, highlighting their volatility and risk.

Correlation Analysis: Examined the correlation between the closing prices of different stocks.

Results

Closing Prices:

<img width="472" alt="Screenshot 2024-09-16 at 6 54 19 PM" src="https://github.com/user-attachments/assets/6098c8f2-ec6c-41bb-b185-5df6452bfa2a">

Most stocks show an upward trend over the analyzed period except for TSLA, which exhibits high volatility and ends on a decline.
NFLX displays the strongest growth, with a substantial increase in its stock price toward the end of the period.

Volume of Sales:

<img width="475" alt="Screenshot 2024-09-16 at 6 54 03 PM" src="https://github.com/user-attachments/assets/8628398c-6924-4261-a8d3-f921028a393b">


AAPL and TSLA had significant trading volume spikes, especially in March and April.
AMZN and NFLX show a declining trend in trading volume over time.

Moving Averages:

<img width="473" alt="Screenshot 2024-09-16 at 6 53 46 PM" src="https://github.com/user-attachments/assets/00e41cc4-88ac-49e0-ba75-6a5de5cbb2a0">

The moving averages across different timeframes (7, 30, and 90 days) help identify stock price trends.
The stocks generally follow a positive trend, with some fluctuations, except for TSLA, which trends downwards in some periods.

Daily Returns and Risk:

<img width="476" alt="Screenshot 2024-09-16 at 6 53 30 PM" src="https://github.com/user-attachments/assets/4f4c0a5c-372d-4928-bc33-50a9dceb9a7d">


<img width="475" alt="Screenshot 2024-09-16 at 6 52 08 PM" src="https://github.com/user-attachments/assets/bd0ea40a-3ff1-43d1-a0a7-979894f6b5d5">

TSLA and NFLX show the highest volatility in daily returns, making them riskier stocks for short-term investments.
AAPL, GOOG, and MSFT show more stability, making them more suitable for long-term investors seeking consistent returns.

Correlation Analysis:
<img width="476" alt="Screenshot 2024-09-16 at 1 51 31 PM" src="https://github.com/user-attachments/assets/f5aa3818-9feb-4323-ad30-59370fd99682">

The analysis shows strong correlations between the performance of the tech stocks, with several stocks moving similarly during market trends.
