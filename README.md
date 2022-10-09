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

## **2- Visualizing Apple Stock price:**
I visualized the data using Tableau for the whole past year and i ended up having a dashboard that summarizes almost everything the data has to offer.
Link for the dashboard : https://public.tableau.com/app/profile/ghazi.dhoaufli/viz/ApplePrices/Tableaudebord1

## **3- Apple Stock price Forecasting:**
In order to forecast the close prices, i used the Long Short Term Memory Network (LSTM) because it's better than RNN when it comes to capturing long-term dependencies and i ended up with 0.0016 validation loss which is a pretty good result.
