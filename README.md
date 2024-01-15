# M W Scanner MT5

This is the ReadMe file for M W Scanner MT5, a Forex trading tool developed by the Forex Robot Easy Team. For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/m-w-scanner-mt5-review-one-click-multi-timeframe-forex-scan/).

## Global Variables

- `g_symbolCount`: Total number of symbols
- `g_currentSymbolIndex`: Index of the current symbol being analyzed
- `g_timeframeCount`: Total number of timeframes
- `g_currentTimeframeIndex`: Index of the current timeframe being analyzed

## OnInit Function

The `OnInit` function is called once when the Expert Advisor is initialized. It initializes the global variables.

## OnStart Function

The `OnStart` function is called when the Expert Advisor is started. It waits for the user to trigger the multi-timeframe scan by pressing a button. Once the button is pressed, it starts analyzing each symbol and timeframe using the `AnalyzeSymbolAndTimeframe` function. After all symbols and timeframes have been analyzed, it performs market analysis using the `PerformMarketAnalysis` function.

## AnalyzeSymbolAndTimeframe Function

The `AnalyzeSymbolAndTimeframe` function performs analysis for a given symbol and timeframe. The code for analyzing the symbol and timeframe is not provided in this sample code.

## PerformMarketAnalysis Function

The `PerformMarketAnalysis` function performs market analysis using the multi-timeframe scan results. The code for market analysis is not provided in this sample code.

## IsButtonPressed Function

The `IsButtonPressed` function checks if the scanner button is pressed. The actual code for checking if the button is pressed is not provided in this sample code.

Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
