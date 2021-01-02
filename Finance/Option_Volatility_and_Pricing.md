# Option Volatility and Pricing by Sheldon Natenberg (2nd Edition)

### Table of Contents

[Quotes I like]()

[Chapter 1: Financial Contracts (24:09 mins)](https://github.com/rohansanjay/reading/blob/main/Finance/Option_Volatility_and_Pricing.md#chapter-1-financial-contracts-2409-mins)

- Buying and Selling

- Notional Value of a Forward Contract

- Settlement Procedures

- Market Integrity

[Chapter 2: Forward Pricing (24:09 mins)]()

- Physical Commodities (Grains, Energy Products, Precious Metals, etc.)

- Stock

- Bonds and Notes

- Foreign Currencies

- Stock and Futures Options

- Arbitrage

- Dividends

- Short Sales

[Chapter 3: Contract Specifications and Option Terminology (23:00 mins)]()

- Contract Specifications

- Option Price Components

[Chapter 4: Expiration Profit and Loss (23:00 mins)]()

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

### Quotes I like

- "The secret, if there is one, is in learning as much as possible, applying in the real world what has been learned, and analyzing both one’s successes and one’s failures."

### Chapter 1: Financial Contracts (24:09 mins)

- Cash transaction: buyer and seller agree on the price and transact
- Forward contract: the parties agree on terms now but exchange does not take place until a later date (maturity or expiration date)
  - Ex: a bakery will enter a forward contract to eliminate the risk or rising grain
  - Also known as a futures contract
- Option contract: gives one party the right to make a decision at a later date
  - Call option: gives one party the right to decide at a later date whether to **buy**
  - Put option: gives one party the right to decide to sell at a later date
  - Premium: the payment that the seller keeps regardless of the buyer's decision
- Forwards, futures, and options are all referred to as derivatives 

##### Buying and Selling

- With derivatives, you can buy then sell, or sell then buy
  - Profit depends on which price is lower
- First trade is the opening trade -> open position
  - The subsequent trade is the closing trade
  - Open interest = the number of contracts that have not been closed out
  - If the trader first buys the contract (opening trade) = long 
    - Results in debit (pay money when you buy)
  - If the trader first sells the contract (opening trade) = short 
    - Results in credit (expect to get money when you sell)

##### Notational Value of a Forward Contract

- No money changes hands when a forward contract is initially traded
- Notation value = number of units to be deliver at maturity price * unit price
  - Ex: delivery of 1000 units at $75/unit = $75,000

##### Settlement Procedures

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

##### Market Integrity

- The exchange is responsible for instilling buyer and seller confidence
  - The exchange becomes the buyer or the seller and the seller of the buyer
    - If either defaults, the exchange guarantees payment
  - So exchanges establish clearinghouse: a separate division of the exchange responsible for processing and guaranteeing all trades on the exchange
    - The 2 largest derivatives clearinghouses are the Options Clearing Corporation and the CME Clearing House
- The margin for a professional trader on an equity options exchange is sometimes called a haircut

### Chapter 2: Forward Pricing (24:09 mins)
### Chapter 3: Contract Specifications and Option Terminology (23:00 mins)
### Chapter 4: Expiration Profit and Loss (23:00 mins)
### Chapter 5: Theoretical Pricing Models (37:57 mins)
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