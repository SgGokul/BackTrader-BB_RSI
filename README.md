# BackTrader-BB_RSI
Implementation of a strategy using Bollinger Bands and RSI on BackTrader

Bollinger Band is a technical analysis tool defined by a set of trendlines. Bollinger Bands are plotted on a price chart as three lines: a simple moving average (SMA) in the middle, and two standard deviation lines above and below the SMA. The standard deviation lines are calculated based on the volatility of the asset, which is determined by measuring the difference between the asset's price and its moving average over a specified period of time. The width of the Bollinger Bands expands and contracts in response to changes in volatility. When volatility is high, the bands widen, and when volatility is low, the bands narrow. Traders often use Bollinger Bands to identify potential breakouts, as prices often move outside the bands during periods of high volatility. Bollinger Bands can also be used to identify potential trend reversals. When prices move outside the bands, it may indicate that a trend is beginning to form. Additionally, when prices move back inside the bands after trending outside of them, it may indicate that the trend is losing momentum and a reversal is possible.

RSI stands for Relative Strength Index and is a technical analysis indicator used by traders to measure the strength of an asset's price action. The RSI is calculated using a mathematical formula that compares the average gain and average loss of the asset's price over a specific period of time (usually 14 periods). The RSI is displayed as a number between 0 and 100, and it is typically plotted on a chart below the asset's price data. An RSI reading above 70 indicates that the asset is overbought, meaning that it may be due for a price correction or reversal. Conversely, an RSI reading below 30 indicates that the asset is oversold, which may indicate a potential buying opportunity. Traders can also use RSI to identify divergences between the indicator and the price of the asset. For example, if the asset's price is making new highs but the RSI is not, this may indicate that the uptrend is losing momentum and a price correction could be imminent.

I have built a strategy using both these indicators. 
Long when ever stock price cross the bottom line of BB, reverses back into the channel and RSI being less than 40. 
Short when ever stock price cross the top line of BB, reverses back into the channel and RSI being greater than 60. 
Exit Long when stock price reaches the bottom line of BB and RSI being less than 50.
Exit Short when stock price reaches the top line of BB and RSI being greater than 50.
Stoploss - Prev day's close
![image](https://user-images.githubusercontent.com/107173414/225478030-4b4d7d22-a953-4624-adf7-4c4b6a58fdb8.png)
