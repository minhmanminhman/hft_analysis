## Task
Task is to fit a model for at least one of the labels of your choosing on the
given data set. 

We are not looking only for the best fit but the design of the
data investigation process. 

Please feel free to engineer additional features
based on the given features as you see fit.

Some brief explaination of the data contained in the columns are as follows.

## Features
timestamp  str  datetime string
bid_price  float  price of current bid in the market
bid_qty  float  quantity currently available at the bid price
bid_price  float  price of current ask in the market
ask_qty  float  quantity currently available at the ask price
trade_price  float  last traded price
sum_trade_1s  float  sum of quantity traded over the last second
bid_advance_time  float  seconds since bid price last advanced
ask_advance_time  float seconds since ask price last advanced
last_trade_time  float  seconds since last trade

## Labels
# Labels indicate what is type of the first event that will happen in the 
# next x seconds, where:
# 0 -- No price change
# 1 -- Bid price decreased
# 2 -- Ask price increased
_1s_side  int
_3s_side  int
_5s_side  int
