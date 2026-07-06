# The Rise of Robinhood Chain: Tokenized Stocks, Perps, and 27M Users | Johann Kerbrat

> Bankless EP · 2026-07-06 · 30:27 · 嘉宾：Johann Kerbrat（Robinhood Crypto VP/GM）

## 📋 基础信息

| 字段 | 内容 |
|------|------|
| **期号** | — |
| **标题** | The Rise of Robinhood Chain: Tokenized Stocks, Perps, and 27M Users |
| **嘉宾** | Johann Kerbrat（Robinhood Crypto VP / GM） |
| **发布日期** | 2026-07-06 |
| **时长** | 30:27 |
| **链接** | https://www.bankless.com/podcast/the-rise-of-robinhood-chain-tokenized-stocks-perps-and-27m-users |
| **关键词** | Robinhood Chain, RWA, tokenized stocks, perps, Arbitrum Orbit, Morpho, USDG, LiDAR |

---

## 1️⃣ 核心论点

> Robinhood Chain 是传统金融迁移到以太坊轨道的明确信号。

**论证链条：**

1. **代币化股票** → 1:1 锚定，带股息和公司治理权，可在 Uniswap 上 24/7 交易，自由跨链转移（Robinhood Chain ↔ Ethereum L1）
2. **USDG 稳定币 + Morpho** → 主应用内嵌自托管智能钱包，7% 收益，Paxos 发行的 USDG 参与 Global Dollar Network，收益分享机制
3. **永续合约扩展** → 受监管平台（Bitstamp/MiFID）提供非加密资产 perps（黄金/白银/QQQ），Robinhood Wallet 通过 LiDAR 提供加密 perps（20-50x 杠杆）
4. **链架构** → Arbitrum Orbit chain，Stylus 支持多语言开发，低 gas，低延迟

## 2️⃣ 关键洞察

| 领域 | 要点 |
|------|------|
| **代币化股票** | 自由转移，无需 ACATS 流程（传统跨券商转移需数天/数周），可作抵押品 |
| **KYC 问题** | 代币化股票转移是 **permissionless** 的，接收方无需 Robinhood KYC |
| **用户增长策略** | 不是跟 Phantom/MetaMask 抢 crypto native 用户，而是瞄准 **从未上链的数十亿人** |
| **钱包定位** | 简化 UX（Apple Pay/Google Pay 入金，滑杆调杠杆），降低 99% 人口的使用门槛 |
| **Robinhood Chain 分发优势** | 开发者反向涌入——不是链找开发者，而是开发者找 2700 万用户的分发能力 |

## 3️⃣ 暂停时刻

> 听到 David 问 "Robinhood Wallet vs 主应用长期平衡" 时暂停

**我的推演：** 传统券商和 DeFi 最终会融合——前端是 Robinhood 品牌，后端全部跑在链上。监管是唯一的障碍。

**差距：** Johann 明确表示"传统系统会逐步被区块链技术替代"，而且已经在用 Morpho 的智能钱包做实验——**这不是"要不要"，而是"等监管"**。

## 4️⃣ 金句 / 洞见

- 上线不到 24 小时，Robinhood Chain 已有 **100 万笔交易**
- LiDAR 承诺 **1100 万美元 LEAD 代币**作为交易激励（8月1日启动），Robinhood Wallet 交易获双倍积分
- "Blockchain was made by engineer for engineer. We are losing 99% of the population." —— Johann

## 5️⃣ 批判思考

- 代币化股票的 mint/ redeem 仍需通过 Robinhood——**这不是完全去中心化的 RWA**
- 7% 的 USDG 收益率能否持续？Johann 说"跟合作伙伴确保稳定"，但 Morpho 的 DeFi 收益天然波动
- 100 万笔交易有多少是真实的用户需求，多少是空投猎人和 bot？链刚上线，需观察

## 6️⃣ 行动计划

