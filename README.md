# binance-ohlc-downloader

A Jupyter notebook that will downlload OHLC data from Binance.

The data from Binance is zipped CSV files.

https://github.com/binance/binance-public-data/

Open time|Open|High|Low|Close|Volume|
| -- | -- | -- | -- | -- | -- |
|1499040000000|0.01634790|0.80000000|0.70000000|0.75000000|100000


It then imports into a dataframe and runs all TA indicators from the ta library:

https://technical-analysis-library-in-python.readthedocs.io/en/latest/

Finally it will export all the data into a csv file: BTCUSDT-1d-2018-2021.csv
