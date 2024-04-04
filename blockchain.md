# Blockchain

<!--toc:start-->

- [Blockchain](#blockchain)
  - [About](#about)
  - [Part 1](#part-1)
    - [History of exchange](#history-of-exchange)
      - [Barter](#barter)
      - [Barter and bitcoin](#barter-and-bitcoin)
      - [Money How](#money-how)
      - [Regulated money](#regulated-money)
    - [Web](#web)
    - [Double transaction](#double-transaction)
    - [Intermediaries](#intermediaries)
      - [Satoshi Nakamoto](#satoshi-nakamoto)
  - [Part 2](#part-2)
    - [Basics](#basics)
      - [About bitcoin](#about-bitcoin)
      - [About blockchain](#about-blockchain)
      - [About mining](#about-mining)
  - [Part 3](#part-3)
    - [Blockchain Framework](#blockchain-framework)
      - [Exchange platforms](#exchange-platforms)
      - [Order book](#order-book)

<!--toc:end-->

## About

Blockchain-focused section of the course

## Part 1

### History of exchange

#### Barter

All products are bound by offer and demand.
Their price fluctuates as much as they're required by the consumer.

The market moves through and from fear and greed. Basically **FOMO**

As the market flowed a simple piece-by-piece barter was changed into a product-standard.
This product was gold.
As a standard all barters were standardized into a gold-based value.

After, it evolved to coin-based value, then paper value and then FIAT.
_FIAT_ are currencies issued by the government,
and are not backed by a physical commodity such as gold.

With this inclusion and control,
exchanges were turned then into plastic money, and then electronic.

> What backs the dollar?
> Nothing so far.

[Wanna check how much the _US_ owes?](https://www.imf.org/en/Countries/USA)
[Check again](https://www.usdebtclock.org)

During the pandemic,
the solution thought after to solve the impending crisis was to _print_ more money.

#### Barter and bitcoin

- Good
  - A barter is the most simple form of exchanging value
  - Only practical in small circles
  - The bigger the market, more difficult to control
  - It isn't affected by market fluctuations and/or de-valuations.
  - No intermediaries
  - Non-taxable
- Bad
  - Lack of scale coincidence
  - Lack of temporary line.
    - What if i don't have the ripe apples yet?
  - Lack of location coincidence
- All three previous solved by bitcoin?
  - Apparently yes

So what's cool about BC?

- Indirectly exchange direct money.

#### Money How

- Functions
  - As a way of exchange
  - As a value deposit
  - As a _countable_ unit
- How
  - Merchandise (physical things such as diamonds, gold bar, salt, _cacao and stones_)
  - Metallic coin
  - Paper money
  - Debt
  - FIAT (backed by law)
  - Electronic

#### Regulated money

| Redeemable                                                              | Non-redeemable                                                        |
| ----------------------------------------------------------------------- | --------------------------------------------------------------------- |
| Backed by metals                                                        | Backed by the government's debt                                       |
| The govt only assumes the responsibility of holding the physical units. | The govt can emit decrees to force the population into using the coin |

### Web

- Web 1.0 & 2.0
  - Basically exchanged information from one node towards another towards another
  - Web, DOCS, PDFs, Email, PPT, Pics
- Web 3.0
  - Exchange of value instead of information
    - Art, currency.
    - Single transaction currency.

### Double transaction

Double transaction is the issue where certain $100 dollars can be duplicated
for multiple transactions by and through the same person. Basically unregulated.

- Bitcoin
  - It solves the issue of double transaction.
  - A single asset can't be sold or bartered twice.
- Traditional solutions
  - Banks as intermediaries
  - Large social media companies
  - Government
  - Large credit card companies

### Intermediaries

Decent at their job but:

| Concept     | Description                                           |
| ----------- | ----------------------------------------------------- |
| Centralized | Hackable and corruptable                              |
| Exclusion   | Exclude millions from the global economy              |
| Slow        | An email takes seconds, an electronic transfer - days |
| Comissions  | High in costs                                         |
| Info        | No privacy or access to the information               |

#### Satoshi Nakamoto

Satoshi Nakamoto created the **Bitcoin: peer-to-peer electronic system** protocol

- Bitcoin white paper:
  - Decentralized
  - No intermediaries
  - Global
  - Digital

## Part 2

### Basics

#### About bitcoin

- Distributed & decentralized.
- Only 21 million of bitcoins will ever be emitted.
- Satoshi Nakamoto (whoever he/she/they is/are) owns a million of those.
- Currently 19.6 million coins are in circulation.
  - Every 4 years, more btc are pushed out into the blockchain
  - The qty of btc pushed out is **halved** by each iteration.
  - By 2140, there will be no more full btc pushed out as the 21 million will be out.
- Not a pyramid scheme but similar (lol)

  - Decentralized so basically no one at the top
  - It's based on maket-driven value instead of recruitment.
  - Blockchain
  - Self-regulated

- History of btc:

![Timeline of btc](./img/btc_prehistory.jpeg)

#### About blockchain

- Blocks like in minecraft
- Generated every 10 minutes
- Holds transactions info
- Can be trusted
  - **Can be traced**
  - Is liquid
- Has governance

> The history is related into the [Cypherpunk movement](https://nakamoto.com/the-cypherpunks/)

![Cypherpunks](./img/cypherpunk_wired.jpg)

#### About mining

Basically whenever you want bitcoins there's only two options to get them:

- Mining
- Buy from another person that already owns btc

This results in very specific outcomes whenever someone is trading with btc.
No longer profitable due to the amount of btc in each block.

## Part 3

### Blockchain Framework

#### Exchange platforms

This refers to a digital marketplace where participants can:
buy, sell, and trade cryptocurrencies and other digital assets like tokens
and non-fungible tokens (NFTs).

Basically an exchange marketplace for cryptocurrencies:

- Immediate liquidation
  - They make transactions valid in an instant.
- Others
  - Certain operations of the financial world can take months to fulfill

There are certain classifications for platforms:

- **Classifications**

  - Cryptocurrencies, Actions or Stocks, basic products and foreign exchange market (FOREX)

- **Exchanges**
  - OTC (Over the Counter): Dealer &rarr; Broker &rarr; Dealer
  - Centralized (Traditional): Dealer &rarr; Business &rarr; Dealer
  - Decentralized (dEX): Dealer &rarr; Smart Contract &rarr; Dealer

#### Order book

- **Bid Orders**: Orders where traders are looking to **buy** a cryptocurrency.
- **Ask Orders**: Orders where traders are looking to **sell** a cryptocurrency.
- **Price Levels**: Each order is placed at a specific price level. The difference is called a _spread_.
- **Quantity**: The amount of cryptocurrency that buyers want to buy and sellers want to sell.

> So basically when someone wants to sell, they place a bid.
> When someone wants to buy, they place a bid.
> If (when) they match, the trade is fulfilled.
> If they don't, the trade won't happen until the market levels to **both seller and buyer**.
> All of this goes in the order books.

- Types of orders
  - Market: At the moment with the highest price in the market
  - Limited: Sets up an expected value and can take time

When making _orders_:

| Maker                       | Taker               |
| --------------------------- | ------------------- |
| Until the price matches     | Automatic execution |
| Lower comission             | Higher comission    |
| Creates volume or liquidity | Consumes liquidity  |

#### Wallets

They're used to store a collection of **private keys**.
These keys are used to access bitcoin addresses and allow you to spend or sell btc.
The wallet can be protected through encryption with a password or other security methods.

| Wallet          | Access                        | Security                         |
| --------------- | ----------------------------- | -------------------------------- |
| Web Wallet      | Web platforms                 | The platform has control         |
| Desktop Wallet  | Personal computers            | Full control. Personal security  |
| Mobile Wallet   | Mobile devices                | Same as Web-based                |
| Hardware Wallet | Physical offline cold devices | Full control. Personal security. |
| Paper Wallet    | Physical documents            | Secure, but can be damaged       |

Some good practices:

- Backup
- Never share the private key
- 2FA
- Encrypt your wallet
- Not your keys, not your crypto
- Distribute the risk
