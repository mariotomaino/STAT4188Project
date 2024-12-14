# Investment Portfolio Optimization

## Objective:

The objective of my final project is to optimize an investment portfolio. My goal is to maximize returns while minimizing risk by optimizing a portfolio of assets.

Throughout this project, I will build an optimized investment portfolio of five stocks by analyzing historical asset performance as well as recent market trends and applying Modern Portfolio Theory.

Modern Portfolio Theory (MPT) is a framework for constructing an investment portfolio that maximizes returns for a given level of risk and minimizes risk for a given level of expected return. It was introduced by economist **Harry Markowitz** in 1952 in his paper *Portfolio Selection* and later earned him a Nobel Prize in Economics.

MPT suggests that the top stocks to include in a potfolio are not selected independently but based on their effectiveness in maximizing the overall portfolio's risk-adjusted return.

We want to focus on the following characteristics:
1. ***Expected returns***: We want stocks with high potential returns.
2. ***Volatility (Risk)***: We want stocks with manageable levels of risk.
3. ***Correlation***: We want stocks that are not highly correlated with each other.

Therefore, the assets that I will be analyzing are stocks from five different sectors that often perform well in MPT-based portfolios.

The assets that I will be analyzing are as follows:

### - *Technology:* **AAPL (Apple)** 

Apple has strong fundamentals and consistent returns, and is often used as a growth asset.

### - *Healthcare:* **JNJ (Johnson & Johnson)**

Johnson & Johnson is a defensive stock with steady cash flows, and has low correlation due to it being in a cyclical industry.

### - *Energy:* **XOM (Exxon Mobil)**

Exxon Mobil is a great asset for hedging, or aiming to  limit losses or inflation risk due to oil price volatility.

### - *Consumer Staple:* **PG (Procter & Gamble)**

Consumer staple stocks like Procter & Gamble maintain stability during economic downturns and lower volatility of the overall portfolio due to the fact that they manufacture every day items that consumers will need no matter what is happening in the world or the economy.

### - *Financials:* **JPM (JPMorgan Chase)**

Financial stocks provide stable returns and a broad exposure to financial markets.

By selecting these five assets for my investment portfolio optimization project, I have applied the Modern Portfolio Theory by implementing fundamental investment strategies such as diversification and risk minimization. Although I can only go so far with these strategies, so I will now use `yfinance` to pull the the necessary data for each stock ticker from Yahoo Finance's public APIs, and then use optimization/data cleaning tools such as `NumPy` and `Pandas` to further optimize my portfolio. I will use `Scipy` to optimize the weights of each asset in my portfolio, and determine their covariance. Lastly, using `Matplotlib` I will visualize an Efficient Frontier, which is essentially a model data that an investor can use to construct a portfolio based on their risk tolerance.


## Data Analysis/Conclusion

Upon the completion of this project I have created a way in which I can source the statistic of daily return percentage of a stock over a 20 year period. This might not seem like a big deal, but from this statistic we are able to extract key values from it such as daily average expected returns, the covariance, as well as the volatility of each asset. From this we are able to extract statistics that hold more weight, such as monthly return, annual return, and geometric annual return. 

After optimizing the weights of each asset, we are able to verify the covariance, which confirms our portfolios efficiency.

All of these statistics are significant because I have also created an Efficient Frontier that is simulated from 5000 random portfolios. This random frontier can be used to compare a potential portfolio to an extremely large set of potfolios. If an investor knows the Sharpe ratio of their investment portfolio, they can use this visual to easily make an informed investment decision.

## Results of Optimized Stock Portfolio:

### **AAPL (Apple)**:

Geometric Annual Return: 0.382923

Volatility: 0.020290

Covariance: Extremely low

### **JNJ (Johnson & Johnson)**:

Geometric Annual Return: 0.087720

Volatility: 0.010772

Covariance: Extremely low
 
### **XOM (Exxon Mobil)**:

Geometric Annual Return: 0.106372

Volatility: 0.016756

Covariance: Extremely low

### **PG (Procter & Gamble)**:

Geometric Annual Return: 0.104030

Volatility: 0.011370

Covariance: Extremely low

### **JPM (JPMorgan Chase)**:

Geometric Annual Return: 0.169875

Volatility: 0.022909

Covariance: Extremely low

**Sharpe Ratio of my Portfolio**: $\text{Sharpe = sum(return)/sum(risk)} = 0.85092/0.082097 = 10.3648$

It seems like my Sharpe Ratio is very off, and I am not sure why. However, based on these statistics, the assets I have chosen have a very high geometric annual return over the past 20 years, combined with very low volatilities and extremely low covariances as well. I believe that according to the model I have created, I have succeeded at creating an optimized investment portfolio.

Thank you for your time!
