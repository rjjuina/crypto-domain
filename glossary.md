# Glossary

| Term | Chinese explanation | Notes | Source |
| --- | --- | --- | --- |
| Blockchain | 区块链，按时间顺序链接的账本 | 基础概念 | https://ethereum.org/en/developers/docs/intro-to-ethereum/ |
| Distributed Ledger (DLT) | 分布式账本，多方共同维护的数据记录 | 术语基础 | https://www.hyperledger.org/resources/knowledge-base/what-is-a-distributed-ledger |
| Consensus | 共识机制，网络对状态达成一致的规则 | 协议基础 | https://ethereum.org/en/developers/docs/consensus-mechanisms/ |
| Proof of Work (PoW) | 工作量证明，通过计算竞争出块 | 典型于 Bitcoin | https://bitcoin.org/en/how-it-works |
| Proof of Stake (PoS) | 权益证明，通过质押参与共识 | 典型于 Ethereum | https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/ |
| Validator | 验证者，参与出块与共识的节点 | PoS 角色 | https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/ |
| Full Node | 全节点，完整验证并存储链数据 | 网络安全基石 | https://bitcoin.org/en/full-node |
| Light Client | 轻客户端，只验证区块头或证明 | 资源占用低 | https://ethereum.org/en/developers/docs/nodes-and-clients/light-clients/ |
| Smart Contract | 智能合约，链上可执行程序 | 运行于 EVM | https://ethereum.org/en/developers/docs/smart-contracts/ |
| Ethereum Virtual Machine (EVM) | 以太坊虚拟机，执行合约的运行时 | EVM 生态 | https://ethereum.org/en/developers/docs/evm/ |
| Account Model | 账户模型，账户余额与状态记录方式 | Ethereum 采用 | https://ethereum.org/en/developers/docs/accounts/ |
| UTXO | 未花费交易输出模型 | Bitcoin 采用 | https://developer.bitcoin.org/devguide/transactions.html |
| Gas | Gas 计价单位，用于衡量计算资源 | 费用基础 | https://ethereum.org/en/developers/docs/gas/ |
| Transaction Fee | 交易费，提交交易的成本 | 由 Gas 计价 | https://ethereum.org/en/developers/docs/gas/ |
| Layer 1 (L1) | 一层网络，基础共识区块链 | 参考 chains.csv | https://ethereum.org/en/developers/docs/scaling/ |
| Layer 2 (L2) | 二层网络，建立在 L1 之上的扩容 | 常见为 Rollup | https://ethereum.org/en/developers/docs/scaling/layer-2-rollups/ |
| Rollup | 汇总，L2 通过批量提交到 L1 | 扩容技术 | https://ethereum.org/en/developers/docs/scaling/rollups/ |
| Optimistic Rollup | 乐观汇总，默认交易有效并可挑战 | L2 方案 | https://ethereum.org/en/developers/docs/scaling/optimistic-rollups/ |
| ZK Rollup | 零知识汇总，使用有效性证明 | L2 方案 | https://ethereum.org/en/developers/docs/scaling/zk-rollups/ |
| Sidechain | 侧链，与主链并行的独立链 | 扩容方案 | https://ethereum.org/en/developers/docs/scaling/sidechains/ |
| Bridge | 跨链桥，在链之间转移资产 | 风险点 | https://ethereum.org/en/developers/docs/bridges/ |
| Cross-chain Messaging | 跨链消息，在链间传递指令 | 中间件能力 | https://chain.link/ccip |
| Oracle | 预言机，为链上提供链下数据 | 数据基础设施 | https://chain.link/education/blockchain-oracles |
| AMM (Automated Market Maker) | 自动做市商，通过算法定价交易 | DEX 核心机制 | https://docs.uniswap.org/ |
| Liquidity Pool | 流动性池，用户资金汇集用于做市 | AMM 结构 | https://docs.uniswap.org/ |
| Orderbook | 订单簿，记录买卖挂单列表 | 现货/衍生品 | https://docs.dydx.exchange/ |
| DEX (Decentralized Exchange) | 去中心化交易所，链上撮合或 AMM | 见 dex.csv | https://www.coinbase.com/learn/crypto-basics/what-is-a-dex |
| CEX (Centralized Exchange) | 中心化交易所，平台托管撮合 | 见 exchanges.csv | https://www.coinbase.com/learn/crypto-basics/what-is-a-centralized-exchange |
| Perpetuals | 永续合约，期限不限的衍生品 | 见 dex.csv | https://docs.dydx.exchange/ |
| Stablecoin | 稳定币，锚定法币或资产的代币 | 见 stablecoins.csv | https://www.coinbase.com/learn/crypto-basics/what-is-a-stablecoin |
| Fiat-backed Stablecoin | 法币抵押稳定币，储备支持 | 例 USDT/USDC | https://www.circle.com/usdc |
| Crypto-collateralized Stablecoin | 加密抵押稳定币，超额抵押 | 例 DAI | https://makerdao.com |
| Synthetic Stablecoin | 合成稳定币，通过衍生结构维持锚定 | 例 USDe | https://ethena.fi |
| TVL (Total Value Locked) | 总锁仓量，协议锁定资产规模 | 见 DefiLlama | https://defillama.com/ |
| Market Cap | 市值，价格乘流通数量 | 需标注快照 | https://www.coingecko.com/en/glossary/market-capitalization |
| Liquidity | 流动性，资产可成交程度 | 交易术语 | https://www.coinbase.com/learn/crypto-basics/what-is-liquidity |
| Slippage | 滑点，成交价偏离预期 | 交易术语 | https://www.coinbase.com/learn/crypto-basics/what-is-slippage |
| Wallet | 钱包，管理私钥与签名的工具 | 见 wallets.csv | https://ethereum.org/en/wallets/ |
| Hardware Wallet | 硬件钱包，离线存储私钥设备 | 安全性高 | https://www.ledger.com/academy/hardware-wallets-what-you-need-to-know |
| Custody | 托管服务，机构保管资产 | 见 custody.csv | https://www.coinbase.com/institutional/custody |
| MPC (Multi-Party Computation) | 多方安全计算，分片私钥签名 | 常用于托管 | https://www.fireblocks.com/what-is-mpc/ |
| HSM (Hardware Security Module) | 硬件安全模块，安全存储密钥 | 安全设备 | https://csrc.nist.gov/publications/detail/fips/140/3/final |
| Multisig | 多重签名，需要多方授权 | 见 multisig.csv | https://docs.safe.global |
| Private Key | 私钥，控制资产的密钥 | 不可泄露 | https://ethereum.org/en/developers/docs/accounts/ |
| Public Key | 公钥，与私钥对应的公开密钥 | 地址来源 | https://ethereum.org/en/developers/docs/accounts/ |
| Seed Phrase | 助记词，用于恢复钱包 | BIP-39 标准 | https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki |
| Address | 地址，接收资产的标识 | 账户标识 | https://ethereum.org/en/developers/docs/accounts/ |
| DAO (Decentralized Autonomous Organization) | 去中心化自治组织，链上治理组织 | 治理结构 | https://ethereum.org/en/dao/ |
| Governance Token | 治理代币，用于投票与治理 | 参与 DAO | https://www.coingecko.com/en/glossary/governance-token |
| Staking | 质押，锁定资产参与共识或收益 | PoS 机制 | https://ethereum.org/en/staking/ |
| Slashing | 罚没机制，对违规验证者扣罚质押 | PoS 惩罚机制 | https://ethereum.org/en/staking/slashings/ |
| Finality | 最终性，区块不可逆转的保证 | PoS 最终性 | https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/finality/ |
| Fork | 分叉，链协议规则或历史分歧 | 协议升级 | https://bitcoin.org/en/glossary/fork |
| Hard Fork | 硬分叉，产生不兼容规则的升级 | 链升级 | https://bitcoin.org/en/glossary/hard-fork |
| Soft Fork | 软分叉，向后兼容的规则升级 | 协议升级 | https://bitcoin.org/en/glossary/soft-fork |
| Token | 代币，链上发行的资产单位 | 代币基础 | https://ethereum.org/en/glossary/#token |
| Native Token | 原生代币，链自身发行的资产 | 例 ETH | https://ethereum.org/en/glossary/#native-token |
| ERC-20 | ERC-20 标准，同质化代币接口 | 代币标准 | https://eips.ethereum.org/EIPS/eip-20 |
| ERC-721 | ERC-721 标准，NFT 接口 | NFT 标准 | https://eips.ethereum.org/EIPS/eip-721 |
| ERC-1155 | ERC-1155 标准，多类型代币接口 | 代币标准 | https://eips.ethereum.org/EIPS/eip-1155 |
| NFT (Non-Fungible Token) | 非同质化代币，唯一资产表示 | 数字藏品 | https://ethereum.org/en/nft/ |
| Liquidity Provider (LP) | 流动性提供者，向池子提供资产 | AMM 角色 | https://docs.uniswap.org/concepts/protocol/fees |
| Yield Farming | 收益耕作，通过提供流动性获取奖励 | DeFi 术语 | https://www.coinbase.com/learn/crypto-basics/what-is-yield-farming |
| APY (Annual Percentage Yield) | 年化收益率，复利收益指标 | 收益指标 | https://www.investor.gov/introduction-investing/investing-basics/glossary/annual-percentage-yield |
| Collateral | 抵押物，用于借贷或稳定币支持 | 抵押概念 | https://makerdao.com/en/whitepaper/ |
| Overcollateralization | 超额抵押，抵押物价值高于负债 | 稳定币机制 | https://makerdao.com/en/whitepaper/ |
| Peg | 锚定，稳定币目标价格 | 稳定币术语 | https://www.coinbase.com/learn/crypto-basics/what-is-a-stablecoin |
| Depeg | 脱锚，价格偏离目标锚定 | 风险术语 | https://www.coinbase.com/learn/crypto-basics/what-is-a-stablecoin |
| Sequencer | 排序器，L2 排序并提交交易 | Rollup 组件 | https://ethereum.org/en/developers/docs/scaling/optimistic-rollups/#sequencers |
| Fraud Proof | 争议证明，用于挑战无效状态 | 乐观汇总 | https://ethereum.org/en/developers/docs/scaling/optimistic-rollups/#fraud-proofs |
| Validity Proof | 有效性证明，证明批次状态正确 | ZK 汇总 | https://ethereum.org/en/developers/docs/scaling/zk-rollups/#validity-proofs |
| Data Availability | 数据可用性，确保数据可被获取 | Rollup 要素 | https://ethereum.org/en/developers/docs/data-availability/ |
| MEV (Maximal Extractable Value) | 最大可提取价值，区块排序套利 | 交易影响 | https://ethereum.org/en/developers/docs/mev/ |
| Gas Price | Gas 价格，单位 Gas 成本 | 费用参数 | https://ethereum.org/en/developers/docs/gas/ |
| Block Explorer | 区块浏览器，查询链上交易和区块 | 见 Etherscan | https://ethereum.org/en/developers/docs/data-availability/ |
| Relayer | 中继者，跨链消息或交易转发 | 跨链组件 | https://layerzero.network/ |
| IBC (Inter-Blockchain Communication) | 跨链通信协议，Cosmos 生态 | IBC 协议 | https://ibcprotocol.org/ |
| Parachain | 平行链，接入 Polkadot 中继链 | Polkadot 架构 | https://wiki.polkadot.network/docs/learn-parachains |
| Subnet | 子网，Avalanche 的验证者子集 | Avalanche 架构 | https://docs.avax.network/learn/platform-overview#subnets |
| Custodial Wallet | 托管钱包，由平台保管私钥 | 钱包类型 | https://www.coinbase.com/learn/crypto-basics/what-is-a-custodial-wallet |
| Non-custodial Wallet | 非托管钱包，用户自管私钥 | 钱包类型 | https://www.coinbase.com/learn/crypto-basics/what-is-a-non-custodial-wallet |
| Hot Wallet | 热钱包，联网环境下的私钥存储 | 风险较高 | https://www.investopedia.com/terms/h/hot-wallet.asp |
| Cold Storage | 冷存储，离线保存私钥 | 适合长期保管 | https://www.coinbase.com/learn/crypto-basics/what-is-cold-storage |
| KYC (Know Your Customer) | 了解你的客户，身份核验流程 | 合规基础 | https://www.finra.org/investors/insights/know-your-customer |
