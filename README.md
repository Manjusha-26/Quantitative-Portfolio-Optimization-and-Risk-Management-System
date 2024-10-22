# Quantitative-Portfolio-Optimization-and-Risk-Management-System

### Project Overview:
This project focuses on **Quantitative Portfolio Optimization** using **Modern Portfolio Theory (MPT)**, aimed at maximizing returns for a given level of risk. The analysis utilizes various asset classes, including equities, commodities, and cryptocurrencies, and employs Monte Carlo simulations and optimization techniques to construct portfolios that achieve optimal returns and risk management.

### Key Objectives:
1. **Maximize Returns**: Construct portfolios that deliver the highest possible return for a given risk level using MPT principles.
2. **Minimize Risk**: Identify portfolios with the lowest possible risk (volatility) while maintaining acceptable returns.
3. **Diversify Assets**: Invest in a range of asset classes (equities, crypto, commodities) to reduce the overall portfolio risk.
4. **Compare Optimization Techniques**: Evaluate and compare the performance of portfolios generated through simulation versus optimization.

---

### Approach:
1. **Data Collection**: 
   - Historical price data for assets (AAPL, MSFT, BTC, TSLA, etc.) was collected using **Yahoo Finance** API from 2015-2022.
   
2. **Portfolio Returns**:
   - **Daily Log Returns**: Calculate the daily log returns of each asset.
   - **Annualized Returns**: Compute annualized returns based on daily log returns.
   
3. **Portfolio Volatility**:
   - **Covariance Matrix**: Construct a covariance matrix to evaluate asset correlations and calculate overall portfolio volatility.

4. **Monte Carlo Simulations**:
   - Generate **100,000 random portfolios** by assigning random weights to the assets and calculating each portfolio’s **expected return**, **volatility**, and **Sharpe ratio**.
   - **Efficient Frontier**: Plot the efficient frontier showing portfolios with optimal return-risk profiles.

5. **Optimization Techniques**:
   - **Maximize Sharpe Ratio**: Optimize portfolio weights to maximize the Sharpe ratio (risk-adjusted returns).
   - **Minimize Volatility**: Optimize portfolio weights to minimize risk while ensuring the portfolio meets return expectations.

6. **Global Minimum Volatility (GMV) Portfolio**:
   - Identify the portfolio with the least risk (volatility) using optimization techniques.

7. **Portfolio Performance Comparison**:
   - Compare the **Max Sharpe Ratio portfolio**, **Global Minimum Volatility portfolio**, and a benchmark **Equally Weighted Portfolio**.

---

### Key Results:
- **Global Minimum Volatility (GMV) Portfolio**:
  - **Return**: 7.03%
  - **Volatility**: 11.05%
  - **Sharpe Ratio**: 0.64

- **Maximum Sharpe Ratio (MSR) Portfolio**:
  - **Return**: 22.34%
  - **Volatility**: 18.61%
  - **Sharpe Ratio**: 1.20

### Visualizations:
1. **Monte Carlo Simulation**: Scatter plot of portfolios with expected returns versus volatility, colored by Sharpe ratio.
2. **Efficient Frontier**: A plot showing the optimal portfolios that maximize return for a given level of risk.
3. **Performance Comparison**: Cumulative return plot comparing the Max Sharpe Ratio portfolio, GMV portfolio, and the Equally Weighted portfolio.

---

### Conclusion:
- The **Max Sharpe Ratio portfolio** outperformed the equally weighted portfolio, delivering higher returns with better risk-adjusted performance.
- The **GMV portfolio** achieved the lowest risk, making it suitable for conservative investors.
- The **Efficient Frontier** provides a clear visual representation of optimal portfolios, aiding in strategic investment decisions.
  
This system is a powerful tool for investors to optimize portfolio allocation, balance risk and return, and improve decision-making through quantitative analysis.
