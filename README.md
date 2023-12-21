# Trade Manager Dashboard MT5

This code is a Trade Manager Dashboard for the MetaTrader 5 (MT5) platform. It is designed to help traders manage their forex portfolio by providing information on the current positions, position sizes, and current prices of each currency in the portfolio. 

The Trade Manager Dashboard is developed by the Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com). 

## Usage

To use this Trade Manager Dashboard, follow these steps:

1. Install the Trade Manager Dashboard on your MT5 platform.
2. Open the Trade Manager Dashboard.
3. The dashboard will automatically retrieve the current positions, position sizes, and current prices for each currency in your portfolio.
4. The dashboard will display the total number of positions and detailed information for each position, including the currency, position size, and current price.
5. Use this information to manage your forex portfolio effectively.

## Code Explanation

The code is written in MQL5 language and consists of the following components:

1. Declaration of necessary variables:
   - `currencies`: an array to store currency names.
   - `positions`: an array to store position sizes.
   - `prices`: an array to store current prices.
   - `totalPositions`: the total number of positions in the portfolio.

2. Definition of necessary functions:
   - `GetPositions()`: retrieves the current positions, position sizes, and current prices for each currency in the portfolio.
   - `SortPositions()`: sorts the positions in descending order based on the position sizes.
   - `DisplayDashboard()`: displays the dashboard with the total number of positions and detailed information for each position.

3. The main program:
   - `OnStart()`: executes the main program.
     - Calls `GetPositions()` to retrieve the positions.
     - Calls `SortPositions()` to sort the positions.
     - Calls `DisplayDashboard()` to display the dashboard.

## Product Description

The Trade Manager Dashboard MT5 is a powerful tool developed by the Forex Robot Easy Team to help traders take control of their forex portfolio. It provides real-time information on the current positions, position sizes, and current prices for each currency in the portfolio.

With the Trade Manager Dashboard, traders can easily monitor their portfolio and make informed trading decisions. The dashboard displays the total number of positions and provides detailed information for each position, including the currency, position size, and current price.

This Trade Manager Dashboard is not the official product of Forex Robot Easy. It is a sample code provided by ForexRobotEasy.com to demonstrate the functionality of the Trade Manager Dashboard. To find the official developer of this product, please refer to the MQL5 platform.

For detailed reviews and trading results of this product, visit [forexroboteasy.com/forex-robot-review/trade-manager-dashboard-mt5-review-take-control-of-your-forex-portfolio/](https://forexroboteasy.com/forex-robot-review/trade-manager-dashboard-mt5-review-take-control-of-your-forex-portfolio/).
