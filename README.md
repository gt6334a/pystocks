# Stock Analysis Tools and Libraries in python

This is my notes on surveying the python tools and libraries available for stocks analysis in Nov 2020.

## Data Sources


### yfinance

This library allows for pythonic download of Yahoo Finance data.
https://pypi.org/project/yfinance/

Github page for yfinance
https://github.com/ranaroussi/yfinance

Yahoo Finance has not just pricing data, but also other information such as earnings, cashflow, etc.  Refer to the Quick Start session from the page above for details.



### Quandl

Used by the 'stocker' analysis script by Will Koehrsen.  It is an aggregated dataset and offers not just stocks data but also things like US GDP, WTI Crude data price, etc.

So, in order to get the data you want, you will need to know the 'Quandl Code' for the data.
https://www.quandl.com/tools/python

The Github page
https://github.com/quandl/quandl-python


## Analysis and Modelling

### fbprophet

Prophet is a time series analysis library by Facebook.  Seems to be quite sophisticated; also takes time to install since it requires a gcc compiler.


## Analysis Tutorials


### Cameron Shadmehry

https://medium.com/automated-trading/a-guide-to-automating-your-stock-analysis-with-python-4b6929e54201


### Will Koehrsen

https://towardsdatascience.com/stock-analysis-in-python-a0054e2c1a4c

The github page for stocker: 
https://github.com/WillKoehrsen/Data-Analysis/blob/master/stocker/stocker.py
