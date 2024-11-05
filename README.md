# Options Backtester

A simple options backtester built in Python that utilizes the Black-Scholes model to evaluate the performance of basic options strategies on historical stock data.

## Overview

The Options Backtester allows users to backtest options trading strategies by fetching historical stock price data, calculating option prices, and analyzing potential profit and loss (P&L) based on user-defined parameters. 

## Features

- Fetch historical stock prices using the `yfinance` library.
- Calculate option prices using the Black-Scholes formula.
- Backtest simple options strategies such as buying and selling call options.
- Evaluate profit/loss for each strategy over a specified time period.

## Installation

To use the Options Backtester, you need to have Python installed along with the required libraries. You can install the necessary packages using pip:

```bash
pip install yfinance numpy scipy

