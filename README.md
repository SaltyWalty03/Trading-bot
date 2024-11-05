Algorithmic Trading Bot
This repository contains Jupyter Notebooks and Python code for an algorithmic trading bot project. The bot uses a Relative Strength Index (RSI) strategy to simulate Bitcoin trading on the Binance exchange. This project was developed for research and educational purposes and aims to provide insights into algorithmic trading and quantitative analysis.

Files
Algo Trading.ipynb: This notebook demonstrates the algorithmic trading strategies, including implementation details of the RSI strategy, data preparation, trading logic, and performance analysis. Key sections:

Data Collection and Preprocessing
Strategy Development (RSI-based)
Backtesting and Analysis
Performance Metrics and Visualization
Bot.ipynb: This notebook contains the main bot code. It includes functions for handling live trading, such as:

Connecting to the Binance API
Executing trades based on the RSI signals
Managing positions and calculating profit/loss
Error handling and logging
Requirements
To run these notebooks, you will need:

Python 3.x
Jupyter Notebook
Required libraries (see the requirements.txt file):
pandas
numpy
matplotlib
Binance API (e.g., python-binance package)
Any other libraries specified within the notebooks

Usage
Setup: Make sure to set up API credentials for Binance in a .env file or directly in the code (not recommended for security reasons).
Run the Bot: Start by running the cells in Bot.ipynb to activate the bot and begin live trading (or simulate using paper trading).
Analysis: Use Algo Trading.ipynb to analyze the strategy's performance and tweak parameters based on backtest results.
Note: Ensure you have a basic understanding of algorithmic trading and manage risks carefully, especially if live trading with real funds.

Project Background
This bot was developed as part of a Python-based exploration into algorithmic trading strategies. The RSI strategy used here was selected for its simplicity and relevance to trend and momentum analysis, particularly in cryptocurrency markets.

Disclaimer
This project is intended for educational purposes only. Use caution when deploying live trading bots in real markets, as financial losses may occur.
