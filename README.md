# Financial-Scanner-and-Visualizer
# Financial Scanner and Visualizer

A Python-based analysis tool that retrieves real-time corporate financial data to calculate automated risk scores and visualize peer-to-peer comparisons.

## Project Overview
This project is designed to process multiple stock tickers simultaneously. It extracts key balance sheet metrics, scores the financial health of each company, and displays the results in both a data table and a visual dashboard.

## Key Features
* **Live Data Extraction:** Retrieves real-time corporate financial metrics (such as Profit Margin, Debt-to-Equity, and Current Ratio) using the Yahoo Finance API.
* **Batch Processing:** Accepts multiple company tickers at the same time and organizes the extracted data into a sorted Pandas DataFrame.
* **Automated Risk Scoring:** Evaluates the data against standard financial thresholds to assign a 0-4 "Health Score" to each company.
* **Data Visualization:** Generates a 1x3 analytical dashboard using Matplotlib and Seaborn.
* **Threshold Color-Coding:** Applies conditional colors to the charts (green for safe metrics, red for missed targets) to clearly show balance sheet vulnerabilities.

## Technologies Used
* **Python 3**
* **yfinance:** For connecting to the Yahoo Finance API.
* **Pandas:** For structuring and organizing the financial data matrix.
* **Matplotlib & Seaborn:** For rendering the visual charts.

## How to Run the Code
1. Open the Python script or Google Colab notebook.
2. Ensure the required libraries are installed (`pip install yfinance pandas matplotlib seaborn`).
3. Run the program and enter the stock tickers when prompted (e.g., `AAPL, MSFT, TSLA`).
4. The system will output a data table and display the comparative charts.
