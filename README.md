# Stock Price Monitor

A  web app that fetches and displays current stock prices and the percentage change from the opening price. Users can add and remove stock tickers.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript (jQuery)
- **Backend**: Flask, Python
- **Stock Data**: `yfinance` library
- **Storage**: `localStorage` for persisting tickers

## Usage

1. ```bash
    git clone https://github.com/codeabuu/MarketWatch.git
    ```
2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3. **Run the application:** python app.py
4. Add different markets symbols to track their prices.
   
You can refer to different market symbols using this [link](https://finance.yahoo.com/lookup/)

**Note:** The market symbol is case-sensitive and must be entered exactly as required by `yfinance`.
   
