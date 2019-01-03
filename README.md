
# Artificial Intelligence for Trading Nanodegree

# Portfolio Optimization

## Project: Smart-Beta and Portfolio Optimization

## Table of Contents

1. [Project Description](#description)
2. [Project Overview](#overview)
3. [Data](#data)
4. [Smart Beta Portfolio](#smart-beta)
5. [Portfolio Optimization](#portfolio_opt)
6. [Conclusion](#conclusion)
7. [Files](#files)
8. [Libraries](#lib)

<a id='description'></a>

### Project Description

**Smart beta** has a broad meaning, but we can say in practice that when we use the universe of stocks from an index, and then apply some weighting scheme **other than market cap weighting**, it can be considered a type of **smart beta fund**.  A Smart Beta portfolio generally gives investors exposure or "beta" to one or more types of market characteristics (or factors) that are believed to predict prices while giving investors a diversified broad exposure to a particular market. Smart Beta portfolios generally target momentum, earnings quality, low volatility, and dividends or some combination.

Smart Beta Portfolios are generally rebalanced infrequently and follow relatively simple rules or algorithms that are passively managed.  Model changes to these types of funds are also rare requiring prospectus filings with US Security and Exchange Commission in the case of US focused mutual funds or ETFs.. Smart Beta portfolios are generally long-only, they do not short stocks.

In contrast, a purely alpha-focused quantitative fund may use multiple models or algorithms to create a portfolio. The portfolio manager retains discretion in upgrading or changing the types of models and how often to rebalance the portfolio in attempt to maximize performance in comparison to a stock benchmark.  Managers may have discretion to short stocks in portfolios.

Imagine we're a portfolio manager, and wish to try out some different portfolio weighting methods.

One way to design portfolio is to look at certain accounting measures (fundamentals) that, based on past trends, indicate stocks that produce better results.  

For instance, we may start with a hypothesis that dividend-issuing stocks tend to perform better than stocks that do not. This may not always be true of all companies; for instance, Apple does not issue dividends, but has had good historical performance.  The hypothesis about dividend-paying stocks may go something like this: 

>Companies that regularly issue dividends may also be more prudent in allocating their available cash, and may indicate that they are more conscious of prioritizing shareholder interests.  For example, a CEO may decide to reinvest cash into pet projects that produce low returns.  Or, the CEO may do some analysis, identify that reinvesting within the company produces lower returns compared to a diversified portfolio, and so decide that shareholders would be better served if they were given the cash (in the form of dividends).  So according to this hypothesis, dividends may be both a proxy for how the company is doing (in terms of earnings and cash flow), but also a signal that the company acts in the best interest of its shareholders.  Of course, it's important to test whether this works in practice.

We may also have another hypothesis, with which we wish to design a portfolio that can then be made into an ETF. We may find that investors may wish to invest in passive beta funds, but wish to have less risk exposure (less volatility) in their investments.  The goal of having a low volatility fund that still produces returns similar to an index may be appealing to investors who have a shorter investment time horizon, and so are more risk averse.

So the objective of this proposed portfolio is to design a portfolio that closely tracks an index, while also minimizing the portfolio variance.  Also, if this portfolio can match the returns of the index with less volatility, then it has a higher risk-adjusted return (same return, lower volatility).

Smart Beta ETFs can be designed with both of these two general methods (among others): alternative weighting and minimum volatility ETF.

<a id='overview'></a>

### Project Overview
In this project, I will build a smart beta portfolio and compare it to a benchmark index. To find out how well the smart beta portfolio did, I’ll calculate the tracking error against the index. I’ll then build a portfolio by using quadratic programming to optimize the weights. My code will rebalance this portfolio and calculate turn over to evaluate the performance. I’ll use this metric to find the optimal rebalancing Frequency.

<a id='data'></a>

### Data

For the dataset, we'll be using the end of day from [Quotemedia](https://www.quotemedia.com).

Udacity doesn't have a license to redistribute the data to us. They are working on alternatives to this [problem](https://github.com/udacity/artificial-intelligence-for-trading/#no-data).

<a id='smart-beta'></a>

### Smart Beta Portfolio

<a id='portfolio_opt'></a>

### Portfolio Optimization

<a id='conclusion'></a>

### Conclusion

<a id='files'></a>

### Files

<a id='lib'></a>

### Libraries