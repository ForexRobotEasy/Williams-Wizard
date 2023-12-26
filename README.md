# Williams Wizard

## Description

Williams Wizard is a Forex trading robot designed for momentum trading. It uses the market momentum indicator to determine whether to open a buy or sell position.

This code is a sample implementation of the Williams Wizard trading strategy. It calculates the lot size based on the risk percentage per trade and the account balance. It then checks if a trade is already open and if not, calculates the market momentum using the iMomentum custom function. If the momentum is positive, it opens a buy position, and if the momentum is negative, it opens a sell position.

Please note that ForexRobotEasy is not the official developer of this product. We only provide this sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Williams Wizard Review - Reliable Forex Software for Momentum Trading](https://forexroboteasy.com/forex-robot-review/williams-wizard-review-reliable-forex-software-for-momentum-trading/).

## Input Parameters

- RiskPercent: Risk percentage per trade
- LotSize: Default lot size

## Global Variables

- AccountBalance: Stores the current account balance

## Functions

- OnInit: Initializes the expert advisor. Calculates the account balance.
- OnDeinit: Performs necessary clean up tasks on deinitialization.
- OnTick: Executes the trading logic. Checks if a trade is already open, calculates the lot size based on risk percentage and account balance, calculates the market momentum using the iMomentum custom function, and opens a buy or sell position accordingly.
- iMomentum: Custom function to calculate and return the market momentum.

## Disclaimer

Please note that ForexRobotEasy is not the official developer of this product. We only provide this sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Williams Wizard Review - Reliable Forex Software for Momentum Trading](https://forexroboteasy.com/forex-robot-review/williams-wizard-review-reliable-forex-software-for-momentum-trading/).
