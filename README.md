# Black-Scholes Option Trading

- A Python-based implementation of the **Black-Scholes option pricing model** with additional modules for backtesting, strategy simulation, and risk management.
- This project is designed as an **industry grade trading research tool**, enabling users to calculate option prices, implied volatility, and evaluate trading strategies using historical market data.

## Features

- **Black-Scholes Pricing**:
    - Calculate call and put option prices
    - Supports European-style options
    - Greeks calculation for risk assessment

- **Implied Volatility Solver**:
    - Iterative numerical approach to estimate IV from market prices

- **Historical Data Loader**:
    - Pulls and formats historical asset price data for analysis

- **Strategy Simulation**
    - Customizable long/short strategies
    - Hedging modules to test delta-neutral positions

- **Backtesting**
    - Trade execution simulation using historical data 
    - PnL tracking and performance metrics

- **Volatility Forecasting**
    - Realized volatility estimation for risk models

## Project Structure

- Source [#Folder holding the source Python files]:
    - backtest.py #Backtesting engine
    - strategy.py #Strategy logic and signals
    - black_scholes.py #Option pricing model
    - iv_solver.py #Implied volatility calculation
    - hedging.py #Delta-neutral hedging tools
    - data_loader.py #Loads and preprocesses market data
    - rv_forecasting.py #Realized volatility forecasting
    - microstructure.py #Market microstructure-related calculations
- README.md #Project documentation
- main.py #Entry point for running the trading program
- tests.py #Unit tests for componenets
- requirements.txt #Libraries used in the project 

### Author: Areeb Arshad | Virginia Tech | Data Science, Statistics, and Mathematics 

### Notes:
- This model is for educational and research purposes only.
- It does **not** constitute financial advice or a production-ready trading system.
