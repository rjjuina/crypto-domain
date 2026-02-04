# Crypto Domain Landscape

## Chains
- Layer 1 (L1, 基础层) chains in `tables/chains.csv`: Bitcoin, Ethereum, BNB Chain, Solana, Cardano, Avalanche, Polygon, TRON, Cosmos, Polkadot, NEAR.
- Layer 2 (L2, 二层) rollups in `tables/chains.csv`: Arbitrum, Optimism, Base, zkSync Era, Starknet.
- Table fields include Category, KeyNotes, and snapshot references for ongoing updates.

## Trading
- Centralized exchange (CEX, 中心化交易所) list TBD in `tables/exchanges.csv`.
- Decentralized exchange (DEX, 去中心化交易所) spot AMMs in `tables/dex.csv`: Uniswap, Curve, Balancer, PancakeSwap, Raydium, Orca.
- Perpetuals (Perp, 永续合约) DEXs in `tables/dex.csv`: GMX, dYdX, Hyperliquid.

## Data/Analytics
- TODO(verify): Populate analytics and explorer tools | tables/security_tools.csv | Codex | due 2025-03-31

## Security/Compliance
- TODO(verify): Add KYT/monitoring and security tooling | tables/security_tools.csv | Codex | due 2025-03-31

## Middleware
- Oracle (Oracle, 预言机): Chainlink.
- Cross-chain messaging (Messaging, 跨链消息): Chainlink CCIP, LayerZero, Wormhole, Axelar.
- See `tables/middleware.csv` for security assumptions and official URLs.

## Stablecoins
- Fiat-backed stablecoins (Fiat-backed, 法币抵押): USDT, USDC.
- Crypto-collateralized stablecoins (Crypto-collateralized, 加密抵押): DAI, LUSD.
- Synthetic stablecoins (Synthetic, 合成): USDe, USDD.
- See `tables/stablecoins.csv` for snapshot sources.

## Wallets
- TODO(verify): Add software/hardware wallets | tables/wallets.csv | Codex | due 2025-03-31

## Custody
- TODO(verify): Add custody providers and models | tables/custody.csv | Codex | due 2025-03-31

## Multi-sig
- Smart contract (智能合约) multisig: Safe on Ethereum, Squads on Solana.
- Native permission (原生权限) multisig: TRON account permissions.
- Script-based (脚本) multisig: Bitcoin PSBT + Script references.
- See `tables/multisig.csv` for official docs links.

## Reading Path
- Start with glossary (Glossary, 术语表) terms for L1/L2, rollup, wallet, stablecoin.
- Read Chains and Trading sections, then review `tables/chains.csv` and `tables/dex.csv`.
- Review Middleware and Stablecoins tables to understand infrastructure and money primitives.
- Finish with custody and multisig sections as operational layers.
