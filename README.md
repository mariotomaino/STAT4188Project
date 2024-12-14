# STAT 4188 Final Project: Stock Portfolio Optimization

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

- *Technology:* **AAPL (Apple)** 

Apple has strong fundamentals and consistent returns, and is often used as a growth asset.

- *Healthcare:* **JNJ (Johnson & Johnson)**

Johnson & Johnson is a defensive stock with steady cash flows, and has low correlation due to it being in a cyclical industry.

- *Energy:* **XOM (Exxon Mobil)**

Exxon Mobil is a great asset for hedging, or aiming to  limit losses or inflation risk due to oil price volatility.

- *Consumer Staple:* **PG (Procter & Gamble)**

Consumer staple stocks like Procter & Gamble maintain stability during economic downturns and lower volatility of the overall portfolio due to the fact that they manufacture every day items that consumers will need no matter what is happening in the world or the economy.

- *Financials:* **JPM (JPMorgan Chase)**

Financial stocks provide stable returns and a broad exposure to financial markets.

By selecting these five assets for my investment portfolio optimization project, I have applied the Modern Portfolio Theory by implementing fundamental investment strategies such as diversification and risk minimization. Although I can only go so far with these strategies, so I will now use optimization/data cleaning tools such as `NumPy` and `Pandas` to further optimize my portfolio. I will use `Scipy` to optimize the weights of each asset in my portfolio, and determine their covariance. Lastly, using `Matplotlib` I will visualize an Efficient Frontier, which is essentially a model data that an investor can use to construct a portfolio based on their risk tolerance.