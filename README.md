# challenge5
Fintech consultation for a large credit union; to help benefit local commuinties they serve.

Requirements: Create two financial analysis tools by using a single Jupyter notebook:

Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

You’ll use the information from the Monte Carlo simulation to answer questions about the portfolio to provide investment advice.


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

Evaluate Crypto Holdings Using ```Requests``` Library

Evaluate the Stock and Bond Holidings by Using the ```Alpaca SDK```

Evaluate the Emergency Fund


Part 2 - Create a Financial Planner for Retirement

Create the Monte Carlo Simulation - Forecast Cumulative 
Returns for 30 Years

Analyze the Retirement Porfolio Forecasts

Create the Monte Carlo Simulation - Forecast Cumulative Returns for 10 Years

Provide Investment Advice - Recommend the portfolio whose time horizon supports retirement goals



---

## Contributors

Andre Johnson

---

## License

MIT
