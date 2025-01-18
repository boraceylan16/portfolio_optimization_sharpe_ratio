
# 📊 Sharpe Ratio Maximization for Portfolio Optimization

This project focuses on optimizing the allocation of randomly selected stocks to maximize the **Sharpe Ratio**, a key metric for risk-adjusted portfolio performance.

---

## 🚀 Project Overview

The **Sharpe Ratio** is one of the most widely used measures in portfolio management. It evaluates the performance of an investment compared to its risk. In this project:
- Randomly selected a portfolio of stocks.
- Utilized historical data to calculate expected returns, risks, and correlations.
- Applied optimization techniques to maximize the portfolio's Sharpe Ratio, balancing risk and return.

---

## 📂 Project Structure

```
📦 Project
├── 📁 data
│   ├── historical_prices.csv    # Historical stock price data
├── 📁 scripts
│   ├── optimization.py          # Portfolio optimization logic
│   ├── sharpe_ratio_calc.py     # Functions to calculate the Sharpe Ratio
├── 📊 notebooks
│   ├── sharpe_ratio_maximization.ipynb  # Full project walkthrough
├── 📄 README.md                 # Project documentation
```

---

## 🛠️ Methodology

1. **Data Collection**: Gathered historical stock price data for a randomly selected group of assets.
2. **Sharpe Ratio Calculation**:
   - **Formula**:  
     \[
     Sharpe\ Ratio = rac{E(R_p) - R_f}{\sigma_p}
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

## 💡 Key Features

- **Random Portfolio Generation**: Randomly selects stocks to create a diversified portfolio.
- **Optimization**: Implements advanced numerical optimization techniques to maximize risk-adjusted returns.
- **Visualization**: Includes graphical representation of the efficient frontier and portfolio metrics.

---

## 📊 Results

The optimized portfolio achieved a **higher Sharpe Ratio** compared to equal-weight and randomly weighted portfolios, demonstrating effective risk-adjusted performance.

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sharpe-ratio-maximization.git
   ```
2. Navigate to the project directory:
   ```bash
   cd sharpe-ratio-maximization
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or the main script to view results:
   ```bash
   jupyter notebook notebooks/sharpe_ratio_maximization.ipynb
   ```

---

## 📈 Visuals

![Efficient Frontier](https://via.placeholder.com/800x400?text=Efficient+Frontier)  
*Efficient frontier showcasing the optimal portfolio.*

---

## 🧰 Technologies Used

- **Python**: Core programming language.
- **NumPy & Pandas**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For visualizations.
- **SciPy**: For numerical optimization.

---

## ✍️ Author

**[Your Name](https://www.linkedin.com/in/yourname)**  
📧 your.email@example.com

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).
