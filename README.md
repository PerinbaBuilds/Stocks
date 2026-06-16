# Stock Analysis Dashboard

Python scripts that fetch historical stock price and revenue data for **Tesla (TSLA)** and **GameStop (GME)**, and render interactive charts.

## Tech Stack

- **yfinance** — fetch historical stock data
- **pandas** — data manipulation
- **plotly** — interactive chart rendering
- **requests + BeautifulSoup** — scrape quarterly revenue tables

## Install

    pip install yfinance pandas plotly requests beautifulsoup4

## Usage

    python "tesla stocks.py"
    python "gme stocks.py"

Charts open in your browser as interactive HTML.
