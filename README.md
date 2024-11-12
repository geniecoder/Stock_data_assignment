# Stock and Revenue Data Analysis for Tesla and GameStop

This project demonstrates the extraction, analysis, and visualization of stock data and revenue data for **Tesla (TSLA)** and **GameStop (GME)**. It uses **yfinance** for stock data extraction and **BeautifulSoup** for web scraping GameStop's revenue data from a publicly available HTML page. The data is then visualized using **Plotly**.

## Project Overview

The project includes the following:

### 1. **Tesla Stock and Revenue Data**
- **Tesla Stock Data**: Extracted using the `yfinance` library, this includes historical stock prices of Tesla.
- **Tesla Revenue Data**: The revenue data is scraped from a provided HTML page using `BeautifulSoup` and cleaned for analysis.

### 2. **GameStop Stock and Revenue Data**
- **GameStop Stock Data**: Stock data for GameStop (GME) is extracted using `yfinance`, showing the historical share prices.
- **GameStop Revenue Data**: Revenue data is scraped from the same HTML page (as for Tesla) using `BeautifulSoup`.

### 3. **Data Visualization**
- The stock data and revenue data for both Tesla and GameStop are visualized using interactive line graphs, which show historical share prices and revenues over time.

## Files in this Repository

- `stock.html`: HTML file containing both Tesla and GameStop revenue data (scraped from the internet).
- `gme_stock_analysis.py`: Python script that handles the extraction, analysis, and visualization of GameStop data.
- `tesla_stock_analysis.py`: Python script for extracting, analyzing, and visualizing Tesla data.
- `README.md`: This file, describing the project and how to run it.

## Requirements

To run this project, you'll need the following Python packages:

- `pandas`
- `yfinance`
- `requests`
- `beautifulsoup4`
- `plotly`

You can install these dependencies using pip:

```bash
pip install pandas yfinance requests beautifulsoup4 plotly
