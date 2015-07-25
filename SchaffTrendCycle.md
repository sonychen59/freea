# Introduction #

Trading systems based on Schaff Trend Cycle.


# Details #

  * **Currency pairs**: _ANY._
  * **Time Frame**: _15M, 1H._
  * **Indicators**: _[FreEA\_SchaffTrendCycle](SchaffTrendCycle.md) and RSI(14)._
  * **Rules**:
    * Entry Phase: _When [FreEA\_SchaffTrendCycle](SchaffTrendCycle.md) goes through 25 level and RSI(14)<50 send a BUY order or When [FreEA\_SchaffTrendCycle](SchaffTrendCycle.md) crossing 75 level down and RSI(14)>50 send a SELL order._
    * Exit Phase:
      1. _When you reach TP or SL._
      1. _When gives a signal contrary and SL < Bid(Buy) or Ask(Sell)._