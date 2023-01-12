# challenge5
A financial consulting project is proposed for a large credit union aimed at supporting the local communities they serve. The project includes the development of two financial analysis tools within a single Jupyter notebook.

Tool 1: Financial Planner for Emergencies
This tool allows members to visualize their current savings and assess if they have enough reserves for unexpected events.

Tool 2: Financial Planner for Retirement
This tool uses historical price data obtained through the Alpaca API and the Alpaca SDK to conduct Monte Carlo simulations and forecast the performance of members' retirement portfolios in 30 years. The simulation results will be used to provide investment advice and answer any questions regarding the portfolio.


## Technologies

[Python](https://www.python.org/downloads/release/python-3915/) v3.9.15

[OS](https://docs.python.org/3/library/os.html) Miscellaneous operating system interfaces

[Requests](https://pypi.org/project/requests/) Requests is a simple, yet elegant, HTTP library

[Pandas](https://pandas.pydata.org/) Open source data analysis and manipulation tool

[Dotenv](https://pypi.org/project/python-dotenv/) Read key-value pairs from a .env file and set them as environment variables

[Alpaca_Trade_API](https://alpaca.markets/docs/python-sdk/) The official Python SDK for Alpaca's suite o of API

[%matplotlib](https://matplotlib.org/) Comprehensive library for creating static, animated, and interactive visualizations in Python

[Json](https://docs.python.org/3/library/json.html) Lightweight data interchange format inspired by JavaScript

[NumPy](https://numpy.org/) The fundamental package for scientific computing with Python

[Datetime](https://docs.python.org/3/library/datetime.html) This module supplies classes for manipulating dates and times

[Pytz](https://pypi.org/project/pytz/) This library allows accurate and cross platform timezone calculations


[MCSimulation](MCForecastTools.py) A Python class for runnning Monte Carlo simulation on portfolio price data.

---

## Installation Guide
```
pip install os
pip install -c anaconda requests
pip install pandas
pip install python-dotenv
pip install alpaca-trade-api
pip install -c jmcmurray json
pip install numpy
pip install datetime
```
---

## Usage
 Part 1 - Create a Financial Plan for Emergencies

Evaluate Crypto Holdings Using the Requests Library to assess the current value and potential risks of these assets.

Evaluate Stock and Bond Holdings by using the Alpaca SDK to determine the performance and diversification of these investments.

Evaluate the Emergency Fund by assessing the amount currently saved and identifying any potential shortfalls that need to be addressed.

Part 2 - Create a Financial Plan for Retirement

Create a Monte Carlo simulation to forecast cumulative returns for a 30-year time horizon, to help plan for long-term retirement goals.

Analyze the retirement portfolio forecasts, looking at factors such as risk, returns, and diversification.

Create a Monte Carlo simulation to forecast cumulative returns for a 10-year time horizon, which can help plan for shorter-term goals leading up to retirement.

Provide investment advice by recommending a portfolio that is best suited to meet the individual's retirement goals, taking into account factors such as time horizon, risk tolerance, and investment goals.



---

## Contributors

Andre Johnson

---

## License

MIT
