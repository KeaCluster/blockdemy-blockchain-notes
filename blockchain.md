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
      - [Wallets](#wallets)
  - [Part 4](#part-4)
    - [Blocks](#blocks)
    - [Nodes](#nodes)
    - [Encryption](#encryption)
      - [Encryption concepts](#encryption-concepts)
      - [Types of algorithms used in encryption](#types-of-algorithms-used-in-encryption)
  - [Part 5](#part-5)
    - [Asymmetric cryptography](#asymmetric-cryptography)
    - [Consensus protocol](#consensus-protocol)
      - [Types of consensus protocols](#types-of-consensus-protocols)
  - [Part 6](#part-6)
    - [Smart contracts](#smart-contracts)
    - [Ethereum](#ethereum)
      - [Ether](#ether)
      - [Gas](#gas)
  - [Part 7](#part-7)
    - [DApps](#dapps)
    - [Tokens](#tokens)
      - [Tokens and Coins](#tokens-and-coins)
      - [Utility Token or Security](#utility-token-or-security)
      - [CBDC](#cbdc)
  - [Part 8](#part-8)
    - [DeFi](#defi)
      - [DeFi concepts](#defi-concepts)
      - [Differences CeFi and DeFi](#differences-cefi-and-defi)

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

## Part 4

### Blocks

They're units if digital ledger tech. Digital containers of data.
They contain transaction records. They're linked through `hash` crypto techniques.
i.e. blocks.

Basically a `.json`.
They contain a header and a body.

- Header contains info such as
  - Version of the block
  - The hash of the prev block
  - The Merkle root
  - A timestamp
  - A target
  - A nonce
- The body contains
  - Transaction data. Details of the transfer between users.

To check blocks' info: [BlockChair](https://www.blockchair.com)

The fact that a block is interconnected with all previous,
and in a way with all to follow, makes them virtually impossible to modify.
This gives blockchain blocks immutability.

### Nodes

Considered crucial components of the network's functionality and integrity.
They're individual points of communication within the blockchain network.
They possess a unique `IP`.
Some are heavy, containing full copy of the blockchain ledger.
Others are light, containing essential information required for verification.

Their role is to **validate and relay transactions**.
This ensures security and reliability as they're decentralized.
Nodes form the backbone of blockchain networks,
ensuring security, reliability and continuous operation.

### Encryption

#### Encryption concepts

What for?

- Confidential
  - Secure the contents
- Auth
  - Verify the origin
- Integrity
  - Prove the content hasn't changed
- Non-deniable
  - Avoid the receiver to deny the message.

| **Plaintext Characteristics**                                                                                                | **Encryption Algorithm**                                                                                                                              | **Encrypted Text Characteristics**                                                                                                         |
| ---------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| **Simple text format**: Readable and understandable by humans. Contains no special formatting.                               | **AES (Advanced Encryption Standard)**: A symmetric key algorithm widely used for secure data encryption.                                             | **Complex alphanumeric string**: Looks like random data, making it impossible to decipher without the correct key.                         |
| **Structured data**: Can include formatted documents, such as spreadsheets or HTML files, containing both text and metadata. | **RSA (Rivest-Shamir-Adleman)**: An asymmetric algorithm that uses a pair of keys, making it suitable for secure data transmission over the internet. | **Scrambled format**: Alters the structured data in a way that the original structure is not discernable without decryption.               |
| **Large data volumes**: Bulk data that requires efficient encryption processing to maintain performance.                     | **Blowfish**: A symmetric block cipher designed for speed and effectiveness, especially in hardware implementations.                                  | **Segmented and uniform blocks**: Encrypted data is divided into uniform blocks, ensuring efficient and secure handling of large datasets. |

| |

#### Types of algorithms used in encryption

There are two:

- Unidirectional
  - HASH
- Bidirectional
  - Symmetric cypher
  - Asymmetric cypher

## Part 5

### Asymmetric cryptography

Also known as _public key cryptography_,
is a traditional foundational element of blockchain tech.
It ensures security and integrity of the transaction being made on networks such as BTC and ETH.
This system employs two keys:

- Private key: Kept in secret by the owner
  - Used to validate signatures and encrypt data.
- Public key: Shared publicly through the network.
  - Used to sign messages and decrypt data.

In blockchain applications, this type of encryption is used for transactions.
It helps maintain privacy of the transaction without revealing identities.
Transactions and identities are instead verified through digital signatures.
A User signs a transaction with their **private key**,
and the network valdiates this signature with the public key.
Digital signatures are analogous to real-world signatures.

### Consensus protocol

How can we make sure the network is free of censorship?

This basically refers to the set of rules and mechanisms that allow all nodes in the network to agree on the validity of transactions and the current state of the distributed ledger.
It ensures _security, consistency, and decentralization._
An agreement like this is crucial for a trustless system where no single node owns and/or controls the entire network.
Every participant has an equal say over the validation process.

#### Types of consensus protocols

- **Proof of Work (PoW)**
  - Involves nodes competing to solve complex mathematical puzzles
  - The first that solves them is rewarded by a block of transactions
  - Used in BTC
- **Proof of Stake (PoS)**
  - Selects validators based on the number of coins they hold and are willing to _stake_
  - More energy-efficient compared to PoW
- **Proof of Authority (PoA)**
  - Suited for private blockchains
  - Validators stake their reputation instead of tokens.
- **Proof of Coverage (PoC)**
  - Verify network coverage through radio waves.

## Part 6

### Smart contracts

Basically a computer program that run **on** a blockchain.
They execute automatically predefined actions when certain conditions are met.
They're stored digitally on a blockchain and make certain processes faster,
reducing the possibility of manual errors or fraud due to their lack of intermediaries.

Basically a conditional-focused program.
Smart contracts to execute on a blockchain can be written and run with programs like [Solidity](https://soliditylang.org/).
Every smart contract on a blockchain is visible for everyone else.
Once a smart contract is on the blockchain, they can't be edited or modified.
Some characteristics are:

- Free of censorship
- Decentralized
- Runs 24/7
- Native to their cryptocurrency
- Immutable

### Ethereum

- An internet where currency and payments are _integrated_
- An internet where users can own their data and applications
- An internet where everyone has access to an open financial system
- An internet built on top of a neutral and open infrastructure without central ownership

#### Ether

Ether is the actual crypto coin of the etherium ecosystem

- Its an economic incentive to verify and execute transactions
- Any participant that makes a transaction request must offer a certain ammount of ether to the network as reward
- This reward is given to whomever verifies the transaction, executes it and compromises it inside the blockchain and into the network

#### Gas

This is the unit that measures the amount of computing effort required to process transactions inside the Ethereum network.
Given each transaction requires computing resources,
each transaction charges a rate.

Gas refers to the rate required to make a successful transaction inside Ethereum.
Gas fees are calculated based on the complexity of the transaction or contract executed.
The total gas fee is calculated by:

- $gasUnits \times gasPricePerUnit = gasFee

## Part 7

### DApps

Decentralized applications that run on a _decentralized network_.
They blend smart contracts and user interfaces.
They operate on blockchain peer-to-peer networks which allow them to be free from single-entity control.
Ethereum has been one of the main providers of these applications due to its smart contract capabilities.
This makes it easy for developers to create DApps from games to financial tools.

### Tokens

Digital representations of any asset or service.
Kind of a cryptocoin of a decentralized app.
They adhere to specific standards

| Standard | Type         | Features                                                                                                                                  | Common Use Cases                         |
| -------- | ------------ | ----------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| ERC-20   | Fungible     | Standard interface for tokens, functions for transferring tokens, getting balances, and allowing others to transfer tokens on your behalf | Digital currencies, ICO tokens           |
| ERC-223  | Fungible     | Improves on ERC-20 to prevent token loss in contracts, more efficient transactions by reducing the steps needed for transfers             | Safer and more efficient token transfers |
| ERC-721  | Non-Fungible | Unique identifiers for each token, making them irreplaceable, enables ownership and transfer of unique digital items                      | Digital collectibles, unique assets      |
| ERC-777  | Fungible     | Advanced features over ERC-20, introduces "operators" to manage tokens, backwards compatible with ERC-20                                  | Advanced token economics, DApps          |
| ERC-1155 | Multi-Token  | A single contract for both fungible and non-fungible tokens, efficient batch transferring, reducing transaction and storage costs         | Gaming, NFT platforms                    |

#### Tokens and Coins

- Coins
  - Operate on their own independent network
  - They primarily serve as a medium of exchange similar to traditional fiat currencies
  - BTC, ETH, DOGE
- Tokens
  - They exist on previously predefined blockchain networks
  - Often associated with specific applications or projects
  - They're generated through smart contracts making the process accessible.
  - BAT, UNI.

#### Utility Token or Security

**Utility tokens** are designed to allow access to a blockchain-based service or app.
They can be used to purchase services or goods, access functionalities, etc.
Utility tokens are often distributed through **Initial Coin Offerings (ICOs)**,
They're fundraising methods for projects to generate interest in their platforms.

**Security tokens** are digital representations of ownership in real-world assets.
They can represent stocks, bonds or real state.
They're subject to federal sec regulations.
Holding a token might grant you rights similar to trad securities,
such as dividends, profit shares, voting rights.

They offer the benefit of increased liquidity, global access,
and fractional ownership of high-value assets.

#### CBDC

Central Bank Digital Currencies are digital forms of _fiat money_.
They're issued and regulated by a country's central bank.
Unlike cryptocurrencies, which are decentralized and operate outside authorities,
CBDCs are centralized and part of the national monetary policy.
They're designed to represent a country's fiat currency in digital form.
This makes transactions more efficient and promote financial inclusion.

CBDCs are built on several tech frameworks including distributed ledger technology (DLT).
DLT is similar to blockchain, however it involves permissioned blockchain,
where access is controlled by a central entity, such as a central bank.

## Part 8

### DeFi

Decentralized Finance refers to an ecosystem of financial apps built on blockchain.
Primarily Ethereum and blockchain networks.
It aims to recreate traditional financial systems with cryptocurrencies that operate without central authorities or intermediaries.
DeFi apps have several functions including lending, borrowing, and trading through smart contracts.
This promotes open source financial systems where anyone with an internet connection can participate.

#### DeFi concepts

- Pool: Funds locked in a smart contract for trading or liquidity in DeFi apps.
- AMM (Automated Market Maker): Decentralized protocol using formulas to price
  assets based on liquidity pools instead of order books.
- Farm: Known as yield farming, involving staking or lending crypto to earn
  rewards.
- Swap: Direct exchange of one cryptocurrency for another through smart contracts.
- Dex (Decentralized Exchange): Operates without central authority, allowing direct
  trades from user wallets.
- Staking: Locking cryptocurrencies to receive rewards and support blockchain
  operations.
- Stablecoins: Cryptocurrencies designed to minimize price volatility, usually
  pegged to stable assets.
- Lending: Platforms that allow crypto lending in return for interest, managed by
  smart contracts.
- Borrowing: Taking loans in a decentralized manner on DeFi platforms, typically
  requiring collateral.
- Oracles: Agents providing external data to blockchains to enable smart contracts
  to react to real-world events.
- DAOs (Decentralized Autonomous Organizations): Organizations run autonomously
  without central leadership, governed by code and community votes.
- ICOs (Initial Coin Offerings): Fundraising mechanisms where new cryptocurrencies
  are sold to raise project capital.

#### Differences CeFi and DeFi

| **Aspect**           | **Centralized Finance (CeFi)**                                                                                 | **Decentralized Finance (DeFi)**                                                                            |
| -------------------- | -------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **Control**          | Managed by centralized entities (e.g., banks, financial institutions).                                         | Operates without a central authority; uses smart contracts on blockchain platforms like Ethereum.           |
| **Custody**          | Users entrust their funds to the institution. The institution holds and manages the funds.                     | Users retain control over their funds through personal wallets and private keys.                            |
| **Regulation**       | Heavily regulated by governmental and financial bodies. Compliance is required for operation.                  | Mostly operates in a regulatory grey area; less oversight, which can lead to both innovation and risk.      |
| **Transparency**     | Limited transparency. Users do not have insight into the institution's internal processes or financial health. | High transparency. All transactions are recorded on a public ledger and are verifiable.                     |
| **Intermediaries**   | Requires intermediaries for transactions, such as banks or payment processors.                                 | Eliminates intermediaries using blockchain technology; direct peer-to-peer transactions.                    |
| **Accessibility**    | Requires going through KYC (Know Your Customer) processes. Accessibility can be limited based on geography.    | Generally accessible to anyone with an internet connection; no KYC required for most platforms.             |
| **Interest Rates**   | Interest rates are set by the institutions based on various economic factors.                                  | Interest rates are determined by smart contracts and can be more dynamic, reflecting supply and demand.     |
| **Innovation Speed** | Innovation can be slower due to regulatory and operational constraints.                                        | Rapid innovation is possible and common due to the open-source and permissionless nature of the technology. |
| **User Experience**  | Often more user-friendly with customer support and established interfaces.                                     | Can be less intuitive for new users; typically requires more technical knowledge to navigate safely.        |
| **Risk**             | Risks include institutional failure, mismanagement, and fraud. Regulatory protection is available.             | Risks include smart contract vulnerabilities, hacking incidents, and high volatility. Limited protection.   |
