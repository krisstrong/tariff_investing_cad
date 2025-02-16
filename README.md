# Stock Performance Tracker

## Overview
This project is a personal investment tool designed to evaluate potential stock purchases. It specifically tracks the performance of selected stocks in response to Trump's Canadian tariff announcements.

## Key Objectives
- **Monitor Market Reactions** – Assess how stocks respond to the tariff announcements.
- **Evaluate Investment Performance** – Track price trends of selected stocks over time.
- **Identify Opportunities** – Determine whether certain stocks present buying or selling opportunities post-announcement.
- **Compare Multiple Investments** – Analyze different stocks side by side to see which are most affected.

## How to Use
1. Modify the stock ticker symbols in the script to track your desired stocks:
    ```python
    stock1 = "MNT.TO"
    stock2 = "GOLD"
    stock3 = "AC"
    ```
2. Install required dependencies:
    ```bash
    pip install yfinance pandas matplotlib
    ```
3. Run the script to fetch stock data and generate a closing price chart.

## Dependencies
This project requires the following Python packages:
- `yfinance`
- `pandas`
- `matplotlib`
- `datetime`

## Data Source
Stock data is retrieved from Yahoo! Finance using the `yfinance` library. The script fetches historical closing prices for up to three selected stocks.

## Visualization
The script generates a stock performance chart, highlighting key dates such as:
- **US Election Day (2024-11-04)**
- **Tariff Announcements (2025-02-01, 2025-02-10)**

The chart provides a visual representation of stock trends, helping identify potential investment opportunities.

## License
This project is for personal use and investment analysis. Feel free to modify and adapt it for your own needs.
