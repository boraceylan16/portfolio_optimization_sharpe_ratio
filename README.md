## 🚀 Project Overview

The **Sharpe Ratio** is one of the most widely used measures in portfolio management. It evaluates the performance of an investment compared to its risk. In this project:
- Randomly selected a portfolio of stocks.
- Utilized historical data to calculate expected returns, risks, and correlations.
- Applied optimization techniques to maximize the portfolio's Sharpe Ratio, balancing risk and return.

---

## 🛠️ Methodology

1. **Data Collection**: Gathered historical stock price data for a randomly selected group of assets.
2. **Sharpe Ratio Calculation**:
   - **Formula**:  
     \[
     Sharpe\ Ratio = \frac{E(R_p) - R_f}{\sigma_p}
     \]  
     Where:
     - \(E(R_p)\): Expected return of the portfolio.
     - \(R_f\): Risk-free rate.
     - \(\sigma_p\): Portfolio standard deviation.
3. **Optimization**:
   - Applied **Mean-Variance Optimization** to calculate weights that maximize the Sharpe Ratio.
   - Explored **Monte Carlo Simulations** to evaluate multiple portfolio configurations.
4. **Validation**:
   - Evaluated the optimized portfolio's risk-return characteristics.
   - Compared against random weight allocations.

---

## 🧰 Technologies Used

- **Python**: Core programming language.
- **NumPy & Pandas**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For visualizations.
- **SciPy**: For numerical optimization.
- **yFinance**: For Data Collection
