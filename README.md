# Nifty USD-INR Strategy Backtesting
This project includes backtesting a strategy on the Nifty Index over 16+ years of historical data. The goal is to analyze the performance of strategy and evaluates its effectiveness.

📊DATA SOURCE:
-Nifty & USD Data: Fetched using the yfinance library.
-Data Retrieval Code: Included in the notebook for reproducibility.

📊 RESULTS AND INSIGHTS:
- Identified the inverse correlation between the Nifty Index and USD returns.
- Compared simple returns vs. normalized returns.
- Determined the optimal window size for maximum win rate, annualized returns, and best stop-loss.
- Summarized key statistics of the strategy.


⚡STRATEGY DETAILS:
- Calculated returns for both Nifty and USD.
- Computed rolling normalized returns (using rolling mean & rolling standard deviation).
- Compared normalized returns of Nifty and USD..
- 
🛠️LIBRARIES USED:
- pandas – Data manipulation
- matplotlib & seaborn – Data visualization
- yfinance – Fetching market data
- vectorbt – Quantitative finance and backtesting

🚀HOW TO RUN THE NOTEBOOK:
- git clone https://github.com/RohitPrakashMhatre/Nifty_Strategy_Backtesting.git
- cd Nifty_Strategy_Backtesting
- jupyter notebook

