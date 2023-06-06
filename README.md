# Bitcoin - USDT Historic Klines

This public GitHub repository contains historic price data for the Bitcoin - USDT trading pair. The data includes candlestick (kline) information spanning from August 17, 2017, to June 6, 2023, with various time intervals.

## Repository Structure

The repository consists of the following structure:

- `all_data.json`: A JSON file containing all the historic kline data for the specified time period.
- `years/`: A folder containing separate JSON files for each year, with data categorized by year.

## Data Format

The kline data is provided in JSON format and follows the standard structure used by various cryptocurrency exchanges. Each data entry represents a specific time interval and includes the following fields:

- `Open`: The opening price of the time interval.
- `High`: The highest price reached during the time interval.
- `Low`: The lowest price reached during the time interval.
- `Close`: The closing price of the time interval.
- `Volume`: The trading volume during the time interval.
- `Timestamp`: The timestamp indicating the start of the time interval.

## Usage

You can utilize this data for various purposes, such as backtesting trading strategies, conducting research, or analyzing historical Bitcoin price trends. To access the data, you have two options:

1. Use the `all_data.json` file to access the complete dataset for the entire specified time period.
2. Access individual yearly data files located in the `years/` folder if you are interested in specific years.

Feel free to explore the data and leverage it according to your needs.

## Disclaimer

Please note that the provided data is for informational purposes only. It is always essential to conduct thorough analysis and exercise caution while making financial decisions. The data in this repository should not be considered as financial advice.

## Contributions

Contributions to this repository are welcome. If you have any improvements, suggestions, or would like to add more data, feel free to create a pull request.

## License

The data in this repository is made available under the [MIT License](LICENSE). Please review the license file for more information.

