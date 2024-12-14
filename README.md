# STAT 4188 Final Project: Stock Portfolio Optimization

## Objective:

The objective of my final project is to optimize an investment portfolio. My goal is to maximize returns while minimizing risk by optimizing a portfolio of assets.

Throughout this project, I will build an optimized investment portfolio of 5 stocks by analyzing historical asset performance as well as recent market trends and applying Modern Portfolio Theory.

Modern Portfolio Theory (MPT) is a framework for constructing an investment portfolio that maximizes returns for a given level of risk and minimizes risk for a given level of expected return. It was introduced by economist Harry Markowitz in 1952 in his paper "Portfolio Selection" and later earned him a Nobel Prize in Economics.

MPT suggests that the top stocks to include in a potfolio are not selected independently but based on their effectiveness in maximizing the overall portfolio's risk-adjusted return.

We want to focus on the following characteristics:
1. **Expected returns**: We want stocks with high potential returns.
2. **Volatility (Risk)**: We want stocks with manageable levels of risk.
3. **Correlation**: We want stocks that are not highly correlated with each other.

Therefore, the assets that I will be analyzing are stocks from five different sectors that often perform well in MPT-based portfolios.

The assets that I will be analyzing are as follows:

- **AAPL (Apple)** *Technology*
Apple has strong fundamentals and consistent returns, and is often used as a growth asset.

- **JNJ (Johnson & Johnson)** *Healthcare*
Johnson & Johnson is a defensive stock with steady cash flows, and has low correlation due to it being in a cyclical industry.

- **XOM (Exxon Mobil)** *Energy*
Exxon Mobil is a great asset for hedging, or aiming to  limit losses or inflation risk due to oil price volatility.

- **PG (Procter & Gamble)** *Consumer Staple*
Consumer staple stocks like Procter & Gamble maintain stability during economic downturns and lower volatility of the overall portfolio due to the fact that they manufacture every day items that consumers will need no matter what is happening in the world or the economy.

By selecting these 5 assets for my investment portfolio optimization project, I have applied MPT by implementing fundamental investment strategies such as diversification and risk minimization. I can only go so far with these strategies however, so I will now use optimization/data cleaning tools such as NumPy and Pandas to further optimize my portfolio, as well as perform further exploratory data analysis by visualizing trends and relationships between these assets using Matplotlib and Seaborn. I will then use Scikit-learn to train a predictive machine learning model for stock price movements and returns.