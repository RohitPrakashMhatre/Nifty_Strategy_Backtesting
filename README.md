# Nifty_Strategy_Backtesting
This project includes backtesting a strategy on the Nifty Index over 16+ years of historical data. The goal is to analyze the performance of strategy and evaluates its effectiveness.

📊 DATA SOURCE:
Nifty & USD Data: Fetched using the yfinance library.
Data Retrieval Code: Included in the notebook for reproducibility.

📊 RESULTS AND INSIGHTS:
- Identify the Inverse Correlation between Nifty Index and USD returns.
- Capturing simple returns VS Normalize returns.
- Finding the best Window size which give [Highest win rate,maximum annualized returns, best Stop_loss].
- Summarizing the statistics of strategy. 

⚡STRATEGY DETAILS:
- Calculate the returns of both Nifty and USD.
- Using returns calculate rolling normalize returns of both (Rolling mean / Rolling STD).
- Compare the normalize returns of both Nifty and USD.

🛠️LIBRARIES USED:
-pandas – Data manipulation
-matplotlib & seaborn – Data visualization
-yfinance – Fetching market dat
-vectorbt – Quantitative finance and backtesting

🚀HOW TO RUN THE NOTEBOOK:
- git clone https://github.com/RohitPrakashMhatre/Nifty_Strategy_Backtesting.git
- cd Nifty_Strategy_Backtesting
- jupyter notebook

