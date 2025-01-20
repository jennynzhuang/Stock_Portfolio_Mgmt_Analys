# Portfolio Management and Performance Analysis
This project was created as part of the **Mathematics of Finance** class to construct, manage, and evaluate the performance of a financial portfolio. The project aims to provide hands-on experience with portfolio management concepts and financial metrics, leveraging tools like Python and Jupyter Notebooks.

## Project Overview
- **Initial Budget**: $1,000,000
- **Portfolio Composition**: 5 stocks
- **Duration**: Weekly tracking and analysis over the semester
- **Stocks Selected**:
  - Broadcom Inc. (AVGO)
  - Fidelity Blue Chip Growth Fund (FBGRX)
  - Alphabet Inc. (GOOGL)
  - Intuitive Surgical Inc. (ISRG)
  - Nvidia Corporation (NVDA)

## Key Features
1. **Portfolio Construction**:
   - Application of the Markowitz Model to determine optimal portfolio weights.
   - Focus on minimizing variance and achieving a target return.

2. **Performance Metrics**:
   - **Rate of Return**: Weekly and overall returns.
   - **Standard Deviation**: Volatility assessment.
   - **Beta**: Sensitivity to market movements.
   - **Jensen Index**: Excess return evaluation.
   - **Sharpe Ratio**: Risk-adjusted returns.
   - **Value at Risk (VaR)**: Downside risk quantification.

3. **Visualization**:
   - Weekly performance trends for the portfolio and individual stocks.
   - Comparisons against the S&P 500 as a benchmark.

4. **Reporting**:
   - Comprehensive analysis of portfolio performance.
   - Insights into risk-return trade-offs and investment strategies.

## Tools and Technologies
- **Python**:
  - Libraries: `pandas`, `numpy`, `matplotlib`, `scipy`, `yfinance`
  - Historical stock data is fetched using the Yahoo Finance API (`yfinance`).
- **Jupyter Notebook**: For interactive analysis and visualization.

## How to Run the Project
- Open the Jupyter Notebook and run the cells sequentially to replicate the analysis.

## Insights and Learnings
- Practical application of theoretical finance concepts.
- Analysis of risk and return metrics to guide portfolio management decisions.
- Hands-on experience with data-driven financial modeling.

## Results
A detailed performance report is included, showcasing:
- Portfolio returns relative to market benchmarks.
- Risk assessment and optimization strategies.
- Key takeaways for improving investment strategies.

### Stock Overview

| Stock   | Return  | Standard Deviation | Beta  | Jensen Index | Sharpe Ratio | VaR (h=0.05) |
|---------|---------|--------------------|-------|--------------|--------------|--------------|
| S&P 500 | -0.0025 | 0.0075             | N/A   | N/A          | N/A          | N/A          |
| AVGO    | -0.0526 | 0.0314             | 2.7075| 0.0166       | -0.5154      | 8.3612       |
| FBGRX   | -0.0462 | 0.0129             | 1.5851| 0.0067       | -0.4524      | 4.6489       |
| GOOGL   | -0.0832 | 0.0174             | 1.6225| 0.0076       | -0.3069      | 5.1598       |
| ISRG    | -0.0800 | 0.0227             | 0.3694| -0.0083      | 0.0451       | 6.3156       |
| NVDA    | -0.0848 | 0.2925             | 3.0843| 0.0079       | -0.0760      | 6.9969       |

### Summary
- **Negative Returns**: All stocks experienced negative returns, with NVDA and GOOGL showing the largest losses.
- **Volatility**: NVDA and AVGO exhibit the highest volatility
- **Risk Indicators**: Positive Jensen Index values indicate some excess return relative to the risk-free rate, but Sharpe Ratios are mostly negative, except for ISRG.
- **Investor Considerations**: Diversification, rebalancing, and focusing on lower-risk assets may help optimize returns and reduce risk.
