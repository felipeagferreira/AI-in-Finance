# Optimal Stock Portfolio 

The goal of this project is to construct an optimal stock portfolio using the mean-variance portfolio optimization methodology. To achieve this we start by selecting a number
of publicly traded stocks that we use to construct our portfolio. Next we use Yahoo finance to download daily historical stock price data for all the stocks we have chosen. 

From this data we calculate the daily historical returns for each of the stocks and then use Excel to calculate the covariance matrix for this data. Since we use daily returns to calculate this covariance matrix we need to convert these covariances to annual values by multiplying our covariance matrix by 252 (the number of trading days in a year). 

Next we estimate the expected returns on all of the stocks we have chosen. Estimating expected future returns from historical data is extremely unreliable as the statistical confidence intervals will be large and often the results will be negative and therefore not realistic. So, again we use Yahoo Finance for the betas of all the stocks we have chosen, and then calculate the expected return on each stock according to the CAPM pricing model formula.  We assume that the risk free interest rate is 1.8% and assume that the expected return on the index is 7.8%.

We develop a mean-variance portfolio optimization tool and use this tool to calculate the efficient frontier of our portfolio. Next, we draw another efficient frontier but
this time we assume that we cannot borrow money for our investment and that we cannot short the stocks either. We overlay this efficient frontier onto the first one we created.


