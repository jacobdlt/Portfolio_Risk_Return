# Hedge Fund Analysis

## Overview

The purpose of this analysis is to evaluate the performance of 4 hedge funds based on NAV values from 2014-2020 (Soros FM, Paulson & Co., Tiger Global, Berkshire Hathaway)  for potential inclusion in client portfolios using key risk-management metrics such as returns, standard deviations, Sharpe ratios, and betas. 

### Performance

I analyzed the data to determine if any of the portfolios outperformed the broader stock market (S&P 500). 

1.) First I used the default Pandas `plot` function to visualize the daily return data of the four fund portfolios and the S&P 500.

2.) Secondly I used the Pandas `cumprod` function to calculate the cumulative returns for the four fund portfolios and the S&P 500.

3.) Lastly I used the default Pandas `plot` to visualize the cumulative return values for the four funds and the S&P 500 over time.

### Volatility

I analyzed the volatility of each of the four fund portfolios and of the S&P 500 Index using box plots.

1.) I ussed the Pandas `plot` function and the `kind="box"` parameter to visualize the daily return data for each of the four portfolios and for the S&P 500 in a box plot.

2.) I then used the Pandas `drop` function to create a new DataFrame that contains the data for just the four fund portfolios by dropping the S&P 500 column.

### Risk

I evaluated the risk profile of each portfolio by using the standard deviation and the beta.

1.) I used the Pandas `std` function to calculate the standard deviation for each of the four portfolios and for the S&P 500.

2.) I then calculated the annualized standard deviation for each of the four portfolios and for the S&P 500.

3.) I used the daily returns DataFrame and a 21-day rolling window to plot the rolling standard deviations of the four fund portfolios and of the S&P 500 index.

4.) Lastly I used the daily returns DataFrame and a 21-day rolling window to plot the rolling standard deviations of only the four fund portfolios.

### Risk-Return Profile

1.) I used the daily return DataFrame to calculate the annualized average return data for the four fund portfolios and for the S&P 500.

2.) I then calculated the Sharpe ratios for the four fund portfolios and for the S&P 500.

3.) Finally I visualized the Sharpe ratios for the four funds and S&P 500 in a bar chart.
