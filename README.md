# Tesla and GameStop Stock and Revenue Dashboard

## Main Objective
The primary objective of this project is to act as a data scientist working for an investment firm. The goal is to extract historical stock data and quarterly revenue data for major companies like **Tesla** and **GameStop**, clean and process the data, and build interactive dashboards comparing their stock prices versus revenue to support financial analysis and investment decisions.

## Project Structure

The project is executed in a Jupyter Notebook containing the following steps:

1. **Extracting Stock Data:** Using the `yfinance` library to fetch historical market data for Tesla and GameStop.
2. **Web Scraping Revenue Data:** Using `requests`, `BeautifulSoup`, and `pandas` (`read_html`) to extract historical quarterly revenue data from HTML tables.
3. **Data Cleaning:** Removing currency symbols (`$`), commas, and handling missing values.
4. **Dashboard Visualization:** Using `Plotly` (`make_subplots` and `go.Scatter`) to create multi-panel interactive dashboards displaying stock prices and revenue trends over time.

## Prerequisites & Installation

To run this notebook locally, ensure you have the required libraries installed:

```bash
pip install yfinance pandas requests beautifulsoup4 plotly
