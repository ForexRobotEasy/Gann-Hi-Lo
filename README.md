# Gann Hi Lo Indicator

This code is an implementation of the Gann Hi Lo indicator for MetaTrader 5 (MQL5). The Gann Hi Lo indicator is used to identify the highest high and lowest low price levels over a certain period of time. It also calculates the middle level and the shadow range between the highest high and lowest low.

## Indicator Settings

- `indicator_buffers 4`: Sets the number of indicator buffers to 4.
- `indicator_color1 Red`: Sets the color of the first buffer to Red.
- `indicator_color2 Lime`: Sets the color of the second buffer to Lime.
- `indicator_color3 Gray`: Sets the color of the third buffer to Gray.
- `indicator_color4 Gainsboro`: Sets the color of the fourth buffer to Gainsboro.
- `indicator_width1 2`: Sets the width of the first buffer to 2.
- `indicator_width2 2`: Sets the width of the second buffer to 2.
- `indicator_width3 1`: Sets the width of the third buffer to 1.
- `indicator_width4 1`: Sets the width of the fourth buffer to 1.

## Indicator Buffers

- `HighBuffer[]`: Buffer to store the highest high price levels.
- `LowBuffer[]`: Buffer to store the lowest low price levels.
- `MiddleBuffer[]`: Buffer to store the middle price levels.
- `ShadowBuffer[]`: Buffer to store the shadow range.

## Indicator Initialization

- `OnInit()`: Initializes the indicator by setting the indicator buffers, styles, labels, shifts, and draw beginnings.

## Indicator Calculation

- `OnCalculate()`: Calculates the indicator values based on the input price data. It iterates over the price data and calculates the highest high, lowest low, middle, and shadow values for each bar.

## Product Description

The Gann Hi Lo indicator is a powerful tool for identifying key price levels in the financial markets. It helps traders to determine the highest high and lowest low price levels over a certain period of time, as well as the middle level and the range between the highest high and lowest low.

This Gann Hi Lo indicator is a sample code provided by ForexRobotEasy. Please note that ForexRobotEasy is not the official developer of this product. We only show a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/gann-hi-lo-forex-software-unbiased-review-results/).
