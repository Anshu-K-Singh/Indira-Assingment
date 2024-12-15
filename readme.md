# Stock Portfolio Tracker and Trade Analyzer

## Project Overview

The **Stock Portfolio Tracker and Trade Analyzer** is a  project that enables users to:

- Collect and analyze real-time stock data using Yahoo Finance.
- Simulate trades and track portfolio performance.
- Log trading activities and handle errors efficiently.
- Visualize stock performance and trade signals.


---

## How to Run the Program

### Prerequisites

1. Ensure you have Python 3.7 or higher installed on your system.
2. Install the required libraries by running the following command:
   ```bash
   pip install yfinance pandas matplotlib
   ```

### Steps to Execute

1. Download the project files and ensure they are in the same directory.



2. Open the provided Jupyter Notebook (`main.ipynb`) in your preferred environment (e.g., Jupyter Notebook, Jupyter Lab, or VS Code).
<br>
3. Run each cell in sequence to execute the program.
   - The program fetches stock data, simulates trades, and generates outputs.
<br>
4. View the generated files in the `stock_data` directory for results.

---

## Assumptions Made

- Stock data is available for the selected symbols.
- Transaction costs, taxes, and dividends are ignored.
- The portfolio starts with a fixed cash balance.
- The program does not account for after-hours trading.

---

## Libraries Used

The following libraries are essential for this project:

- **yfinance**: For fetching real-time stock data.
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For data visualization.
- **os**: For file and directory operations.
- **logging**: For logging trade activities and errors.

Install all dependencies using:

```bash
pip install yfinance pandas matplotlib
```

---

## Output Files and Logs

- **Portfolio Performance**: Saved as a CSV file (`portfolio_summary.csv`) in the `stock_data` directory.
- **Trade Logs**: Detailed logs of all trade activities, saved in `trade_log.txt`.
- **Error Logs**: Logged alongside trade activities in `trade_log.txt`.
- **Visualization**: Plots showing stock performance with buy/sell signals are displayed within the notebook.

---

Feel free to customize the tool to suit specific trading strategies or analysis needs. Happy trading!

## References

- **yfinance Documentation**: For more details on using `yfinance` to fetch financial data, refer to the official documentation: [yfinance Documentation](https://pypi.org/project/yfinance/).
- **YouTube Videos**:
  - [Using Python for algorithm Trading ](https://www.youtube.com/watch?v=9Y3yaoi9rUQ&pp=ygUfYWxnb3JpdGhtIHRyYWRpbmcgdXNpbmcgcHl0aG9uIA%3D%3D)
  - [Using Python yfinance library ](https://www.youtube.com/watch?v=7wAQCwdvqqo&pp=ygUYIHVzaW5nIHB5dGhvbiAgeWZpbmFuY2Ug)
