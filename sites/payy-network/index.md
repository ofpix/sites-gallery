---
title: Payy
url: https://payy.network
tags: [fintech, web3, stablecoin, privacy, crypto-payments, infrastructure, product]
captured: 2026-07-18
---

# Payy — Private Stablecoin Payments Infrastructure

> Payy 为企业、开发者和全球平台提供**默认隐私的稳定币支付基础设施**——钱包、Visa 卡和自建的 Ethereum L2 网络（Payy Network），让稳定币在真实商业场景中可用。

---

## 设计风格

- **Minimalist fintech aesthetic** — 干净界面，信息层级清晰，深色/浅色双模式
- **Dashboard-first UX** — 首页直接展示实时钱包数据（余额、交易记录），让用户立刻理解产品功能
- **Product hierarchy 清晰** — 从产品（Wallet、Card、Cash Links）→ 平台（Network、Privacy Layer 等模块）→ 开发者工具，逐步深入
- **内容驱动** — 工程量级的技术博客（Noir circuits、ZK proofs、rollup architecture），用可读的叙述拆解复杂系统设计
- **隐私作为核心叙事** — 从文案（"Private by architecture. Familiar by design."）到 UI，隐私理念贯穿全线
- **新闻/博客时间线** — 用编号列表展示更新，搭配媒体引用和社交推文嵌入，增强可信度

## 产品亮点

| 模块 | 说明 |
|------|------|
| **Payy Wallet** | 非托管钱包，支持私密稳定币转账 |
| **Payy Card** | ZK 保护隐私的 Visa 卡，可直接用稳定币消费 |
| **Payy Network** | 默认隐私的 Ethereum L2，使用 Solid BFT 共识 + 递归 ZK 证明聚合 |
| **PrivacyBridge** | EVM 桥接层，用于资产进出隐私池 |
| **Privacy Vault** | 兼容钱包的私密数据存储与证明生成 |
| **Polylang** | TypeScript 风格的 ZK 智能合约语言 |

## 技术亮点

- **ZKP（Zero-Knowledge Proofs）** — 基于 Noir 框架，UTXO 模型（私密笔记），递归证明聚合实现扩容
- **Solid BFT** — 自建共识协议，优先 safety 而非 liveness
- **SMIRK Sparse Merkle Tree** — 同一棵树同时存储 commitments 和 nullifiers
- **Guardian Recovery** — 无种子短语的多因素钱包恢复方案
- **EIP-7702 Relayer** — 让 EOA 账户实现智能合约行为，无需迁移地址

## 关键数据

- 80,000+ KYC'd users & businesses
- $130M+ 年化交易量
- 10M+ 交易数
- 300ms 区块时间
- 种子轮 $6M（FirstMark Capital、DBA、Robot Ventures）

## 来源

[payy.network](https://payy.network) — 2026-07-18 抓取
