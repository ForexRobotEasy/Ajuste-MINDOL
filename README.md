# Ajuste MINDOL
Ajuste MINDOL is a trading software developed by Forex Robot Easy Team. The software retrieves real-time trading data from specified websites and finds the adjustment point of the Brazilian Mini Index Future.

## How It Works
The software uses the `WebRequest` library to retrieve data from the specified URLs. It then processes the retrieved data to find the adjustment point. The adjustment point is the point at which the Brazilian Mini Index Future needs to be adjusted.

The main entry point of the program is the `OnStart()` function. It links the URLs to the software, retrieves real-time trading data, and prints the adjustment point.

## Usage
To use the Ajuste MINDOL software, follow these steps:

1. Link the URLs to the software: Modify the `_urls` array in the `OnStart()` function to include the URLs from which you want to retrieve the trading data.

2. Retrieve real-time trading data: Call the `RetrieveTradingData()` function to retrieve the trading data from the specified URLs.

3. Print the adjustment point: The adjustment point will be printed in the terminal using the `Print()` function.

## Disclaimer
Please note that Forex Robot Easy is not the official developer of this product. This code is provided as a sample that can work as described in the product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/ajuste-mindol-forex-software-review-real-results-and-download/).
