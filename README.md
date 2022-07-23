## Description
This repository consists of a number of jupyter notebooks in which I analyze my own investment ideas and popular beliefs in finance.

## List of Contents

1. [Analyzing Gold](https://github.com/Jon-Nie/investment_ideas/blob/main/analyzing_gold.ipynb)
I discuss what variables drive the gold price and gold returns and whether gold is indeed a good portfolio diversifier, as often asummed.

2. Analyzing the Value Premium
*analyzing_the_value_premium.ipynb*
Many sceptics claim that the value premium is dead since it failed to return any premium during the last 20 years. I show that the opposite is true. The US value premium was largely driven by changing relative valuations of cheap and expensive stocks and the current value premium might be historically high.

3. Building Analyst Recommendation Portfolios
*building_analyst_recommendation_portfolios.ipynb*
I use publicly available data of analyst recommendations for a large sample of US stocks and analyze whether they could be used in real-time to construct stock portfolios that outperform its benchmark.

4. Bulding Commodity-Factor Portfolios
*building_commodity_factor_portfolios.ipynb*
I use commodity futures data and try to construct a portfolio in real-time with high exposure to the commodity momentum and roll premium.

5. Building Equity-Factor Portfolios
*building_equity_factor_portfolios.ipynb*
I use publicly available price and fundamental data for a large sample of US stocks and try to construct a portfolio in real-time with high exposure to common equity risk factors such as the value and profitability premium.

6. Exploiting the Variance Drag
*exploiting_the_variance_drag.ipynb*
The variance drag is the difference between the arithmetic mean return and geometric mean return, which is generally in the order of half the variance.
Given a large enough amount of variance, any asset with a positive arithmetic mean return can return a negative compunding return. This is particularly the case for 2x or 3x leveraged ETFs. I analyze whether one can profit from the variance drag by short selling high-variance inverse ETFs and I also give an exact solution under what characteristics of the underlying asset it is possible.

7. The Optimal Equity-Factor Allocation
*the_optimal_equity_factor_allocation.ipynb*
Depending on the model used, there are at least 5 factors to price equity risk. I compute the efficient frontier of those factors, derive historically optimal factor allocations and compare common Factor-ETFs to the efficient frontier.