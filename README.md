# Oberon iMA

Oberon iMA is an expert advisor (EA) developed by the Forex Robot Easy Team. This EA is designed to trade in the Forex market using a 15-block trading strategy. It is compatible with the MetaTrader 5 (MT5) trading platform.

## Features

- Adjustable block size: The user can customize the size of each trading block according to their preferences.
- Timeframe selection: The EA can be used on different timeframes, allowing flexibility in trading strategies.
- Testing modes: The EA supports different testing modes, including every tick mode, to ensure accurate backtesting results.

## Input Parameters

- BlockSize: The size of each trading block.
- TimeFrame: The timeframe used for trading.
- TestingMode: The testing mode used for backtesting.

## Initialization

During the initialization phase, the EA calculates the total number of blocks based on the tick size of the selected symbol. It also sets the initial block and symbol values. Additionally, it checks if trading is allowed based on the magic number.

## Tick Function

The tick function is responsible for executing trading operations. It checks if the current block has been completed and updates the current block and symbol accordingly. It also checks if trading is allowed for the new symbol. If trading is not allowed, the function returns without executing any trading operations. Otherwise, it performs the necessary trading operations.

## Deinitialization

The deinitialization function is executed when the EA is removed from the chart or the trading platform is closed. It performs any necessary deinitialization tasks.

## Product Description

Oberon iMA is a powerful expert advisor developed by the Forex Robot Easy Team. It is designed to provide traders with a reliable and efficient trading solution in the Forex market. With its customizable block size and flexible timeframe selection, traders can tailor the EA to their trading preferences and strategies.

This EA utilizes a 15-block trading strategy, which has been proven to be profitable in the Forex market. By analyzing market conditions and executing trades based on these blocks, Oberon iMA aims to generate consistent profits for its users.

Please note that Forex Robot Easy is not the official developer of Oberon iMA. We provide this sample code to demonstrate how the EA works as described in the product. For detailed reviews and trading results of this product, please visit the official developer's website at [https://forexroboteasy.com/forex-robot-review/oberon-ima-review-profiting-with-15-block-forex-software/](https://forexroboteasy.com/forex-robot-review/oberon-ima-review-profiting-with-15-block-forex-software/). To find the official developer of this product, please refer to MQL5.
