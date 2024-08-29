# Pandemic Portfolio Optimization

The purpose of this project is to analyze the impact of the COVID-19 pandemic on stock performance within the S&P 500 index and to develop data-driven strategies for portfolio optimization based on clustering and machine learning techniques. By integrating multiple datasets, including COVID-19 case data, stock price information, and financial metrics, the project aims to understand how pandemic-related factors influenced stock prices and how investors could use these insights to make informed decisions. 
## Data Setting 

**1. Data on COVID-19:** This dataset includes the COVID-19 cases and deaths in 207 countries from December 2019 to October 2023. I want to observe how COVID-19 originating from Asia affects the US stock market and how the stock price was correlated with the COVID-19 numbers.  
**2. S&P 500 historical price:** It will be obtained through Kaggle. The dataset contains day-to-day open and close prices from 2010 to the present. I will calculate daily returns for the S&P 500 companies. Return is the key metric used in the project to build the portfolio.  
**3. List of S&P 500 companies:** This dataset contains the company name, symbol, sector, industry, market cap, and EBITDA. They are useful features because they combined price data to show the performance of companies in various industries during the pandemic, helping me develop the stock-picking strategy.  
**4. Stock information:** This dataset will be obtained through Yahoo Finance. Beta is the main information I need as it implies the diversification of the portfolio and allows me to use the CAPM to evaluate the portfolio.  
**5. Risk-free Rate:** This dataset will be obtained through Kaggle. The risk-free rate is an essential part of the CAPM formula and I use the 10-year treasury yield as the risk-free rate.
