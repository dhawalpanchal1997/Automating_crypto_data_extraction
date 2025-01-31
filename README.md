# Automating Crypto Data Extraction and Analysis

## Project Overview
This project automates the process of fetching cryptocurrency market data from the CoinGecko API, storing it in a CSV file, and performing data analysis using Python. The project is designed to retrieve real-time market data, append it to a historical dataset, and visualize key insights using Seaborn and Matplotlib.

## Features
- **Automated API Calls**: Periodically fetches cryptocurrency market data using CoinGecko API.
- **Data Storage**: Appends new data to a CSV file to maintain historical records.
- **Data Processing**: Cleans and processes the retrieved data using Pandas.
- **Data Visualization**: Uses Seaborn and Matplotlib to create insightful plots.
- **Error Handling**: Implements robust exception handling for API requests.

## Technologies Used
- **Python**
- **Pandas** (for data manipulation)
- **Seaborn & Matplotlib** (for data visualization)
- **Requests** (for API calls)
- **CoinGecko API** (for cryptocurrency market data)

## Installation
To run this project, ensure you have Python installed along with the required libraries. Install dependencies using:
```bash
pip install requests pandas seaborn matplotlib
```

## Usage
1. Run the script to start fetching cryptocurrency data:
```bash
python script.py
```
2. The script will fetch data every 10 seconds for 5 iterations and save it to a CSV file.
3. The stored data is processed to compute meaningful insights, including price trends and market movements.
4. The script generates plots to visualize cryptocurrency price changes over time.

## Data Flow
1. **Fetching Data**: The script sends a request to the CoinGecko API and retrieves cryptocurrency market data.
2. **Storing Data**: The fetched data is appended to a CSV file for historical tracking.
3. **Processing Data**: The dataset is cleaned and analyzed to extract key metrics.
4. **Visualization**: The data is plotted using Seaborn and Matplotlib for easy interpretation.

## Example Outputs
- **Cryptocurrency price trends over time**
- **Comparison of price fluctuations across multiple cryptocurrencies**

## Future Enhancements
- Implement a database for efficient data storage.
- Automate scheduled data pulls using a cron job.
- Expand analysis to include predictive modeling using machine learning.

## Contributing
Feel free to fork this repository and submit pull requests for improvements.
