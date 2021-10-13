# Stock Price Volatility Model Comparison

The goal of this project is to write a program to simulate the S&P using certain volatility models that we calibrate, which are: an EWMA model, the GARCH(1,1) model and the asymmetric GARCH model.  For each of these models we assume μ=.07 and simulate 1-year into the future where we use daily steps. We first conduct a large number of simulations using Python programming language, then we graph a histogram plot of the final annual returns for each model. Then we finally calculate and report the variance, skew and kurtosis of each of the simulated returns distributions and compare them to the normal distribution. Write a brief report summarizing your findings and provide your code as an appendix.  Pseudo code for such simulations can be found on slide deck 17 of slide deck 3.0cMMAI 823_VolatilityModelling


## Data

We use data from a file that has S&P data from July of 2013-Aug of 2018.

	

