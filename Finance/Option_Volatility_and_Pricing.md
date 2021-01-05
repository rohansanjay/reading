# Option Volatility and Pricing by Sheldon Natenberg (2nd Edition)

### Table of Contents

[Quotes I like](https://github.com/rohansanjay/reading/blob/main/Finance/Option_Volatility_and_Pricing.md#quotes-i-like)

[Chapter 1: Financial Contracts (24:09 mins)](https://github.com/rohansanjay/reading/blob/main/Finance/Option_Volatility_and_Pricing.md#chapter-1-financial-contracts-2409-mins)

- Buying and Selling

- Notional Value of a Forward Contract

- Settlement Procedures

- Market Integrity

[Chapter 2: Forward Pricing (24:09 mins)](https://github.com/rohansanjay/reading/blob/main/Finance/Option_Volatility_and_Pricing.md#chapter-2-forward-pricing-2409-mins)

- Physical Commodities (Grains, Energy Products, Precious Metals, etc.)

- Stock

- Bonds and Notes

- Foreign Currencies

- Stock and Futures Options

- Arbitrage

- Dividends

- Short Sales

[Chapter 3: Contract Specifications and Option Terminology (23:00 mins)](https://github.com/rohansanjay/reading/blob/main/Finance/Option_Volatility_and_Pricing.md#chapter-3-contract-specifications-and-option-terminology-2300-mins)

- Contract Specifications

- Option Price Components

[Chapter 4: Expiration Profit and Loss (23:00 mins)](https://github.com/rohansanjay/reading/blob/main/Finance/Option_Volatility_and_Pricing.md#chapter-4-expiration-profit-and-loss-2300-mins)

- Parity Graphs

[Chapter 5: Theoretical Pricing Models (37:57 mins)]()

- The Importance of Probability

- A Simple Approach

- The Black-Scholes Model

[Chapter 6: Volatility (60:57 mins)]()

- Random Walks and Normal Distributions

- Mean and Standard Deviation

- Forward Price as the Mean of a Distribution

- Volatility as a Standard Deviation

- Scaling Volatility for Time

- Volatility and Observed Price Changes

- A Note on Interest-Rate Products

- Lognormal Distributions

- Interpreting Volatility Data

[Chapter 7: Risk Measurement I (44:51 mins)]()

- The Delta

- The Gamma

- The Theta

- The Vega

- The Rho

- Interpreting the Risk Measures

[Chapter 8: Dynamic Hedging (32:12 mins)]()

- Original Hedge

[Chapter 9: Risk Measurement II (39:06 mins)]()

- Delta

- Theta

- Vega

- Gamma

- Lambda (Λ)

[Chapter 10: Introduction to Spreading (25:18 mins)]()

- What Is a Spread?

- Option Spreads

[Chapter 11: Volatility Spreads (73:36 mins)]()

- Straddle

- Strangle

- Butterfly

- Condor

- Ratio Spread

- Christmas Tree

- Calendar Spread

- Time Butterfly

- Effect of Changing Interest Rates and Dividends

- Diagonal Spreads

- Choosing an Appropriate Strategy

- Adjustments

- Submitting a Spread Order

[Chapter 12: Bull and Bear Spreads (34:30 mins)]()

- Naked Positions

- Bull and Bear Ratio Spreads

- Bull and Bear Butterflies and Calendar Spreads

- Vertical Spreads

[Chapter 13: Risk Considerations (48:18 mins)]()

- Volatility Risk

- Practical Considerations

- How Much Margin for Error?

- Dividends and Interest

- What Is a Good Spread?

[Chapter 14: Synthetics (18:24 mins)]()

- Synthetic Underlying

- Synthetic Options

- Using Synthetics in a Spreading Strategy

- Iron Butterflies and Iron Condors

[Chapter 15: Option Arbitrage (54:03 mins)]()

- Options on Futures

- Locked Futures Markets

- Options on Stock

- Arbitrage Risk

[Chapter 16: Early Exercise of American Options (54:03 mins)]()

- Arbitrage Boundaries

- Early Exercise of Call Options on Stock

- Early Exercise of Put Options on Stock

- Impact of Short Stock on Early Exercise

- Early Exercise of Options on Futures

- Protective Value and Early Exercise

- Pricing of American Options

- Early Exercise Strategies

- Early Exercise Risk

[Chapter 17: Hedging with Options (35:39 mins)]()

- Protective Calls and Puts

- Covered Writes

- Collars

- Complex Hedging Strategies

- Hedging to Reduce Volatility

- Portfolio Insurance

[Chapter 18: The Black-Scholes Model (34:30 mins)]()

- n(x) and N(x)

- A Useful Approximation

- The Delta

- The Theta

- Maximum Gamma, Theta, and Vega

[Chapter 19: Binomial Option Pricing (35:39 mins)]()

- A Risk-Neutral World

- Valuing an Option

- The Delta

- The Gamma

- The Theta

- Vega and Rho

- The Values of u and d

- Gamma Rent

- American Options

- Dividends

[Chapter 20: Volatility Revisited (57:30 mins)]()

- Historical Volatility

- Volatility Forecasting

- Implied Volatility as a Predictor of Future Volatility

- Forward Volatility

[Chapter 21: Position Analysis (62:06 mins)]()

- Some Thoughts on Market Making

- Stock Splits

[Chapter 22: Stock Index Futures and Options (43:42 mins)]()

- What Is an Index?

- Stock Index Futures

- Stock Index Options

[Chapter 23: Models and the Real World (46:00 mins)]()

- Markets Are Frictionless

- Interest Rates Are Constant over the Life of an Option

- Volatility Is Constant over the Life of the Option

- Trading Is Continuous

- Expiration Straddles

- Volatility Is Independent of the Price of the Underlying Contract

- Underlying Prices at Expiration Are Lognormally Distributed

- Skewness and Kurtosis

[Chapter 24: Volatility Skews (52:54 mins)]()

- Modeling the Skew

- Skewness and Kurtosis

- Skewed Risk Measures

- Shifting the Volatility

- Skewness and Kurtosis Strategies

- Implied Distributions

[Chapter 25: Volatility Contracts (56:21 mins)]()

- Realized Volatility Contracts
- Implied Volatility Contracts
- Trading the VIX
- Replicating a Volatility Contract
- Volatility Contract Applications
- Afterword: A Final Thought

[Khan Academy Videos Supplement]()

### Quotes I like

- "The secret, if there is one, is in learning as much as possible, applying in the real world what has been learned, and analyzing both one’s successes and one’s failures."

### Chapter 1: Financial Contracts (24:09 mins)

- Cash transaction: buyer and seller agree on the price and transact
- Forward contract: the parties agree on terms now but exchange does not take place until a later date (maturity or expiration date)
  - Ex: a bakery will enter a forward contract to eliminate the risk or rising grain
  - Also known as a futures contract
- Option contract: gives one party the right to make a decision at a later date
  - Call option: gives one party the right to decide at a later date whether to **buy**
  - Put option: gives one party the right to decide to **sell** at a later date
  - Premium: the payment that the seller keeps regardless of the buyer's decision
- Forwards, futures, and options are all referred to as derivatives 

#### Buying and Selling

- With derivatives, you can buy then sell, or sell then buy
  - Profit depends on which price is lower
- First trade is the opening trade -> open position
  - The subsequent trade is the closing trade
  - Open interest = the number of contracts that have not been closed out
  - If the trader first buys the contract (opening trade) = long 
    - Results in debit (pay money when you buy)
  - If the trader first sells the contract (opening trade) = short 
    - Results in credit (expect to get money when you sell)

#### Notational Value of a Forward Contract

- No money changes hands when a forward contract is initially traded
- Notation value = number of units to be deliver at maturity price * unit price
  - Ex: delivery of 1000 units at $75/unit = $75,000

#### Settlement Procedures

- The transfer of money and ownership when the contract is traded depends on the exchange
- Margin deposit: security against possible default by the buyer or seller
  - Exchange tries to make this high enough to protect but low enough to trade
- Variation: credit or debit that results from fluctuations in the price of a futures contract
- Two ways for a trader to close out a position
  - Make an offsetting trade, selling out the contract initially bought or buying back the contract initially sold
  - Carry the position to maturity -> physical settlement (seller makes delivery and buyer pays)
- What about options? They are settled like stock
  - They must be paid for immediately and in full
  - All profits or losses are unrealized until the position is liquidated
  - This causes problems when trying to hedge futures with options because traders must pay variation with futures but options, like stock, are unrealized
    - Losses from futures require immediate cash outlay to cover variation requirements

#### Market Integrity

- The exchange is responsible for instilling buyer and seller confidence
  - The exchange becomes the buyer or the seller and the seller of the buyer
    - If either defaults, the exchange guarantees payment
  - So exchanges establish clearinghouse: a separate division of the exchange responsible for processing and guaranteeing all trades on the exchange
    - The 2 largest derivatives clearinghouses are the Options Clearing Corporation and the CME Clearing House
- The margin for a professional trader on an equity options exchange is sometimes called a haircut

*options and futures are confusing haha but easier to understand with examples*

### Chapter 2: Forward Pricing (24:09 mins)

- Forward price = current cash price + costs of buying now - benefits of buying now

- Basis = cash price - forward price

  - Usually negative because the cost of buying now outweighs the benefit

- Common costs and benefits for stocks and forex

- | instrument       | Costs of buying now            | Benefits of buying now         |
  | ---------------- | ------------------------------ | ------------------------------ |
  | stock            | Interest on the stock price    | Dividends (if any) + interest  |
  | Foreign currency | Interest on borrowing domestic | Interest earned on the foreign |

#### Physical Commodities

- If you buy now, you pay the current price + the interest on the amount
  - C = commodity price, t = time to maturity, r = interest rate, s = annual storage costs/commodity, i = annual interest costs/commodity, F = forward price
    - F = C * (1 + r * t) + (s * t) + (I * t)
    - Normal/contago = long-term futures trade at premium to short term
    - Backward = cash price of commodity is greater than futures price
      - Ex: cost of storage is high and factory loses money by just staying open
  - S = stock price, t = time to maturity, r = interest rate, d_i = each dividend payment, t_i = time remaining to maturity, ri = applicable interest rate from each divident payment
    - F = [S * (1 * r * t)] - sum[dn * (1 + r_n * t_n)]

#### Stock and Future Options

- Stock and future options are the most common exchange traded options
  - Almost all exchange traded options on physical commodities, bonds, and forex are futures options
    - Ex: someone trading options on crude oil is really trading options on crude oil futures
- The value of the option depends on the forward price of the underlying contract
  - The forward price for a futures contract is the futures price
  - Ex: if a 3 month futures contract is trading at $75, the 3 month forward price is $75
  - This makes futures options easier than stock options because you don't need to calculate the forward price

#### Arbitrage

- Buying and selling the same or very closely related instrument in different markets to profit from an apparent mispricing
  - Ex: in forex, a trader might try to profit by borrowing low interest domestic currency and using it to buy a high interest foreign currency
    - Hopes to pay a low interest rate and earn a high interest rate
- Cash and carry arbitrage: buying the the cash market, selling in the futures market, and carrying the position to maturity
  - Ex: calculated forward price = $69.02 and the price of the forward contract is $69.50
    - So the trader sells the forward contract at $69.50 and buys the stock
    - Profit = 69.50 - 69.02 = $0.48 -> cash and carry arbitrage

#### Dividends

- Declared date: date when the company announces the amount and pay date
- Record date: date on which the stock must be owned to receive the dividend

#### Short Sales

- Selling stock that you don't own hoping to back back the stock later at a lower price
  - The trader first borrows the stock
    - Stock short squeeze: it is difficult or impossible to borrow stock
    - The brokerage firm (seller) pays interest to the trader on the amount of the sale
      - This is because the trader theoretically has the money from the "sale"
        - But the seller only pays a portion of the full interest based on how hard it is to borrow the stock
          - Difficult = no interest
      - But the trader pays back any dividends
- You can short when the forward price is lower than the current price
  - Buy a forward contract and sell the stock
  - But if you don't already own the stock, you could lose money by losing interest
- For options, always apply the ordinary long rate to the cash flow

*interest makes things confusing but I also see where quant probably comes in with calculating forward pricing models and trading for any arbitrage...*

### Chapter 3: Contract Specifications and Option Terminology (23:00 mins)

- People trade options with different goals
  - Ex: opinion on price movements, hedging, arbitrage, etc. 
  - Very important to understand the terminology 

#### Contract Specifications

- type
  - Call = right to buy or take long position in an asset at a fixed price on or before a specified date
  - Put = right to sell or take a short position in an asset
  - Difference between options and futures: futures require delivery at a fixed price because buyers/sellers have guidelines but options give choice
    - Trader can choose to take delivery (call) or sell delivery (put)
    - If the buyer chooses to make/take delivery, the seller must take the other side
    - Right lie with the buyer and obligations with the seller
- Underlying 
  - The underlying asset is the security or commodity to be bought or sold under the terms of the option contract
    - For stock exchanges, the underlying is usually 100 shares
      - The owner of a call has the right to buy 100 shares
      - The owner of a put has the right to sell 100 shares
    - For futures options, the underlying is uniformly one futures contract
      - The owner of the call has the right to buy one futures contract
      - The owner of the put has the right to sell one futures contract
      - Usually the futures month corresponds to the expiration month of the option
        - Ex: the underlying for an April futures option is an April futures contract
      - In a *serial option*, there is no corresponding futures month
        - So the underlying contract is the nearest futures contract beyond expiration of the option
        - Ex: the underlying for a jan or feb option is a march futures contract because futures are often listed on a quarterly cycle
      - Midcurve options: short-term options on long-term futures
- Expiration date (expiry)
  - Date on which the owner of the option must make the final decision to buy (call) or sell (put)
    - For many exchanges, this will be the 3rd Friday of the expiration month
  - AM expiration is used for stock index contracts (opening price rather than the closing price on the last trading day)
- Exercise price
  - The price at which the underlying will be delivered should the holder of the option choose to exercise the right to buy or sell
    - If exercised, the owner of a call will pay the exercise price or the owner of a put will receive the exercise price
  - Exercise prices are set by the exchange, usually at equal intervals around the current price of the underlying
- Exercise and Assignment
  - The buyer of a call or put has the right to exercise that option prior to its expiration date
    - Can cover the option into a long underlying position (call) or short underlying position (put)
  - When a valid exercise is submitted, a seller is assigned 
    - The seller is someone who has sold the option and has not closed out the position through an offsetting trade
      - This decision is assigned randomly
    - \## this part is a bit confusing
  - Summary 
    - If you exercise a call -> choose to *buy* at the exercise price
    - If you are assigned a call -> required to *sell* at the exercise price
    - If you exercise a put -> choose to *sell* at the exercise price
    - If you are assigned a put -> required to *buy* at the exercise price
- Settlement into physical underlying
  - The exerciser of a call pays the exercise price regardless of the actual price
    - Same in the opposite for a put
- Settlement in a futures position
  - It is like the exerciser is buying or selling the futures contract at the exercise price
    - Requires margin and variation
- Settlement into cash
  - Used primarily for index contracts
    - Cash payment = difference between the exercise price and the underlying price
- Exercise style
  - European: can only be exercised at expiration 
    - Holder must make decision to exercise or not on the last business day
  - American: can be exercised on any business day prior to expiration
  - This doesn't have to do will location 
    - Futures and stock are usually American and indexes are usually European 

#### Option Price Components

- And options price/premium is determined by supply and demand
  - Buyers and sellers make competitive bids -> when bid and offer coincide, a trade is made
- Premium has two components: the intrinsic value and time value
  - And option has intrinsic value if it enables the holder of the option to buy low and sell high or sell high and buy lowe
    - Intrinsic value = different between buying and selling price
    - Ex: contract trading at 435, intrinsic value of a 400 call is 35
      - Because the holder can buy at 400
  - So call will only have intrinsic value if exercise price is less than current market price and put will only have intrinsic value if exercise price is greater than current market price
    - Call intrinsic value = max of 0 or S - X
    - Put intrinsic value = max of 0 or X - S
    - Usually the option price is greater than its intrinsic value
  - Time value (time premium/extrinsic value) = additional amount of premium beyond the intrinsic value that traders are willing to pay for an option
    - Willing to pay this additional amount because of the protective characteristics of an option over an outright long or short position in the underlying
    - So an options premium is always intrinsic value + ev
      - Ex: 400 call trading at 50 with underlying 435
        - Ev is 15 and intrinsic value is 35
    - If the option has no time value, it is trading at **parity**
- In the money = any option that has positive intrinsic value by the amount of iv
  - Traders can capture value by selling the option or exercising and closing the underlying
  - Most exchanges have automatic exercise for these cases
- Out the money = no intrinsic value -> price is solely time value
- At the money = option with exercise price same as current price
  - Technically out the money since it has no iv
  - But these are desirable so they are usually most actively traded

*puts are more confusing to me -> need to talk through them*

### Chapter 4: Expiration Profit and Loss (23:00 mins)

- Options traders have a many different contracts to choose from
  - Which one to buy? You need to know what the option is worth
  - There is one time when everyone can agree on one answer: expiration
    - The option is worth exactly its intrinsic value -> 0 if its out of the money or difference between exercise and underlying if its in the money

#### Parity Graphs

- intrinsic value = credit or positive value for someone who buys an option
  - Buyer can buy low and sell high
- intrinsic value = debit for seller of an option
  - Forced to sell low and buy high
- The option value increases by 1 point for each 1 point increase (call) or decrease (put) in intrinsic value when in the long position
  - Opposite for short (out the money)
- Parity graph shows the value of an option at expiration (parity = iv)
  - These show options have **limited risk**
    - Buyers can never lose more than the price of the option but have unlimited upside
    - Sellers of options have limited profit -> they can never make more than the price
      - Also have unlimited risk
  - So why sell options? Unbalanced risk reward right?
    - Because of the likelihood of possible occurrences
    - If the price is high enough and the perceived risk is low enough, then a trader might be willing to take it
- Slope = change in position value / change in underlying (0, 1, or -1)
  - You can also stack slopes by stacking the options
    - Ex: two long call options can have a slope of +2 above the exercise price
  - You can also combine options with the underlying contract
  - Even if the combination of options is complex, you can construct the parity graph by:
    - Determining slopes of the graph below the lower exercise, highest exercise, and between, and then connect all segments
- PnL
  - You contract PnL by seeing where the position(s) result in debit/credit and adding/subtracting the option cost depending on call/put and long/short

### Chapter 5: Theoretical Pricing Models (37:57 mins)

- Traders who think underlying will rise are more inclined to buy calls or sell puts
- Traders who think underlying will fall are more inclined to buy puts of sell calls
- But a problem for options traders is the **speed** of the market
  - The underlying needs to rise/fall within a certain period of time for the trader to profit or the option expires worthless and the trader loses money
  - And further expirations could be more expensive so that is not always an option
  - So options traders need to think about how fast the market will move because they need to be right about direction **and** speed
    - But most people have trouble prediction just market direction...
- Many option strategies depend only on the speed of the market and not at all on direction
  - If you can predict direction well, you might as well just trade the underlying then

### Chapter 6: Volatility (60:57 mins)
### Chapter 7: Risk Measurement I (44:51 mins)
### Chapter 8: Dynamic Hedging (32:12 mins)
### Chapter 9: Risk Measurement II (39:06 mins)
### Chapter 10: Introduction to Spreading (25:18 mins)
### Chapter 11: Volatility Spreads (73:36 mins)
### Chapter 12: Bull and Bear Spreads (34:30 mins)
### Chapter 13: Risk Considerations (48:18 mins)
### Chapter 14: Synthetics (18:24 mins)
### Chapter 15: Option Arbitrage (54:03 mins)
### Chapter 16: Early Exercise of American Options (54:03 mins)
### Chapter 17: Hedging with Options (35:39 mins)
### Chapter 18: The Black-Scholes Model (34:30 mins)
### Chapter 19: Binomial Option Pricing (35:39 mins)
### Chapter 20: Volatility Revisited (57:30 mins)
### Chapter 21: Position Analysis (62:06 mins)
### Chapter 22: Stock Index Futures and Options (43:42 mins)
### Chapter 23: Models and the Real World (46:00 mins)
### Chapter 24: Volatility Skews (52:54 mins)

### Chapter 25: Volatility Contracts (56:21 mins)

### Khan Academy Videos Supplement

Basic Shorting

- First you borrow the stock -> sell at the current price -> buy it back at a lower price (hopefully) -> then give it back to the owner
  - Profit = sell price - buy price (unlimited downside)

Put Options

- Gives you the right to **sell** company X at $Y
  - If you don't already own it, you can buy it (at the lower price) and then sell it right away

Call Option as Leverage

- Calls give you **leverage** because you are making the same bet as buying a stock but you are **multiplying** your potential gain/loss relative to your starting upfront capital

Put Option as Leverage

- When you short, you still have to put down some starting capital even though you technically are borrowing stock
- You multiply your gains relative to shorting
  - Lots of protection on the downside

Call Payoff Diagram

- Looks like a hockey stick because the value of the option is flat when less than stick price but has a slope of 1 when greater than strike
- P/L graph shows the same thing but accounts for the price of the option (negative before breaking even)

Put Payoff Diagram

- Value of the stock decreases as the price of underlying increases