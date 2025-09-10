# Portfolio-Risk-Optimization-using-Var-and-CVaR

This project demonstrates portfolio risk management using Value at Risk (VaR) and Conditional Value at Risk (CVaR) for a two-stock portfolio of ICICI Bank &amp; HDFC Bank. It combines financial theory with Python-based implementation for risk analysis, portfolio optimization, and visualization.

Features

	•	Fetches historical stock prices from Yahoo Finance using yfinance.
	•	Computes daily returns and calculates parametric (Normal) and historical VaR & CVaR.
	•	Optimizes portfolio weights to minimize CVaR using SciPy SLSQP.
	•	Provides annualized mean return and volatility metrics.
	•	Visualizes CVaR vs portfolio weight allocation using Matplotlib.
	•	Exports results in CSV format for reporting.

 Future Improvements
 
	•	Extend to multi-asset portfolios beyond two stocks for more realistic diversification.
	•	Incorporate other risk measures like Expected Shortfall, drawdown, or stress testing.
	•	Include rolling window analysis to assess time-varying risk and optimal weights.
	•	Develop an interactive dashboard using Plotly or Streamlit for dynamic allocation and risk visualization.
	•	Integrate real-time stock price feeds for live portfolio monitoring.
