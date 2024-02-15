# Deep Pound MT5

Deep Pound MT5 is a trading expert advisor designed to trade the GBP/USD currency pair on the MetaTrader 5 platform. This code serves as a sample implementation of the trading logic used in the Deep Pound MT5 expert advisor. 

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/deep-pound-mt5-review-elevate-gbpusd-trading-with-tft-tech/). Please note that ForexRobotEasy is not the official developer of this product. We only provide this code as a reference to demonstrate how the product works. To find the official developer of this product, please refer to MQL5.

## Global Variables

- `tradeAllowed`: Flag to determine if trading is allowed. By default, it is set to 1, indicating that trading is allowed.
- `startDate`: Start date for trading. By default, it is set to January 15, 2022.
- `endDate`: End date for trading. By default, it is set to December 15, 2022.

## Expert Initialization Function

The `OnInit` function is called during the initialization of the expert advisor. It checks if the current date is within the restricted period (specified by `startDate` and `endDate`) and disables trading if necessary.

## Expert Deinitialization Function

The `OnDeinit` function is called when the expert advisor is being deinitialized. It provides an opportunity to clean up any resources used by the expert advisor.

## Expert Tick Function

The `OnTick` function is called on every tick of the price data. It checks if trading is allowed and executes the trading logic if permitted. In the sample code, it displays a 'Buy signal' message and places a buy order when a condition is met. It also includes placeholders for trade execution and performance statistics updates.

## Custom Functions

- `IsTradeAllowed()`: This function checks if trading is allowed based on the current date and the restricted period defined by `startDate` and `endDate`.
- `UpdatePerformance()`: This function is responsible for updating performance statistics. 

Please note that this code is a simplified version of the actual Deep Pound MT5 expert advisor. The complete expert advisor may have additional features and trading logic.

For detailed information and to obtain the official version of this product, please visit MQL5.

