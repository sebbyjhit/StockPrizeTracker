 Stock Price Tracker

This Stock Price Tracker fetches and displays the latest stock prices for a given list of stock symbols using the Alpha Vantage API. The prices are updated every 60 seconds.

## Features

- Fetches real-time stock prices using the Alpha Vantage API.
- Displays the latest stock prices for a list of user-provided stock symbols.
- Updates stock prices every 60 seconds.

## Requirements

- Python 3.6+
- Required Python libraries:
  - `requests`
  - `json`
  - `time`

## Installation

1. **Clone the Repository or Download the Script**:
   - Clone the repository or download the script file `stock_price_tracker.py`.

2. **Install the Required Python Libraries**:
   - Open a terminal or command prompt and run the following command to install the required libraries:
     ```sh
     pip install requests
     ```

3. **Get an API Key**:
   - Sign up for a free API key from Alpha Vantage: [Alpha Vantage API](https://www.alphavantage.co/support/#api-key)

## Configuration

Replace the placeholder _API`'YOUR_KEY'` in the script with your actual Alpha Vantage API key.

### Example

```python
# Replace 'YOUR_API_KEY' with your actual Alpha Vantage API key
API_KEY = 'your_actual_api_key

Running the Script
Save the Script:

Save the script to a file named stock_price_tracker.py.
Run the Script:

Open a terminal or command prompt, navigate to the directory where the script is saved, and run the following command:
python stock_price_tracker.py

Enter Stock Symbols:

When prompted, enter the stock symbols you want to track, separated by commas (e.g., AAPL,GOOGL,MSFT).
View Stock Prices:

The script will fetch and display the latest stock prices for the given symbols every 60 seconds
