# Financial Planner Tools
This application contains two financial analysis tools in a single Jupyter notebook designed to help credit union members evaluate their financial health.

The first is a financial planner for emergencies that enables members to visualize their current savings so that they can determine if they have enough reserves for an emergency fund.

The second is a financial planner for retirement that forecasts the performance of their retirement portfolio over 30 years. To do that, this tool makes an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

## Install

In order to successfully run ```financial_planning_tools.ipynb``` please install the following packages:

1. dot-env: ```pip install python-dotenv```
2. Alpaca API: ```pip install alpaca-trade-api``` (In order to use this API you must create a .env file and include your Alpaca Keys)
3. Requests ```conda install -c anaconda requests```
4. Pandas ```pip install pandas```
5. Pathlib ```pip install pathlib```
6. Matplotlib ```pip install matplotlib```
7. JSON ```conda install -c jmcmurray json```

## License
MIT
