## About Project
A screener on the data sheet named NIFTY25JUN2010000PE.csv

The strategy workflow is as follows:-

- Converts 1 minute timeframe data 15 minutes
- If low of candle is less than previous low we enter short position, with 2 exit criteria’s
  - Exit at end of day
  - Exit if the high of previous candle is broken

## Getting started
### Prerequisites
```sh
pip install openpyxl
```
### Installation
Clone or Download the repository
```sh
git clone https://github.com/KritinMathur/StockDataManipulation.git
```
### Usage

1. The user needs to run the 'TimeFrameConv.py'.
2. This will convert the NIFTY25JUN2010000PE.csv into 15 min candles.
3. The user needs to run the 'ProfitLossCalc.py' to calculate the profit/loss using the strategy mentioned above.
