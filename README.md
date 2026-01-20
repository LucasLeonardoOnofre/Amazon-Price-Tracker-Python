# Amazon Price Tracker (Python)

This project is a Python script that scrapes an Amazon product page, extracts the product title and price, and saves the data to a CSV file. The script can run repeatedly to track price changes over time.

## Features
- Scrapes product title and price from Amazon
- Stores price history in a CSV file
- Automatically timestamps each price check
- Uses BeautifulSoup and Requests for web scraping
- Data can be analyzed using Pandas

## Technologies Used
- Python
- BeautifulSoup
- Requests
- Pandas
- CSV
- Datetime

## How It Works
1. Sends an HTTP request to an Amazon product page
2. Parses the HTML content
3. Extracts the product title and price
4. Saves the data with the current date into a CSV file
5. Repeats the process at a fixed time interval
