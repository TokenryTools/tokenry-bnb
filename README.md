# Tokenry on BNB Chain

No-code token tools built on **BNB Smart Chain (BSC)** and compatible with other EVM networks: create a BEP-20 token, open its PancakeSwap or Uniswap pool, airdrop it and manage it from your own wallet.

Live app: [tokenry.tools/binance](https://tokenry.tools/binance)

## Technology Stack

- **Blockchain**: BNB Smart Chain (primary) + EVM-compatible chains
- **Smart Contracts**: Solidity 0.8.38, OpenZeppelin libraries
- **Frontend**: Next.js + viem + wagmi
- **Development**: Hardhat (mainnet-fork tests against BSC)

## Supported Networks

- **BNB Smart Chain Mainnet** (Chain ID: 56)
- **BNB Smart Chain Testnet** (Chain ID: 97)

The same tools also run on Ethereum, Base, Arbitrum, Polygon, Optimism, Avalanche, Unichain, Robinhood Chain, Ink, Arc, Cronos and Elysium.

## Contract Addresses

All contracts are verified on BscScan.

| Contract | BNB Mainnet (56) | BNB Testnet (97) |
| --- | --- | --- |
| TokenFactory (BEP-20 token creator) | [0xD1f1DA33b2934981aDe31f6AD525f0D1646114F5](https://bscscan.com/address/0xD1f1DA33b2934981aDe31f6AD525f0D1646114F5#code) | [0x4F64D82Fd00180686f92Cdad1f1Cb4276f551c38](https://testnet.bscscan.com/address/0x4F64D82Fd00180686f92Cdad1f1Cb4276f551c38#code) |
| TokenMultiSender (airdrops) | [0xC1CEbE1dE66Efdd0b415e5fbb5462469BB1b86ba](https://bscscan.com/address/0xC1CEbE1dE66Efdd0b415e5fbb5462469BB1b86ba#code) | [0x6586c20d217d7d1BfB8d56241D1F3FB60df8f2fE](https://testnet.bscscan.com/address/0x6586c20d217d7d1BfB8d56241D1F3FB60df8f2fE#code) |
| PoolLauncher (pool creation + first buy) | [0x157E85E1527b2d1c1188Cad9101Df5644beaf396](https://bscscan.com/address/0x157E85E1527b2d1c1188Cad9101Df5644beaf396#code) | [0x3a168bb619f9113E3A98A7DF0e40b66674FE7d5a](https://testnet.bscscan.com/address/0x3a168bb619f9113E3A98A7DF0e40b66674FE7d5a#code) |
| LiquidityManager (add / remove liquidity, claim fees) | [0x828cb0424f7f8FAb1DB1411e5B12b8fC78AC286f](https://bscscan.com/address/0x828cb0424f7f8FAb1DB1411e5B12b8fC78AC286f#code) | [0xdbc5307fd635063733CFedb651E6ffBB00eC2EAC](https://testnet.bscscan.com/address/0xdbc5307fd635063733CFedb651E6ffBB00eC2EAC#code) |

Network settings and addresses in machine-readable form: [`bnbconfig.json`](bnbconfig.json).

## Features

- **BEP-20 Token Creator**: deploy a BEP-20 token on BNB Smart Chain with optional tax, limits, minting and ownership settings; Tokenry submits its source for verification on BscScan after deploy.
- **Multisender**: airdrop BNB or any BEP-20 token to thousands of wallets from a list or CSV.
- **Liquidity Pool Creator**: open a PancakeSwap or Uniswap pool on BNB Smart Chain, with an optional first buy in the same transaction.
- **Add / Remove Liquidity and Claim Fees**: manage PancakeSwap and Uniswap positions on BNB Smart Chain.
- **Token Manager**: change the settings of a BEP-20 token made with Tokenry.
- **Non-custodial**: every action is a transaction you review and sign in your own wallet; fees are shown in BNB before signing.

## Links

- Website: [tokenry.tools](https://tokenry.tools)
- BNB Chain tools: [tokenry.tools/binance](https://tokenry.tools/binance)
- X: [@tokenryTools](https://x.com/tokenryTools)
- Support: [support@tokenry.tools](mailto:support@tokenry.tools)