- [ ] 研究 Robinhood Chain 的区块浏览器和生态项目
- [ ] 对比 Ondo Finance 的 RWA 方案（同期 Bankless 另一期有 Ian De Bode）
- [ ] 跟踪 USDG vs USDC 的竞争格局（Global Dollar Network 模式）
- [ ] 关注 Robinhood 的 S1 财报中新增的链收入项目

## 7️⃣ 框架抽取

```
框架名称：传统金融上链的三层渗透模型
适用范围：分析任何 TradFi 机构的加密战略
原始上下文：Bankless Robinhood Chain EP

框架结构：
Layer 1 - 前端集成（主应用嵌入 DeFi 产品，如 Morpho 收益）
Layer 2 - 链上基建（自建 L2，托管原生资产）
Layer 3 - 生态开放（资产可跨链、可组合、可编程）
```

---

## 📝 逐字稿全文

```
David: [0:03] On Wednesday of last week, Robinhood held their "The World is Flat" event, where they launched the Robinhood chain, along with a huge collection of ecosystem partners and integrations. The name is a tip of the hat to the fact that Robinhood wants to democratize access, flatten the world to have access to financial products using blockchain technology. Tokenized stocks issued by Robinhood are freely and permissionlessly transferable around the Robinhood chain and on and off to the Ethereum layer one and its layer twos. Morpho is integrated into the main Robinhood app, offering 27 million Robinhood customers 7% yield on USDG stablecoin deposits in a non-custodial section of the main app. They've expanded PERP offerings to EU and Canadian customers, and have a full feature-complete integration of LiDAR (the ZK L2 PERP DEX on Ethereum) inside the Robinhood wallet.

Johann: The vision was to show how using blockchain and crypto, we can actually remove all the inequalities in the world and make persons anywhere in the world able to access U.S. Stocks, perps, and all these products. We showed 15 products at the event. The chain is not even live for 24 hours and we already saw a million transactions.

[Key detail: Tokenized stocks are 1:1 backed, pay dividends, support corporate actions. If anything happens to Robinhood, the customer's position is secure. Users can send stocks to another wallet — compared to traditional ACATS transfer which takes days or weeks.]

[On USDG + Morpho: Robinhood creates a self-custody smart wallet for each user within the main app, connected to Morpho vaults on Robinhood Chain. The 7% yield is sustainable because Robinhood's massive distribution attracts market makers who create new pools. USDG is part of the Global Dollar Network where treasury yield is shared with network members.]

[On perps: Two tracks — (1) Regulated perps via Bitstamp (MiFID license) for EU customers, offering non-crypto assets like gold, silver, QQQ, WTI with up to 10x leverage. (2) DeFi perps via LiDAR integration in Robinhood Wallet, available in 100+ countries, up to 20-50x leverage. LiDAR committed $11M in LEAD tokens for trading incentives starting August 1.]

[On chain architecture: Robinhood Chain is an Arbitrum Orbit chain. Chose Arbitrum for Stylus (multi-language support including Rust), low gas fees, low latency, EVM compatibility, and Ethereum-level security.]

[On long-term vision: The two worlds (traditional Robinhood app and Robinhood Wallet) will converge. "Traditional systems are going to slowly replace their technology with blockchain technology. It's just faster, fraud-proof, verifiable, decentralized, fractionalization by default."]

[On target audience: Building for non-crypto natives, not competing with Phantom/MetaMask. "Blockchain was made by engineer for engineer. We are losing 99% of the population." Robinhood Wallet simplifies everything — Apple Pay/Google Pay to fund, slider for leverage, no 20-step approval processes.]

[On developer ecosystem: Unlike typical chains that chase developers, Robinhood Chain has the opposite situation — developers are excited about the 27M user distribution. "People are really excited about having the distribution coming from Robinhood and having all these customers that are not necessarily crypto first."]
```

---

*笔记使用 C（反向演练）+ D（知识库沉淀）双路线完成*
