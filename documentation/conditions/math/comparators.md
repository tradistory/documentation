

comparators can be used for comparison/validation purposes and in conjunction with any valid indicator or values

> `these are the exhaustive list of comparators that could be used in conjunction with the indicators`

### up by
> up by takes a numeric value, type and can be used alongside any given indicator to compare the current candle with the previous candle and returns a boolean representing if the condition was met or not

`note: works only with one indicator on its left hand side`

***Inputs:***

value

type [options: %, abs] `defaults to '%'`

***Example:***

![VWAP](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/VWAP_upBy_Number5Percent.gif)


### down by
> down by takes a numeric value, type and can be used alongside any given indicator to compare the current candle with the previous candle and returns a boolean representing if the condition was met or not

`note: works only with one indicator on its left hand side`

***Inputs:***

indicator/value on the left

value

type [options: %, abs] `defaults to '%'`

***Example:***

![close_downBy_10Percent](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/close_downBy_10Percent.gif)


### equal to
> equal to can be used between any 2 indicators or values to validate its equality

***Inputs:***

indicator/value on the left and indicator/value on the right


### crosses below
> crosses below can be used validate if one indicator value crosses below the other

`note for best results: use this with only one indicator, try to avoid using this in a complex condition`

***Inputs:***

indicator/value on the left and indicator/value on the right

***Example:***

![crosses below](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/MA20_crossesbelow_MA50.gif)

### crosses above
> crosses above can be used validate if one indicator value crosses above the other

`note for best results: use this with only one indicator, try to avoid using this in a complex condition`

***Inputs:***

indicator/value on the left and indicator/value on the right

***Example:***

![crosses above](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/MA20_crossesabove_MA50.gif)


### lower than
> lower than can be used between any 2 indicators or values to validate if the value on the left is lower than the one on the right

***Inputs:***

indicator/value on the left and indicator/value on the right

***Example:***

![WR](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/WR_lowerthan_minusNumber90.gif)

### lower than equal to
> lower than equal to can be used between any 2 indicators or values to validate if the value on the left is lower than or equal to the one on the right

***Inputs:***

indicator/value on the left and indicator/value on the right

***Example:***

![lower than equal to](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/close_lowerthanequalto_periodmin.gif)

### higher than
> higher than can be used between any 2 indicators or values to validate if the value on the left is higher than the one on the right

***Inputs:***

indicator/value on the left and indicator/value on the right

***Example:***

![ATR](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/ATR_higherthan_Number15.gif)

### higher than equal to
> higher than equal to can be used between any 2 indicators or values to validate if the value on the left is higher than or equal to the one on the right

***Inputs:***

indicator/value on the left and indicator/value on the right

***Example:***

![higher than equal to](https://raw.githubusercontent.com/tradistory/documentation/main/assets/gifs/close_higherthanequalto_periodmax.gif)
