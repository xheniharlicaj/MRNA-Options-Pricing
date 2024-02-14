# Options-Valuation for MRNA
Modern Inc. (MRNA) is a biotechnology company that focuses on developing mRNA-based vaccines and therapeutics. It gained a lot of attention in recent years due to its development of mRNA vaccines, particularly for COVID-19.

This code calculates the theoretical prices of European call and put options using the Black-Scholes option pricing model. It obtains historical stock price data and option chain data for the "MRNA" stock. 

The script calculates the historical volatility of the stock returns and the time to expiration of the options. It takes as input the strike price we want. It then uses the Black-Scholes formula to estimate the theoretical option prices based on the current stock price, time to expiration, risk-free interest rate, volatility, as well as our chosen strike price.

Lastly, it compares the calculated option prices with the actual prices obtained from the option chain data. 

I used different strike price values so that I could compare the results between ATM, ITM and OTM calls and puts. For both OTM calls and puts, the prices are very close to 0.00. When the calculated prices deviate from their actual values, it can be due to various factors ssuch as market volatility or interest rates assumptions made in the model.
When the difference is significant, it means that market participants may be expecting a higher or lower volatility than what the Black-Scholes model predicts. 
We need to realize that the Black-Scholes model has its limitations. It assumes constant volatility, no dividends, and efficient markets, which may not always hold true. To conclude, although the model helps us understand how options are priced, traders need to consider other factors into their analysis, like market trends and news, to make informed decisions.
