# IndexArbAlgoTrading
Algo Trading for Equity Index 

Cash Futures Arb: Cash future arbitrage is the safest form of arbitrage where in profit is captured through pricing inefficiencies between the cash and derivatives market. Future contract is an agreement to buy or sell a stock at a particular date in future. Theoretically, the price of the future contract has to be the current stock price plus the cost of capital required to buy the stock (to keep it for delivery at a future date) also called as Cost-of-Carry.

Thus, if

F = Future price of the stock
S = Current market price of the underlying stock/index
R = Risk free rate of return
T = Time in days

F= S* e^(r*t)

This is the fundamental basis (or formula) for pricing future contracts. Irrespective of what the underlying is an index or an individual stock. Thus, the future price should always reflect this premium.

An arbitrage opportunity exists if futures price are either greater than or less then the spot price plus cost-of-carry. In case the futures price are greater then cash price plus carry cost then sell the (overpriced) futures contract, buy the underlying asset in spot market and carry it until the maturity of futures contract. This is called "cash-and-carry" arbitrage. If futures are trading at discount to the spot then buy the (under priced) futures contract, short-sell the underlying asset in spot market and invest the proceeds of short-sale until the maturity of futures contract. This is called "reverse cash-and-carry" arbitrage.
