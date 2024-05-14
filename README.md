# Stock Price Comparison Tool

This tool allows users to compare the stock prices of two companies over a specified time period. It visualizes the stock price data along with selected technical indicators using Bokeh, a Python interactive visualization library.

## Getting Started

### Prerequisites:
- Python (version 3.x recommended)
- Bokeh (for interactive visualization)
- NumPy (for numerical computations)
- yfinance (for fetching stock price data from Yahoo Finance)

### Installation:
1. Install the required packages:
    ```bash
    pip install bokeh numpy yfinance
    ```

2. Clone the repository and navigate into the project directory:
    ```bash
    git clone https://github.com/haseebsultankhan/stock-comparison-tool.git
    cd stock-comparison-tool
    ```

3. Run the Python script:
    ```bash
    python main.py
    ```

## Usage:
1. Enter the main stock ticker symbol in the "Main Stock" text input field.
2. Enter the comparison stock ticker symbol in the "Comparison Stock" text input field.
3. Select the start and end dates using the date pickers.
4. Choose one or more indicators from the multi-choice selector.
5. Click the "Load Data" button to visualize the stock price data and selected indicators.

## Project Structure
- `stock_comparison.py`: The main Python script for comparing stock prices and visualizing data.
- `README.md`: This README file providing information about the project.

## Implementation Details
- Stock price data is fetched using the Yahoo Finance API through the `yfinance` library.
- Bokeh is used to create interactive plots for visualizing the stock price data and technical indicators.
- Technical indicators such as Simple Moving Average (SMA) and Linear Regression Line are computed and plotted along with the stock price data.

## Contributing
Contributions to this project are welcome! Feel free to fork the repository, make changes, and submit pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
