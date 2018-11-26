# Exploratory Data Analysis - US Equities Fundamentals 

In my effort to learn the basic skills needed for a career as a data scientist, I needed to practice with a data set that I found personally interesting. I've previously investigated college admissions data, which was directly related to my previous work with Newton. But for this project I decided to dive into the stock market so I could start to understand a small slice of the world my good friend in finance is always trying to talk with me about. 

I discovered Quandl, a company that collects and sells data for use in making investment decisions. Some of their data is available for free when you create an account and they will provide you an API key and python library to access their data.  I decided their [SF1 Core US Fundamentals Data](https://www.quandl.com/data/SF1-Core-US-Fundamentals-Data) would help me better understand the shape and scale of the equities market. This dataset contains one entry per company for each of the last seven years with over one hundred indicators (columns) showing not only basic balance sheet information like total company assets and liabilities but also dozens of more esoteric indicators that I can at this point only barely understand.

In addition to this indicators table, there is a tickers table which includes one entry for each company, indexed by their stock ticker, with columns containing information like the full company name, sector, industry, location, which exchange the company is listed, and so forth. For our purposes, we will need to use both tables.