# Weather-Forecast-Web-Scrapping-And-Analysis

**Purpose:**
This Python script scrapes weather forecast data from a webpage, presents it in tabular form, modifies the table for data analysis, and generates various visualizations using seaborn and matplotlib.

**Dependencies:**
requests: HTTP library for making requests
bs4 (Beautiful Soup): HTML parsing library
pandas: Data manipulation library
StringIO: Provides a convenient way to work with text data as a file-like object
google.colab: Colab-specific library for file handling
matplotlib: Plotting library
seaborn: Data visualization library
warnings: Used to suppress warnings

**Functions:
print_all_headlines:**
Prints headlines from the news page using BeautifulSoup.

**getHistoryData:**
Retrieves historical stock market data for a specified company within a given date range.
Utilizes NSE India's API to fetch the data.

**niftyHistoryData:**
Retrieves historical data for a specified NIFTY index (e.g., NIFTY 50) within a given date range.
Scrapes data from the NSE India website using BeautifulSoup.

**Usage:
Headline Extraction:**
The script prints headlines from the provided URL.

**Weather Data Scraping and Tabulation:**
Weather forecast data is scraped, tabulated, and saved as 'weatherdata.csv'.
The modified table with numerical values is saved as 'modified_weatherdata.csv'.

**Basic Operations - First Table:**
Basic statistical operations (sum, max, mean, median, mode) are performed on the humidity column of the modified table.

**Graph Generation:**

_Three visualizations are created and saved:_
Scatter plot ('graph4-1.png') for High Temperature vs. Period.
Scatter plot ('graph4-2.png') for Humidity vs. Wind.
Pair plot ('graph4-3.png') for High Temperature, Wind, and Humidity.
