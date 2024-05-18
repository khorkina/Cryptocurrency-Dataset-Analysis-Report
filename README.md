# Cryptocurrency-Dataset-Analysis-Report
Introduction
Cryptocurrency web scraping involves collecting data from various online sources such as exchanges, news websites, forums, and social media platforms. The collected data provides valuable insights into real-time prices, trading volumes, market sentiment, blockchain statistics, ICO details, and more. This report analyzes a comprehensive dataset consisting of 21,347 entries and 12 columns, detailing various aspects of different cryptocurrencies.

Dataset Overview

The dataset contains the following columns:

name: The name of the cryptocurrency.
abbr: The abbreviation or ticker symbol of the cryptocurrency.
crypturl: The URL for the cryptocurrency.
price: The current price of the cryptocurrency.
volume24hrs: The 24-hour trading volume.
marketcap: The market capitalization.
circulatingsupply: The circulating supply.
maxsupply: The maximum supply.
totalsupply: The total supply.
date_taken: The date when the data was collected.
Unnamed: 10 and Unnamed: 11: Empty columns without any data.

Data Cleaning:

Market Cap: The marketcap column was converted to numeric format after removing commas.
Date: The date_taken column was converted to datetime format for time series analysis.

Data Visualizations and Analysis:
  1) Distribution of Cryptocurrency Prices:
The prices of cryptocurrencies are highly skewed, with most cryptocurrencies priced below $100. This indicates a few high-value cryptocurrencies dominating the market.
![image](https://github.com/khorkina/Cryptocurrency-Dataset-Analysis-Report/assets/166530415/68f03f07-a616-4b04-a72d-d87b134e0382)

  2) Top 10 Cryptocurrencies by Market Cap:
The top 10 cryptocurrencies by market cap include well-known names like Bitcoin, Ethereum, and Binance Coin. These top cryptocurrencies hold a significant portion of the total market capitalization.
![image](https://github.com/khorkina/Cryptocurrency-Dataset-Analysis-Report/assets/166530415/587adb10-caf9-4f45-b246-6f1562dfdb5a)

  3) 24-Hour Trading Volume vs Price
There is a wide variation in trading volumes across different price ranges. Higher-priced cryptocurrencies tend to have higher trading volumes, indicating greater investor interest and activity.

  4) Market Cap Distribution
The market cap distribution is highly skewed, with a few cryptocurrencies having extremely high market caps. This further emphasizes the dominance of leading cryptocurrencies in the market.

  5) Top 10 Cryptocurrencies by Circulating Supply
The cryptocurrencies with the highest circulating supply include well-known coins like Ripple (XRP) and Stellar (XLM). These coins are designed for high-volume transactions.

  6) Correlation Heatmap
A heatmap of correlations between various attributes shows strong correlations between market cap, circulating supply, and total supply. Price and trading volume also show a positive correlation.

  7) Price vs Circulating Supply
The scatter plot of price versus circulating supply shows that cryptocurrencies with lower circulating supplies tend to have higher prices, likely due to scarcity.

  8) Price Time Series for Top Cryptocurrency
Analyzing the time series of the top cryptocurrency (Bitcoin) shows significant price fluctuations over time, reflecting the volatility of the cryptocurrency market.

  9) Max Supply Distribution
The max supply distribution shows that most cryptocurrencies have a predefined maximum supply, which impacts their long-term scarcity and value.

  10) Total Supply vs Market Cap
The scatter plot of total supply versus market cap highlights that cryptocurrencies with larger total supplies do not necessarily have higher market caps, indicating other factors influencing market value.

Conclusion:
This analysis provides insights into the characteristics and trends of the cryptocurrency market. Key findings include the dominance of a few major cryptocurrencies in terms of market cap and trading volume, the skewed distribution of prices and market caps, and the significant correlations between various attributes. Understanding these trends can help traders, analysts, and researchers make informed decisions and develop strategies in the evolving cryptocurrency landscape.
