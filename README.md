# Stock Market Analysis and Portfolio Analysis

This project analyzes historical stock market data to identify trends, correlations between sectors, and potential investment opportunities. It also includes portfolio optimization for two hypothetical investors with distinct risk profiles:

* **Mr. Patrick Jyengar:** A low-risk investor aiming for steady returns with minimal volatility.
* **Mr. Peter Jyengar:** A high-risk investor seeking maximum returns with the potential for larger gains but also greater losses.


## Data and Methodology

The project utilizes historical stock data for various companies and the S&P 500 index, covering a period of 5 years. Key steps in the analysis include:

1. **Data Collection:** Importing and preprocessing historical stock prices from a reliable source (e.g., CSV files, APIs, databases).
2. **Data Normalization:** Scaling stock prices to a consistent range for fair comparison.
3. **Sectoral Analysis:** Examining the performance and correlation between stocks within specific sectors such as Aviation, Finance, Pharma, and Technology.
4. **Key Metrics Calculation:** Determining daily returns, cumulative returns, annualized returns, risk (standard deviation), and the Sharpe ratio for individual stocks.
5. **Portfolio Optimization:** Constructing portfolios for both Mr. Patrick and Mr. Peter based on their risk preferences and investment goals.
6. **Portfolio Analysis:** Assessing the expected returns, risks, and Sharpe ratios associated with each portfolio.


## Key Findings

* **Sector Trends:** The analysis reveals significant variations in stock performance across different sectors during the 5-year period. For instance, the tech sector experienced a sharp recovery during the pandemic, while the aviation sector underperformed.
* **Top-performing Stocks:** Key stocks like Amazon, Microsoft, and Apple demonstrate robust growth and superior returns compared to the market average.
* **Portfolio Performance:** The two optimized portfolios show clear differences in returns and risk. Mr. Peter's high-risk portfolio with high-growth stocks achieves higher returns but also carries more volatility. Mr. Patrick's portfolio, on the other hand, focuses on more stable, low-risk stocks with moderate returns.


## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## Project Structure

The project is organized into a notebook with a clear progression of code and analysis:
1. Data preprocessing
2. Sector wise Analysis
3. Calculation of sharp Ratio, Annual Risk & Annual Returns
4. Portfolio Optimization
5. Portfolio Analysis


## Potential Applications

This project's findings can be used to inform:
* **Investment decisions:** Identifying stocks and sectors with potential for growth.
* **Portfolio construction:** Creating diversified portfolios that align with individual risk profiles and objectives.
* **Risk management:** Evaluating the risks associated with various investment strategies.


## Further Improvements

* Incorporate more advanced portfolio optimization algorithms (e.g., Mean-Variance optimization, Monte Carlo simulations).
* Include factors like dividend payouts and earnings growth in the analysis.
* Develop a more robust risk management system.


## Disclaimer

This project serves as an educational example and should not be considered professional investment advice. The results and predictions presented in this project are based on historical data and may not accurately reflect future market conditions. 
