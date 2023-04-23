# Cross Currency Basis Swaption


A Cross-currency basis swap, which is also called FX basis swap, is a contract between two parties that one side receives a floating rate of currency A and the other receives a floating rate of currency B. An cross currency basis swaption is the option to enter an in-the-money underlying cross currency basis swap.

Between the two currencies, suppose that currency A is more liquid than currency B. For example, USD is currency A and CAD is currency B. That is, in the currency A world, there is a market difference in supply and demand of currency B. Thus the traditional interest rate parity in the currency A world may not valid without any adjustment.

Specifically, let Qt be the exchange rate at a time t which is expressed as number of units in currency A per unit of currency B, Q(t; T) be the forward exchange rate at the time t matured at a time T > t, dfA(t; T) be the discounting factor in currency A and dfB(t; T) be the one in currency B. The traditional interest rate parity can be expressed 

However, currency B, as a commodity in the currency A world, has extra convenience yield so that the relation (1) is valid provided that the discounting factor dfB(t; T) has to be adjusted, denoted by  df_B(t; T) or equivalently, the currency B zero curve has to be adjusted by a spread from the view point of currency A world.

There is initial exchange at T0 and final exchange at TN of notional principals of NA and NB, respectively. At each payment date Ti, one party pays A-floating rate plus a spread xA in currency A and the other pays B-floating rate plus a spread xB in currency B. Let t < T0 be a valuation time. Due to the reason mentioned above, the time t-value in currency A of the FX basis swap (paying A-floating and receiving B-floating) can be given.

An Fx basis swaption is the option to enter an in-the-money underlying Fx basis swap. With the notation defined above and consider the same Fx basis swap, suppose that the option expiry is T0. 

Due to the lack of quantitative analysis of the balance spread process ¤ and correlations
among balance spread, exchange rate, currency A risk-free rate and currency B risk-free rate, it should be noted that pricing Fx basis swaption is much more difficult than pricing regular interest rate swaption. Adopting some assumptions is necessary for simplifying the pricing problem. We introducing the following assumptions.

[1] Risk-free rates in currency A and currency B are deterministic. Both zero curves can be obtained from the market at any time;

[2] The adjusted short rate in curency B (from the view point of the currency A world) is
deterministic and the adjusted zero curve can also be obtained from the market at any time;

References:

https://finpricing.com/knowledge.html
