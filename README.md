![](./bitcoin.jpg)

[Link to Kaggle Data](https://www.kaggle.com/tencars/392-crypto-currency-pairs-at-minute-resolution?select=btceur.csv)

Content
This dataset contains the historical trading data (OHLC) of more than 400 trading pairs at 1 minute resolution reaching back until the year 2013. It was collected from the Bitfinex exchange as described in [this article](https://medium.com/coinmonks/how-to-get-historical-crypto-currency-data-954062d40d2d).

The data in the CSV files is the raw output of the Bitfinex API. This means, there are no timestamps for time periods in which the exchange was down. Also if there were time periods without any activity or trades there will be no timestamp as well.

Inspiration
This dataset is intended to facilitate the development of automatic trading strategies. Machine learning algorithms, as they are available through various open source libraries these days, typically require large amounts of training data to unveil their full power. Also the process of backtesting new strategies before deploying them rests on high quality data. Most crypto trading datasets that are currently available either have low temporal resolution, are not free of charge or focus only on a limited number of currency pairs. This dataset on the other hand provides high temporal resolution data of more than 400 currency pairs for the development of new trading algorithms.
