This project contains a Python script that scrapes data from a website.  The script uses `requests` and `BeautifulSoup` for web scraping and `pandas` for data manipulation.

## Prerequisites

Ensure you have the following libraries installed:

- `requests`
- `beautifulsoup4`
- `pandas`


You can install them using pip:

```sh
pip install requests
pip install beautifulsoup4
pip install pandas


Script Overview
The script performs the following steps:

Scrape Data: Fetches HTML content from a specified URL and parses it to extract the desired information.
Convert Data to DataFrame: Organizes the extracted data into a pandas DataFrame.
