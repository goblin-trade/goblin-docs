# Introduction

Goblin is building the first on-chain limit order book on Arbitrum.

Orderbooks have remained an elusive dream on Ethereum. The EVM was unable to meet the high memory and computational requirements of a matching engine, necessating the invention of automated market makers that suffer from arbitrage and impermanent loss. Enter Arbitrum stylus, a generational update which brings Rust and WebAssembly smart contracts to Ethereum.

By leveraging Stylus, we have built a decentralized exchange free from liquidity pools that suffer from toxic flow, arbitrage or centralized points of failure. The dream of a decentralized Binance is at hand.

## Features of Goblin

- **On-chain limit orders:** Limit orders provide a user experience competitive to centralized exchanges. Currently traders are constrained to market price swaps on decentralized exchanges.

- **True decentralization:** Unlike 0x protocol and 1inch limit order protocol that rely on centralized servers, the Goblin is 100% smart contract based.

- **No impermanent loss and toxic arbitrage**: Goblin's market depth is built by active market makers, not passive liquidity pools that lose money to impermanent loss and arbitrage. Market makers earn profits from the bid-ask spread and active trading strategies.

- **Revenue positive**: Thanks to limit orders Goblin follows the revenue model of centralized exchanges. Goblin earns profits from a taker fee charged on take orders. Makers earn from the bid-ask spread, so unlike DEXes Goblin doesn't levy a swap fee to compensate LPs. Goblin has positive revenue unlike other DEXes whose main revenue comes from selling tokens.

- **Unlimited composability**:

  - An NFT marketplace that settles orders on Goblin. The #1 NFT marketplace OpenSea uses a centralized backend for limit orders.

  - Liquidity vaults like Raydium that allow passive LPs to participate in market making.

  - The spot orderbook can be extended to support perpetuals.

