# Sypto-Athena-V2-trading-data-analyis

## About Athena V2
Sypto is a fully managed portfolio management service for cryptocurrencies. With a host of different products, built for traders and investors alike!
Sypto uses its algorithm trading bot Athena for trading in crypto. Athena has been trained for historical data for backtesting.
you can learn more about Athena [here](https://www.sypto.xyz/athena)


## Bitcoin Backtesting Results: Athena V2

   ### We will scrape the Backtesting results of Athena V2 using BeautifulSoup.

    - There are 3 tables in the web page showing performance of Athena V2 which is an Algo trading bot.

    - Following are the tables:
        - table no 1 which has trading data from August 2017 to August 2019.
        - table no 2 : November 2019 to oct 2021.
        - table no 3 : October 2021 to August 2022

    - Merge data in above tables to create a dataframe for further analyis.
    
   - Used Beautiful Soup and pandas for Scraping and all the data cleaning. (please see the [notebook file](https://github.com/android16-rj/Sypto-Athena-V2-trading-data-analyis/blob/main/sypto-web_scraping.ipynb) for more details)
   - Data analysis using [Microsoft Excel](https://github.com/android16-rj/Sypto-Athena-V2-trading-data-analyis/blob/main/Sypto_athena_V2_trading_data.xlsx).

   - url for the web page scraped is [here](https://learn.sypto.xyz/invest-in-bitcoin-athena-v2/)

