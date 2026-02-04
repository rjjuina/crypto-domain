---
title: Glossary
---

# Glossary

<table>
  <colgroup>
    <col style="width:20%">
    <col style="width:45%">
    <col style="width:25%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Term</th>
      <th>Chinese explanation</th>
      <th>Notes</th>
      <th>Source</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Blockchain</td>
      <td>区块链，按时间顺序链接的账本</td>
      <td>基础概念</td>
      <td><a href="https://ethereum.org/en/developers/docs/intro-to-ethereum/">Source</a></td>
    </tr>
    <tr>
      <td>Distributed Ledger (DLT)</td>
      <td>分布式账本，多方共同维护的数据记录</td>
      <td>术语基础</td>
      <td><a href="https://www.hyperledger.org/resources/knowledge-base/what-is-a-distributed-ledger">Source</a></td>
    </tr>
    <tr>
      <td>Consensus</td>
      <td>共识机制，网络对状态达成一致的规则</td>
      <td>协议基础</td>
      <td><a href="https://ethereum.org/en/developers/docs/consensus-mechanisms/">Source</a></td>
    </tr>
    <tr>
      <td>Proof of Work (PoW)</td>
      <td>工作量证明，通过计算竞争出块</td>
      <td>典型于 Bitcoin</td>
      <td><a href="https://bitcoin.org/en/how-it-works">Source</a></td>
    </tr>
    <tr>
      <td>Proof of Stake (PoS)</td>
      <td>权益证明，通过质押参与共识</td>
      <td>典型于 Ethereum</td>
      <td><a href="https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/">Source</a></td>
    </tr>
    <tr>
      <td>Validator</td>
      <td>验证者，参与出块与共识的节点</td>
      <td>PoS 角色</td>
      <td><a href="https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/">Source</a></td>
    </tr>
    <tr>
      <td>Full Node</td>
      <td>全节点，完整验证并存储链数据</td>
      <td>网络安全基石</td>
      <td><a href="https://bitcoin.org/en/full-node">Source</a></td>
    </tr>
    <tr>
      <td>Light Client</td>
      <td>轻客户端，只验证区块头或证明</td>
      <td>资源占用低</td>
      <td><a href="https://ethereum.org/en/developers/docs/nodes-and-clients/light-clients/">Source</a></td>
    </tr>
    <tr>
      <td>Smart Contract</td>
      <td>智能合约，链上可执行程序</td>
      <td>运行于 EVM</td>
      <td><a href="https://ethereum.org/en/developers/docs/smart-contracts/">Source</a></td>
    </tr>
    <tr>
      <td>Ethereum Virtual Machine (EVM)</td>
      <td>以太坊虚拟机，执行合约的运行时</td>
      <td>EVM 生态</td>
      <td><a href="https://ethereum.org/en/developers/docs/evm/">Source</a></td>
    </tr>
    <tr>
      <td>Account Model</td>
      <td>账户模型，账户余额与状态记录方式</td>
      <td>Ethereum 采用</td>
      <td><a href="https://ethereum.org/en/developers/docs/accounts/">Source</a></td>
    </tr>
    <tr>
      <td>UTXO</td>
      <td>未花费交易输出模型</td>
      <td>Bitcoin 采用</td>
      <td><a href="https://developer.bitcoin.org/devguide/transactions.html">Source</a></td>
    </tr>
    <tr>
      <td>Gas</td>
      <td>Gas 计价单位，用于衡量计算资源</td>
      <td>费用基础</td>
      <td><a href="https://ethereum.org/en/developers/docs/gas/">Source</a></td>
    </tr>
    <tr>
      <td>Transaction Fee</td>
      <td>交易费，提交交易的成本</td>
      <td>由 Gas 计价</td>
      <td><a href="https://ethereum.org/en/developers/docs/gas/">Source</a></td>
    </tr>
    <tr>
      <td>Layer 1 (L1)</td>
      <td>一层网络，基础共识区块链</td>
      <td>参考 chains.csv</td>
      <td><a href="https://ethereum.org/en/developers/docs/scaling/">Source</a></td>
    </tr>
    <tr>
      <td>Layer 2 (L2)</td>
      <td>二层网络，建立在 L1 之上的扩容</td>
      <td>常见为 Rollup</td>
      <td><a href="https://ethereum.org/en/developers/docs/scaling/layer-2-rollups/">Source</a></td>
    </tr>
    <tr>
      <td>Rollup</td>
      <td>汇总，L2 通过批量提交到 L1</td>
      <td>扩容技术</td>
      <td><a href="https://ethereum.org/en/developers/docs/scaling/rollups/">Source</a></td>
    </tr>
    <tr>
      <td>Optimistic Rollup</td>
      <td>乐观汇总，默认交易有效并可挑战</td>
      <td>L2 方案</td>
      <td><a href="https://ethereum.org/en/developers/docs/scaling/optimistic-rollups/">Source</a></td>
    </tr>
    <tr>
      <td>ZK Rollup</td>
      <td>零知识汇总，使用有效性证明</td>
      <td>L2 方案</td>
      <td><a href="https://ethereum.org/en/developers/docs/scaling/zk-rollups/">Source</a></td>
    </tr>
    <tr>
      <td>Sidechain</td>
      <td>侧链，与主链并行的独立链</td>
      <td>扩容方案</td>
      <td><a href="https://ethereum.org/en/developers/docs/scaling/sidechains/">Source</a></td>
    </tr>
    <tr>
      <td>Bridge</td>
      <td>跨链桥，在链之间转移资产</td>
      <td>风险点</td>
      <td><a href="https://ethereum.org/en/developers/docs/bridges/">Source</a></td>
    </tr>
    <tr>
      <td>Cross-chain Messaging</td>
      <td>跨链消息，在链间传递指令</td>
      <td>中间件能力</td>
      <td><a href="https://chain.link/ccip">Source</a></td>
    </tr>
    <tr>
      <td>Oracle</td>
      <td>预言机，为链上提供链下数据</td>
      <td>数据基础设施</td>
      <td><a href="https://chain.link/education/blockchain-oracles">Source</a></td>
    </tr>
    <tr>
      <td>AMM (Automated Market Maker)</td>
      <td>自动做市商，通过算法定价交易</td>
      <td>DEX 核心机制</td>
      <td><a href="https://docs.uniswap.org/">Source</a></td>
    </tr>
    <tr>
      <td>Liquidity Pool</td>
      <td>流动性池，用户资金汇集用于做市</td>
      <td>AMM 结构</td>
      <td><a href="https://docs.uniswap.org/">Source</a></td>
    </tr>
    <tr>
      <td>Orderbook</td>
      <td>订单簿，记录买卖挂单列表</td>
      <td>现货/衍生品</td>
      <td><a href="https://docs.dydx.exchange/">Source</a></td>
    </tr>
    <tr>
      <td>DEX (Decentralized Exchange)</td>
      <td>去中心化交易所，链上撮合或 AMM</td>
      <td>见 dex.csv</td>
      <td><a href="https://www.coinbase.com/learn/crypto-basics/what-is-a-dex">Source</a></td>
    </tr>
    <tr>
      <td>CEX (Centralized Exchange)</td>
      <td>中心化交易所，平台托管撮合</td>
      <td>见 exchanges.csv</td>
      <td><a href="https://www.coinbase.com/learn/crypto-basics/what-is-a-centralized-exchange">Source</a></td>
    </tr>
    <tr>
      <td>Perpetuals</td>
      <td>永续合约，期限不限的衍生品</td>
      <td>见 dex.csv</td>
      <td><a href="https://docs.dydx.exchange/">Source</a></td>
    </tr>
    <tr>
      <td>Stablecoin</td>
      <td>稳定币，锚定法币或资产的代币</td>
      <td>见 stablecoins.csv</td>
      <td><a href="https://www.coinbase.com/learn/crypto-basics/what-is-a-stablecoin">Source</a></td>
    </tr>
    <tr>
      <td>Fiat-backed Stablecoin</td>
      <td>法币抵押稳定币，储备支持</td>
      <td>例 USDT/USDC</td>
      <td><a href="https://www.circle.com/usdc">Source</a></td>
    </tr>
    <tr>
      <td>Crypto-collateralized Stablecoin</td>
      <td>加密抵押稳定币，超额抵押</td>
      <td>例 DAI</td>
      <td><a href="https://makerdao.com">Source</a></td>
    </tr>
    <tr>
      <td>Synthetic Stablecoin</td>
      <td>合成稳定币，通过衍生结构维持锚定</td>
      <td>例 USDe</td>
      <td><a href="https://ethena.fi">Source</a></td>
    </tr>
    <tr>
      <td>TVL (Total Value Locked)</td>
      <td>总锁仓量，协议锁定资产规模</td>
      <td>见 DefiLlama</td>
      <td><a href="https://defillama.com/">Source</a></td>
    </tr>
    <tr>
      <td>Market Cap</td>
      <td>市值，价格乘流通数量</td>
      <td>需标注快照</td>
      <td><a href="https://www.coingecko.com/en/glossary/market-capitalization">Source</a></td>
    </tr>
    <tr>
      <td>Liquidity</td>
      <td>流动性，资产可成交程度</td>
      <td>交易术语</td>
      <td><a href="https://www.coinbase.com/learn/crypto-basics/what-is-liquidity">Source</a></td>
    </tr>
    <tr>
      <td>Slippage</td>
      <td>滑点，成交价偏离预期</td>
      <td>交易术语</td>
      <td><a href="https://www.coinbase.com/learn/crypto-basics/what-is-slippage">Source</a></td>
    </tr>
    <tr>
      <td>Wallet</td>
      <td>钱包，管理私钥与签名的工具</td>
      <td>见 wallets.csv</td>
      <td><a href="https://ethereum.org/en/wallets/">Source</a></td>
    </tr>
    <tr>
      <td>Hardware Wallet</td>
      <td>硬件钱包，离线存储私钥设备</td>
      <td>安全性高</td>
      <td><a href="https://www.ledger.com/academy/hardware-wallets-what-you-need-to-know">Source</a></td>
    </tr>
    <tr>
      <td>Custody</td>
      <td>托管服务，机构保管资产</td>
      <td>见 custody.csv</td>
      <td><a href="https://www.coinbase.com/institutional/custody">Source</a></td>
    </tr>
    <tr>
      <td>MPC (Multi-Party Computation)</td>
      <td>多方安全计算，分片私钥签名</td>
      <td>常用于托管</td>
      <td><a href="https://www.fireblocks.com/what-is-mpc/">Source</a></td>
    </tr>
    <tr>
      <td>HSM (Hardware Security Module)</td>
      <td>硬件安全模块，安全存储密钥</td>
      <td>安全设备</td>
      <td><a href="https://csrc.nist.gov/publications/detail/fips/140/3/final">Source</a></td>
    </tr>
    <tr>
      <td>Multisig</td>
      <td>多重签名，需要多方授权</td>
      <td>见 multisig.csv</td>
      <td><a href="https://docs.safe.global">Source</a></td>
    </tr>
    <tr>
      <td>Private Key</td>
      <td>私钥，控制资产的密钥</td>
      <td>不可泄露</td>
      <td><a href="https://ethereum.org/en/developers/docs/accounts/">Source</a></td>
    </tr>
    <tr>
      <td>Public Key</td>
      <td>公钥，与私钥对应的公开密钥</td>
      <td>地址来源</td>
      <td><a href="https://ethereum.org/en/developers/docs/accounts/">Source</a></td>
    </tr>
    <tr>
      <td>Seed Phrase</td>
      <td>助记词，用于恢复钱包</td>
      <td>BIP-39 标准</td>
      <td><a href="https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki">Source</a></td>
    </tr>
    <tr>
      <td>Address</td>
      <td>地址，接收资产的标识</td>
      <td>账户标识</td>
      <td><a href="https://ethereum.org/en/developers/docs/accounts/">Source</a></td>
    </tr>
    <tr>
      <td>DAO (Decentralized Autonomous Organization)</td>
      <td>去中心化自治组织，链上治理组织</td>
      <td>治理结构</td>
      <td><a href="https://ethereum.org/en/dao/">Source</a></td>
    </tr>
    <tr>
      <td>Governance Token</td>
      <td>治理代币，用于投票与治理</td>
      <td>参与 DAO</td>
      <td><a href="https://www.coingecko.com/en/glossary/governance-token">Source</a></td>
    </tr>
    <tr>
      <td>Staking</td>
      <td>质押，锁定资产参与共识或收益</td>
      <td>PoS 机制</td>
      <td><a href="https://ethereum.org/en/staking/">Source</a></td>
    </tr>
    <tr>
      <td>Slashing</td>
      <td>罚没机制，对违规验证者扣罚质押</td>
      <td>PoS 惩罚机制</td>
      <td><a href="https://ethereum.org/en/staking/slashings/">Source</a></td>
    </tr>
    <tr>
      <td>Finality</td>
      <td>最终性，区块不可逆转的保证</td>
      <td>PoS 最终性</td>
      <td><a href="https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/finality/">Source</a></td>
    </tr>
    <tr>
      <td>Fork</td>
      <td>分叉，链协议规则或历史分歧</td>
      <td>协议升级</td>
      <td><a href="https://bitcoin.org/en/glossary/fork">Source</a></td>
    </tr>
    <tr>
      <td>Hard Fork</td>
      <td>硬分叉，产生不兼容规则的升级</td>
      <td>链升级</td>
      <td><a href="https://bitcoin.org/en/glossary/hard-fork">Source</a></td>
    </tr>
    <tr>
      <td>Soft Fork</td>
      <td>软分叉，向后兼容的规则升级</td>
      <td>协议升级</td>
      <td><a href="https://bitcoin.org/en/glossary/soft-fork">Source</a></td>
    </tr>
    <tr>
      <td>Token</td>
      <td>代币，链上发行的资产单位</td>
      <td>代币基础</td>
      <td><a href="https://ethereum.org/en/glossary/#token">Source</a></td>
    </tr>
    <tr>
      <td>Native Token</td>
      <td>原生代币，链自身发行的资产</td>
      <td>例 ETH</td>
      <td><a href="https://ethereum.org/en/glossary/#native-token">Source</a></td>
    </tr>
    <tr>
      <td>ERC-20</td>
      <td>ERC-20 标准，同质化代币接口</td>
      <td>代币标准</td>
      <td><a href="https://eips.ethereum.org/EIPS/eip-20">Source</a></td>
    </tr>
    <tr>
      <td>ERC-721</td>
      <td>ERC-721 标准，NFT 接口</td>
      <td>NFT 标准</td>
      <td><a href="https://eips.ethereum.org/EIPS/eip-721">Source</a></td>
    </tr>
    <tr>
      <td>ERC-1155</td>
      <td>ERC-1155 标准，多类型代币接口</td>
      <td>代币标准</td>
      <td><a href="https://eips.ethereum.org/EIPS/eip-1155">Source</a></td>
    </tr>
    <tr>
      <td>NFT (Non-Fungible Token)</td>
      <td>非同质化代币，唯一资产表示</td>
      <td>数字藏品</td>
      <td><a href="https://ethereum.org/en/nft/">Source</a></td>
    </tr>
    <tr>
      <td>Liquidity Provider (LP)</td>
      <td>流动性提供者，向池子提供资产</td>
      <td>AMM 角色</td>
      <td><a href="https://docs.uniswap.org/concepts/protocol/fees">Source</a></td>
    </tr>
    <tr>
      <td>Yield Farming</td>
      <td>收益耕作，通过提供流动性获取奖励</td>
      <td>DeFi 术语</td>
      <td><a href="https://www.coinbase.com/learn/crypto-basics/what-is-yield-farming">Source</a></td>
    </tr>
    <tr>
      <td>APY (Annual Percentage Yield)</td>
      <td>年化收益率，复利收益指标</td>
      <td>收益指标</td>
      <td><a href="https://www.investor.gov/introduction-investing/investing-basics/glossary/annual-percentage-yield">Source</a></td>
    </tr>
    <tr>
      <td>Collateral</td>
      <td>抵押物，用于借贷或稳定币支持</td>
      <td>抵押概念</td>
      <td><a href="https://makerdao.com/en/whitepaper/">Source</a></td>
    </tr>
    <tr>
      <td>Overcollateralization</td>
      <td>超额抵押，抵押物价值高于负债</td>
      <td>稳定币机制</td>
      <td><a href="https://makerdao.com/en/whitepaper/">Source</a></td>
    </tr>
    <tr>
      <td>Peg</td>
      <td>锚定，稳定币目标价格</td>
      <td>稳定币术语</td>
      <td><a href="https://www.coinbase.com/learn/crypto-basics/what-is-a-stablecoin">Source</a></td>
    </tr>
    <tr>
      <td>Depeg</td>
      <td>脱锚，价格偏离目标锚定</td>
      <td>风险术语</td>
      <td><a href="https://www.coinbase.com/learn/crypto-basics/what-is-a-stablecoin">Source</a></td>
    </tr>
    <tr>
      <td>Sequencer</td>
      <td>排序器，L2 排序并提交交易</td>
      <td>Rollup 组件</td>
      <td><a href="https://ethereum.org/en/developers/docs/scaling/optimistic-rollups/#sequencers">Source</a></td>
    </tr>
    <tr>
      <td>Fraud Proof</td>
      <td>争议证明，用于挑战无效状态</td>
      <td>乐观汇总</td>
      <td><a href="https://ethereum.org/en/developers/docs/scaling/optimistic-rollups/#fraud-proofs">Source</a></td>
    </tr>
    <tr>
      <td>Validity Proof</td>
      <td>有效性证明，证明批次状态正确</td>
      <td>ZK 汇总</td>
      <td><a href="https://ethereum.org/en/developers/docs/scaling/zk-rollups/#validity-proofs">Source</a></td>
    </tr>
    <tr>
      <td>Data Availability</td>
      <td>数据可用性，确保数据可被获取</td>
      <td>Rollup 要素</td>
      <td><a href="https://ethereum.org/en/developers/docs/data-availability/">Source</a></td>
    </tr>
    <tr>
      <td>MEV (Maximal Extractable Value)</td>
      <td>最大可提取价值，区块排序套利</td>
      <td>交易影响</td>
      <td><a href="https://ethereum.org/en/developers/docs/mev/">Source</a></td>
    </tr>
    <tr>
      <td>Gas Price</td>
      <td>Gas 价格，单位 Gas 成本</td>
      <td>费用参数</td>
      <td><a href="https://ethereum.org/en/developers/docs/gas/">Source</a></td>
    </tr>
    <tr>
      <td>Block Explorer</td>
      <td>区块浏览器，查询链上交易和区块</td>
      <td>见 Etherscan</td>
      <td><a href="https://ethereum.org/en/developers/docs/apis/#block-explorers">Source</a></td>
    </tr>
    <tr>
      <td>Relayer</td>
      <td>中继者，跨链消息或交易转发</td>
      <td>跨链组件</td>
      <td><a href="https://layerzero.network/">Source</a></td>
    </tr>
    <tr>
      <td>IBC (Inter-Blockchain Communication)</td>
      <td>跨链通信协议，Cosmos 生态</td>
      <td>IBC 协议</td>
      <td><a href="https://ibcprotocol.org/">Source</a></td>
    </tr>
    <tr>
      <td>Parachain</td>
      <td>平行链，接入 Polkadot 中继链</td>
      <td>Polkadot 架构</td>
      <td><a href="https://wiki.polkadot.network/docs/learn-parachains">Source</a></td>
    </tr>
    <tr>
      <td>Subnet</td>
      <td>子网，Avalanche 的验证者子集</td>
      <td>Avalanche 架构</td>
      <td><a href="https://docs.avax.network/learn/platform-overview#subnets">Source</a></td>
    </tr>
    <tr>
      <td>Custodial Wallet</td>
      <td>托管钱包，由平台保管私钥</td>
      <td>钱包类型</td>
      <td><a href="https://www.coinbase.com/learn/crypto-basics/what-is-a-custodial-wallet">Source</a></td>
    </tr>
    <tr>
      <td>Non-custodial Wallet</td>
      <td>非托管钱包，用户自管私钥</td>
      <td>钱包类型</td>
      <td><a href="https://www.coinbase.com/learn/crypto-basics/what-is-a-non-custodial-wallet">Source</a></td>
    </tr>
    <tr>
      <td>Hot Wallet</td>
      <td>热钱包，联网环境下的私钥存储</td>
      <td>风险较高</td>
      <td><a href="https://www.investopedia.com/terms/h/hot-wallet.asp">Source</a></td>
    </tr>
    <tr>
      <td>Cold Storage</td>
      <td>冷存储，离线保存私钥</td>
      <td>适合长期保管</td>
      <td><a href="https://www.coinbase.com/learn/crypto-basics/what-is-cold-storage">Source</a></td>
    </tr>
    <tr>
      <td>KYC (Know Your Customer)</td>
      <td>了解你的客户，身份核验流程</td>
      <td>合规基础</td>
      <td><a href="https://www.finra.org/investors/insights/know-your-customer">Source</a></td>
    </tr>
  </tbody>
</table>
