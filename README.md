<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# MT5 Order Automation with Python

This Python script is designed to interact with the MetaTrader 5 (MT5) platform to place and manage financial orders. The script uses the `MetaTrader5` library to connect to the MT5 terminal, execute buy and sell orders, and handle the results.

## Features

- **MT5 Connection**: Establishes a connection with the MetaTrader 5 terminal.
- **Symbol Check and Selection**: Verifies if the symbol (e.g., PETR4) is available and visible in the MarketWatch. If not, it attempts to add it.
- **Order Execution**: Sends a buy order for the specified symbol and, after a brief interval, sends a sell order to close the position.
- **Error Handling**: Checks and displays error codes if order execution fails.
- **Disconnection**: Disconnects from the MT5 terminal after completing the operations.

## Requirements

- **Python**: Version 3.x
- **MetaTrader5 Library**: Install via pip using the command `pip install MetaTrader5`.

## Usage

1. **Initialization**: The script initializes the connection to the MT5 terminal.
2. **Symbol Configuration**: Defines the trading symbol and checks its availability. If necessary, it attempts to make the symbol visible.
3. **Place Buy Order**: Sends a buy order with specified parameters, including volume, price, and deviation.
4. **Close Position**: After 2 seconds, sends a sell order to close the opened position.
5. **Disconnection**: Shuts down the connection to the MT5 terminal.

## Author

- **George Telles**
