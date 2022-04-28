

a typical definition:
> Technical indicators are heuristic or pattern-based signals produced by the price, volume, and/or open interest of a security or contract used by traders who follow technical analysis. By analyzing historical data, technical analysts use indicators to predict future price movements. `- Excerpts from Investopedia`


> `the exhaustive list of supported indicators`

### OHLCV (Open, High, Low, Close, Volume)
> OHLCV are the basic constituents of the price/candle data

O = Open, opening price of the candle

H = High, highest price of the candle

L = Low, lowest price of the candle

C = Close, closing price of the candle

V = Volume, volume/quantity traded for the candle

### Number (to represents the numeric)
> Number indicator is used to represent the numeric values (Could be Int or Float or Double)

***Example:***

![SO](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/SO_lowerthan_Number.gif)

### Accumulation Distribution Line (ADL)
> ADL indicator takes HLC price & volume data and gives back a resultant number that represents the ADL value

***Inputs:***

Nil

***Example:***

![ADL](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/ADL_lowerthan_Number.gif)

***Reference:***

[ADL](https://www.tradingview.com/support/solutions/43000501770-accumulation-distribution-adl/)

### Average True Range (ATR)
> ATR indicator takes HLC price data and a period and gives back a resultant number that represents the ATR value

***Inputs:***

Period `'Period' values in all indicators are defaulted to 14`

***Example:***

![ATR](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/ATR_higherthan_Number15.gif)


***Reference:***

[ATR](https://www.thebalance.com/how-average-true-range-atr-can-improve-trading-4154923)


### Bollinger Bands (BB)
> BB takes OHLCV, period, standard deviation, level (upper, middle, lower) and gives back 3 values representing the upper, middle & lower band values

***Inputs:***

OHLCV `'OHLCV' values in all indicators are defaulted to 'Close'`

Period

standard Deviation `Defaults to 2`

level [options: upper, middle, lower] `defaults to lower`


***Example:***

![BB](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/close_lowerthan_BB-lower.gif)

***Reference:***

[BB](https://www.investopedia.com/trading/using-bollinger-bands-to-gauge-trends/)



### Commodity Channel Index (CCI)
> CCI takes OHLC, period and gives back a result representing CCI value

***Inputs:***

Period

***Example:***

![CCI](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/CCI_lowerthan_minusNumber30.gif)

***Reference:***

[CCI](https://www.investopedia.com/terms/c/commoditychannelindex.asp)

### Force Index (FI)
> FI takes OHLCV, Period and gives back a number representing the FI value

***Inputs:***

Period

***Example:***

![FI](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/FI_lowerthan_Number0.gif)

***Reference:***

[FI](https://www.investopedia.com/terms/f/force-index.asp)


### Moneyflow Index (MFI)
> MFI takes HLCV, Period and gives back a number representing the MFI value

***Inputs:***

Period

***Example:***

![FI](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/MFI_lowerthan_Number10.gif)

***Reference:***

[MFI](https://www.investopedia.com/terms/m/mfi.asp)


### On Balance Volume (OBV)
> OBV takes OHLCV and gives back a number representing the OBV value

***Inputs:***

OHLCV

Period

***Example:***

![OBV](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/OBV_higherthan_volume_dividedby_close.gif)

***Reference:***

[OBV](https://www.investopedia.com/terms/o/onbalancevolume.asp)


### Rate of Change (ROC)
> ROC takes OHLC, Period and gives back a number representing the ROC value

***Inputs:***

OHLC

Period

***Example:***

![ROC](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/ROC_lowerthan_minusNumber10.gif)

***Reference:***

[ROC](https://www.investopedia.com/terms/p/pricerateofchange.asp)


### Relative Strength Index (RSI)
> RSI takes OHLCV, Period and gives back a number representing the RSI value

***Inputs:***

OHLCV

Period

***Example:***

![RSI](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/close_lowethan_MA200_AND_RSI_lowethan_Number30.gif)

***Reference:***

[RSI](https://www.investopedia.com/terms/r/rsi.asp)


### Moving Average (MA)
> MA takes OHLCV, Period, type [simple, exponential, weighted, smoothed, dynamic weighted] and gives back a number representing the MA value for the given MA type

***Inputs:***

OHLCV

Period

***Example:***

![MA](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/close_lowethan_MA200_AND_RSI_lowethan_Number30.gif)

***Reference:***

[MA](https://www.investopedia.com/articles/active-trading/052014/how-use-moving-average-buy-stocks.asp)

[SMA](https://www.investopedia.com/terms/s/sma.asp)

[EMA](https://www.investopedia.com/terms/e/ema.asp)

[WMA](https://corporatefinanceinstitute.com/resources/knowledge/trading-investing/weighted-moving-average-wma/)

[Smoothed](https://in.tradingview.com/scripts/smma/)

[DW](https://github.com/kaelzhang/finmath#dynamic-weighted-moving-average-dmadata-alpha-nohead)



### Stochastic Oscillator (SO)
> SO takes HLC, type [%K, %d], Period, Signal Period and gives back 2 numbers representing k & d values

***Inputs:***

type [options: %k, %d] `defaults to %k`

Period

Signal Period `defaults to 3`

***Example:***

![SO](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/SO_lowerthan_Number.gif)

***Reference:***

[SO](https://www.investopedia.com/terms/s/stochasticoscillator.asp)

### Volume Weighted Average Price (VWAP)
> VWAP takes HLCV and gives back a number representing the VWAP value

***Inputs:***

Nil

***Example:***

![VWAP](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/VWAP_upBy_Number5Percent.gif)

***Reference:***

[VWAP](https://www.investopedia.com/terms/v/vwap.asp)

### Volume Profile (VP)
> VP takes OHLCV, type [bullish, bearish, range start, range end, total], Period and gives back numbers for every single type: bullish, bearish, range start, range end, total

***Inputs:***

type [options: bullish, bearish, range start, range end, total volume] `defaults to 'total volume'`

***Example:***

![VP](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/VP_higherthan_Number0.gif)

***Reference:***

[VP](https://in.tradingview.com/scripts/volumeprofile/)


### WilliamsR (W%R)
> W%R takes HLC, Period and gives back a number representing the W%R value

***Inputs:***

Period

***Example:***

![WR](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/WR_lowerthan_minusNumber90.gif)

***Reference:***

[W%R]([https://www.investopedia.com/terms/w/williamsr.asp](https://www.investopedia.com/terms/w/williamsr.asp))

### Offset
every single indicator mentioned above comes with an option to set an offset, which takes an integer/number.

it defaults to 0 which represents current candle, whereas if you want to define the previous candle then the offset should be -1, similarly if you want to represent the next day candle, then the offset value should be 1

`Note: the number should always get incremented or decremented by 1`
