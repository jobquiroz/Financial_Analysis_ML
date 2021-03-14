# Financial_Analysis_ML

This repository contains some of the work I've been doing related to analyzing the markets using market and fundamental data. 

We use data wrangling pandas methods to analyze the current state of the markets to extract insights. The end goal is to produce a Data Science tool to support investing decisions for non-expert people using free data and other available tools.

Most of my work is currently in another private repo but I show here some highlights. The description of the contained files are:

- `01_Update_tickers`: This uses the yfinance library to extract information from the tickers of the US markets. It generates a csv file to be used in other programs.
- `02_Performance_by_industry`: Perform some basic cleaning tasks and measure the performance metrics for relevant companies.
- `03_Working_with_fundamental_data`: A simple example on how to read an income statement
- `04_Price_to_Sales_SP500`: Combinees the two previous notebooks to calculate the Price to Sales ratio of all the stocks in the SP500

Due to the size of the files we cannot include the data used in this programs.
