

![](https://github.com/tradistory/documentation/raw/main/assets/images/create_strategy.png)

> `the exhaustive list of input fields required for backtesting`

### Symbol
these are the symbols or stocks on which you want to backtest your strategy upon. There can multiple scrips on which the backtest can be performed at a time

### Capital
the initial capital that you want to deploy in your strategy

### Candle Interval
determines which candle time-frame/interval/period you want to use to backtest your strategy upon. this candle's closing price is used for entry/exit

### Trade Type
CNC refers to carry forward trade and also otherwise called as long term trade, whereas MIS refers to Intraday trade

### Entry Type
represents whether the entry should be LONG or SHORT. if the entry is LONG, then exit is taken as SHORT and vice-versa.

### Start Date
represents from which date you want your strategy to be backtested.

### End Date
represents upto which date you want your strategy to be backtested.

### Strategy Name
Strategy name can be anything of your choice which is for your easy reference purposes

### Include Charges
represents if you want to consider including the charges in the backtest or not

### Take Profit
an optional field.

take profit expects a percentage integer which represents at which point you want to exit your trade. once the trade reaches a profit level that matches this number in percentage terms, then it is considered as an exit signal and the trade is exited even if the other provided exit conditions aren't met.

`Consider a scenario where you want to exit the trade after reaching a 20% profit:`

`for example, when you enter a LONG trade at 2000 and the trade goes in your favour and reached 2400, which is at 20% profit, then this is taken as an exit signal and the trade is exited even if the other provided exit conditions aren't met.`

### Take Loss
an optional field.

take loss is otherwise called as stop loss, expects a percentage integer which represents at which point you want to exit your trade. once the trade reaches a loss level that matches this number in percentage terms, then it is considered as an exit signal and the trade is exited even if the other provided exit conditions aren't met.

`Consider a scenario where you want to exit the trade after reaching a 20% loss:`

`for example, when you enter a LONG trade at 2000 and the trade doesn't go in your favour and reached 1600, which is at 20% loss, then this is taken as an exit signal and the trade is exited even if the other provided exit conditions aren't met.`


### Entry/Exit Conditions
entry or exit conditions are optionals. conditions are rules which can be formed with the indicators, comparators, math functions, math operators, logic operators, etc, that have been provided by the app. conditions are at the heart of our app and a lot of heavy lifting have been done to provide the users with the best possible tools to define their own entry & exit conditions and they're not limited by any means. conditions are one of the powerful feature in our app and you can literally use it to define & create any kind of strategy by leveraging it.
> for best results, please make sure to define the conditions as per our documentation <link goes here> since the validation is done on the backend side of the app
