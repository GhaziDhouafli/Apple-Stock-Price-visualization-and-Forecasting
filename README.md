# Apple-Stock-Price-Analytics-and-Forecasting
In this project, I web scraped "Yahoo finance" website to get data about Apple sales. After that I created a dashboard that describes our data perfectly and at the end i forecasted the "Close prices" using the LSTM architecture

## **1- Web Scraping the "Yahoo Finance" Website:**
In order to collect the data, i used Beautifulsoup and requests libraries that allowed me to get the Html file and parse it. For this part i aimed to get data that represents the apple stock prices from 2012 up to 2022 and i ended up having different features:

- date
- Open
- High
- Low
- Close
- Adj Close
- Volume
