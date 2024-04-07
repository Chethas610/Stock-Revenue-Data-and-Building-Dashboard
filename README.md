# Stock-Revenue-Data-and-Building-Dashboard
Analyzing Historical Stock/Revenue Data and Building a Dashboard
The project involves extracting and visualizing stock data for two companies, Tesla and GameStop, using Python. Here's a summary of the tasks involved:

# Extracting Stock Data:
Using the yfinance library, extract historical stock data for Tesla and GameStop.
For Tesla, the data is extracted with the ticker symbol 'TSLA'.
For GameStop, the data is extracted with the ticker symbol 'GME'.
The extracted data includes information such as Date, Open, High, Low, Close, Volume, Dividends, and Stock Splits.

# Extracting Revenue Data:
Utilize web scraping techniques to extract quarterly revenue data for both companies.
For Tesla, revenue data is extracted from a webpage using the requests library and BeautifulSoup.
For GameStop, revenue data is extracted from a different webpage using similar techniques.
The extracted revenue data includes Date and Revenue columns.

# Data Cleaning:
Clean the extracted revenue data by removing any commas and dollar signs from the Revenue column.
Drop any rows with null values or empty strings in the Revenue column.

# Visualizing Data:
Utilize a predefined function make_graph to create graphs for both companies.
The function takes the stock data and revenue data as inputs along with the company name.
The graphs display historical share price and revenue over time for Tesla and GameStop.

The project aims to provide insights into the stock performance and revenue trends of Tesla and GameStop through data extraction, cleaning, and visualization techniques.
