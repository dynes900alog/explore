# PURR（Hyperliquid Strategies）投资分析

> 标的：Hyperliquid Strategies Inc.（NASDAQ: `PURR`）  
> 报告日期：2026-08-30  
> 最新业绩：截至 2026-06-30 的 FY2026 年报，发布于 2026-08-27  
> 价格口径：PURR 使用 2026-08-28 美股收盘价约 $11.61；HYPE 使用 2026-08-30 约 $79.82。由于周末 HYPE 继续交易而 PURR 停牌，这两个价格并非同步可成交价格，周一开盘可能跳空。  
> 结论置信度：中。财报和官方 dashboard 输入可核查，但 HYPE 价格、稀释股数和 NAV 会持续变化。

## 一句话结论

PURR 不是传统意义上的盈利成长公司，而是一个**持有、质押并运营 HYPE 资产的美股上市包装器**。其投资结果主要由 `HYPE 价格 × 每股 HYPE 数量 × PURR 的 NAV 溢价/折价` 决定。FY2026 的 $305.5M 净利润主要来自未实现币价上涨，不能按普通 PE 估值。按公司最新 dashboard 输入和税后稀释口径估算，$11.61 对应约 **1.20× 税后 NAV**，当前更适合观察或极小试验仓，而不是把“盈利大增”理解为经营利润爆发。

## 公司是什么

Hyperliquid Strategies 的目标是为美国和机构投资者提供 HYPE 敞口。核心模式：

1. 发行 PURR 股票募集美元。
2. 使用资金购买 HYPE。
3. 质押 HYPE，并通过 `Hyperliquid Strategies x Unit` validator 获得收益和佣金。
4. 在 PURR 明显低于 NAV 时回购股票。
5. 通过美国上市公司结构提供无需个人管理链上钱包的 HYPE 敞口。

公司已退出原 Sonnet BioTherapeutics 的生物科技业务，旧业务相关 IPR&D 在 FY2026 一次性减记 $35.6M。

**本质判断**：PURR 的“主营资产”是 HYPE，validator 和资本配置是附加层。购买 PURR 等于同时承担 HYPE 风险、公司治理、税务、稀释、托管和股市交易时段风险。

公司在 2025 年 12 月才完成向 HYPE treasury 的转型，因此 FY2026 是混合了旧业务、合并会计和约 7 个月新策略的过渡年度，不是一个可以直接外推的完整正常年份。

## FY2026 最新业绩

来源：[公司 FY2026 业绩公告，2026-08-27](https://www.prnewswire.com/news-releases/hyperliquid-strategies-inc-reports-financial-results-for-the-fiscal-year-ended-june-30-2026-302861372.html)

### 资产负债表

| 指标 | 2026-06-30 | 解读 |
|------|------------|------|
| HYPE 持仓 | 29.28M | 期后更新为约 29.3M |
| HYPE 账面价值 | $1,904.1M | 按 $65.04/HYPE |
| 现金及类似资产 | $149.9M | 包括 $12.0M USDC |
| 总资产 | $2,060.0M | 绝大部分是 HYPE |
| 股东权益 | $1,872.9M | 已扣除负债和递延税影响 |
| 债务 | $0 | 暂无财务杠杆 |

截至 2026-08-19，公司更新：

- HYPE 约 29.3M。
- 剩余现金约 $132.6M，其中 USDC $12.0M。
- 从成立到该日共投入 $773.4M，以平均 $46.77 买入约 16.5M HYPE。
- 使用 $27.8M，以平均 $4.80 回购约 5.8M PURR。
- 通过 committed equity facility 募集 $646.6M，平均发行价 $8.70。

### 损益表

| 指标 | FY2026 | 收益质量 |
|------|--------|----------|
| Staking revenue 和 validator commissions | $9.5M | 相对可重复，但随 HYPE、质押率和协议规则变化 |
| 利息收入 | $2.7M | 可重复但不是核心增长引擎 |
| SG&A + R&D | $14.0M | 公司称正常季度开支可能约 $4M |
| HYPE 未实现净收益 | $709.9M | 非现金、随币价反转 |
| 合并时贡献 HYPE 的一次性损失 | -$169.2M | 一次性 |
| 旧生物科技 IPR&D 减记 | -$35.6M | 一次性 |
| 递延所得税费用 | -$183.5M | 未出售 HYPE 也会随未实现增值计提 |
| GAAP 净利润 | $305.5M | 主要是 mark-to-market，不是经营现金利润 |

## 如何正确阅读这次“盈利”

### 事实

- 公司报告 $305.5M 净利润。
- 其中 $709.9M 来自 HYPE 未实现净收益。
- 质押和 validator 收入只有 $9.5M。
- HYPE 在截至 2026-06-30 的季度上涨约 77%。

### 推断

1. 用 GAAP EPS 或 PE 给 PURR 估值意义很低。HYPE 下跌时，公司可能在没有卖币的情况下报告巨额亏损。
2. $9.5M 不能直接当作当前 29.3M HYPE 的稳定年化收益，因为持仓在年内快速增加，平均质押资产低于期末余额。
3. 真正应跟踪的是：
   - 每股 HYPE 数量。
   - 税前和税后 NAV。
   - PURR 相对 NAV 的溢价。
   - 新股发行是否增加每股 HYPE。
   - 质押净收益能否覆盖约 $16M 年化公司开支。

## 资本结构和稀释

### 当前公开输入

[公司 dashboard API](https://hypestrat.xyz/api/dashboard-inputs) 在 2026-08-27 给出：

- HYPE：29.36M。
- Basic shares：224.43M。
- 现金：$132.62M。
- HYPE tax basis：$1,023.75M。
- 税率输入：21.05%。
- Warrants：
  - 0.64M，strike $6.25。
  - 0.60M，strike $6.25。
  - 9.13M，strike $9.38。
  - 9.13M，strike $12.50。
  - 9.13M，strike $18.75。

10-K cover page 被二手索引为 2026-08-23 有约 197.84M common shares outstanding，而 2026-08-27 公司 dashboard 使用 224.43M basic shares。两者相差约 26.6M。可能原因包括期后发行、dashboard 的调整口径或其他股本项目，但公开摘要没有完整解释。

**投资纪律**：计算当前 NAV 时采用较新的公司 dashboard 口径，但在下一份 SEC filing 中必须核对差异。不能用较低的旧股数制造虚假的每股 NAV。

### 为什么发行股票有时增值、有时毁值

- PURR 高于 NAV 发行股票，再用资金买 HYPE：可能增加每股 HYPE/NAV。
- PURR 低于 NAV 发行股票：通常稀释每股 NAV。
- PURR 低于 NAV 回购股票：通常提高剩余股东的每股 NAV。

因此，只看公司“增加了多少 HYPE”不够；必须同时看 basic/fully diluted shares 增长了多少。

## 当前 NAV 重算

### 输入

| 输入 | 数值 |
|------|------|
| HYPE 持仓 | 29.36M |
| HYPE 参考价格 | $79.82 |
| HYPE 市值 | 约 $2,343.5M |
| 现金 | $132.6M |
| 税基 | $1,023.8M |
| 估算递延税 | 约 $277.8M |
| Basic shares | 224.43M |
| 当前价下 treasury-stock method 稀释股数 | 约 226.76M |
| PURR 参考价格 | $11.61 |

### 结果

| 口径 | 每股 NAV | PURR/NAV |
|------|----------|----------|
| 税前、稀释后 | 约 $10.92 | 约 1.06× |
| 税后、稀释后 | 约 $9.69 | 约 1.20× |

税后估算公式：

```text
HYPE value = HYPE held × HYPE price
Estimated DTL = max(HYPE value - tax basis, 0) × 21.05%
After-tax NAV = HYPE value + cash - Estimated DTL
NAV/share = After-tax NAV ÷ treasury-stock-method diluted shares
```

### 为什么不同网站会显示 0.63×、1.02× 或 1.20×

差异可能来自：

- 使用旧 basic share count。
- 使用 basic 而非 fully diluted shares。
- 是否扣除递延税。
- 是否加入 warrant exercise proceeds。
- HYPE 和 PURR 使用不同时间的价格。
- 使用 gross crypto NAV、book NAV 或 adjusted NAV。

本报告不采用 DefiLlama 当前显示的 0.63×，因为它无法与 29.36M HYPE、$11.61 PURR 和公司最新股数直接调和。也不采用旧的 1.02× 作为最终结论，因为公司 2026-08-27 dashboard 的 224.43M basic shares 会明显降低每股 NAV。

## HYPE 价格敏感性

以下使用公司 2026-08-27 输入、21.05% 税率和当前 warrant 稀释近似值。实际股价变化会改变 treasury-stock method 股数。

| HYPE 价格 | 估算税后 NAV | 估算税后 NAV/稀释股 |
|-----------|-------------|----------------------|
| $40 | $1,275M | $5.62 |
| $60 | $1,739M | $7.67 |
| $80 | $2,202M | $9.71 |
| $100 | $2,666M | $11.76 |
| $150 | $3,825M | $16.87 |

大致上，在当前结构下，HYPE 每变化 $10，PURR 的税后 NAV/股约变化 $1.0。实际 PURR 股价还会叠加 NAV 溢价变化。

## 投资逻辑

### 看多逻辑

1. **Hyperliquid 有真实费用池**：公司引用的数据称，截至 2026-06-30 的 12 个月内约 $945M 价值流入 Hyperliquid ecosystem。
2. **协议市场地位强**：公司引用公开数据称，Hyperliquid 在 2026-08-23 占去中心化 perpetual open interest 约 63%。
3. **HYPE 价值捕获较直接**：协议费用通过 Assistance Fund 买回 HYPE；[hl.eco](https://hl.eco/financials) 说明相关 HYPE 被正式 burn。
4. **PURR 没有债务**：没有因币价下跌触发债务清算的直接风险。
5. **质押和 validator 提供收益**：资产不是完全静态持有。
6. **美股可访问性**：部分无法或不愿直接持币的账户可以通过 NASDAQ 获取敞口。
7. **资本配置可形成正循环**：若股票持续高于 NAV，溢价发行可能增加每股 HYPE。

### 看空逻辑

1. **单一资产集中**：PURR 绝大部分价值来自 HYPE，无法靠传统业务抵消币价下跌。
2. **监管风险**：Hyperliquid 的非托管、无许可衍生品模式可能面临 CFTC、SEC 或其他司法辖区限制。公司公告明确说明没有任何涉及 Hyperliquid 的 CFTC 申请、注册、豁免或规则制定已获批准，也不能保证美国合规路径出现。
3. **协议和智能合约风险**：validator、桥、预言机、链上执行、私钥或托管事故可能同时冲击 HYPE 和 PURR 溢价。
4. **代币供应风险**：[hl.eco](https://hl.eco/financials) 明确表示 Hyperliquid 没有公布 team unlock schedule，因此其预测排除了未来团队解锁。这是无法量化的重要风险。
5. **税务拖累**：C corporation 的递延税会让股东不能按 gross HYPE value 一比一受益。
6. **持续稀释**：公司依赖发行股票买币；错误时点发行可能降低每股 HYPE。
7. **Warrant overhang**：多档 warrants 在上涨时增加稀释。
8. **NAV 溢价双杀**：HYPE 下跌时，PURR 可能同时从溢价跌到折价。
9. **交易时段错配**：HYPE 7×24 小时交易，PURR 只在美股时段交易，周末事件会导致跳空。
10. **直接持有替代品**：能直接、安全持有并质押 HYPE 的投资者，可能不愿支付 PURR 的税、费用和 NAV 溢价。

## 情景分析

以下不是目标价预测，而是对 HYPE 和 NAV multiple 的压力测试：

| 情景 | HYPE | 税后 NAV/股 | 假设 PURR/NAV | PURR 情景价 | 相对 $11.61 |
|------|------|-------------|----------------|-------------|-------------|
| 严重熊市 | $40 | $5.62 | 0.80× | $4.50 | -61% |
| 熊市 | $60 | $7.67 | 0.90× | $6.90 | -41% |
| 基准 | $80 | $9.71 | 1.00× | $9.71 | -16% |
| 温和牛市 | $100 | $11.76 | 1.15× | $13.52 | +16% |
| 强牛市 | $150 | $16.87 | 1.30× | $21.93 | +89% |

牛市回报依赖两个变量同时有利：HYPE 上涨且 PURR 维持/扩大 NAV 溢价。熊市也可能两个变量同时恶化。

## 投资策略

### 当前判断

**评级：观察 / 只允许极小试验仓。**

原因：

- HYPE 基本面和协议收入值得继续跟踪。
- PURR 无债务、持仓透明度较高。
- 但当前税后约 1.20× NAV，不是明显折价。
- HYPE 刚经历大幅上涨，PURR 最新财报的 GAAP 利润高度依赖这一涨幅。
- 股数口径存在需要下一份 filing 进一步核对的差异。

### 仓位

由于 `soul/my-soul.md` 尚未填写风险承受能力，采用保守默认：

- 初始试验仓：投资组合的 **0.25%-0.5%**。
- NAV 折价且协议指标稳定后：最多 **1%**。
- 美国监管路径明确、每股 HYPE 持续增长且风险偏好很高：绝对上限 **2%**。
- 不使用融资，不卖裸期权，不把 PURR 当作现金或核心指数替代品。
- 将直接 HYPE、PURR 和其他 crypto treasury 股票合并计算为同一加密风险预算。

### 建仓条件

优先级从高到低：

1. **税后 NAV 折价**：PURR ≤ 1.0× 税后 fully diluted NAV。
2. **合理小溢价**：1.0-1.1× NAV 时，仅在 Hyperliquid 费用、open interest 和 market share 没有恶化时试验建仓。
3. **每股 HYPE 增长**：新股发行后，HYPE/basic share 和 HYPE/fully diluted share 均提高。
4. **质押净收入覆盖开支**：staking/validator 收入接近或超过公司正常运营费用。
5. **股本核对完成**：下一份 SEC filing 能解释 dashboard 224.43M 与 10-K cover 约 197.84M 的差异。

按当前 HYPE 约 $80 计算，税后 NAV 约 $9.7。若其他条件不变：

- PURR 接近或低于 $9.7：开始具备税后 NAV 安全边际。
- $9.7-$10.7：可考虑极小仓位。
- 高于约 $12.1（约 1.25× NAV）：不追涨。

这些价格必须随 HYPE、现金、股数和 warrants 每次重算，不能永久使用。

### 加仓条件

至少满足三项：

- HYPE 不是仅靠市场 beta 上涨，协议费用和交易份额同步增长。
- 每股 HYPE 连续两个披露周期增加。
- Equity facility 发行价持续高于当时 adjusted NAV。
- Staking/validator 收入季度环比增长。
- 没有重大安全事故、validator 惩罚或监管执法。
- PURR 仍低于 1.1× 税后 NAV。

### 减仓条件

- PURR 超过 1.3× 税后 NAV：减仓 25%-50%。
- PURR 超过 1.5× NAV，而每股 HYPE 没有加速增长：只保留观察仓。
- HYPE 快速上涨导致单一加密风险超过组合预算：再平衡。
- 公司在低于 NAV 时大量发行股票：立即降低仓位。

### 退出和论点证伪

任一重大事件触发重新评估，严重时退出：

1. Hyperliquid 遭到导致美国用户、流动性或核心产品明显受限的监管行动。
2. 协议费用、open interest 或去中心化 perpetual market share 持续两个季度显著下降。
3. HYPE 出现重大漏洞、链停摆、私钥/桥/预言机事故或治理攻击。
4. PURR 增加债务或以 HYPE 为抵押使用杠杆。
5. 在 NAV 折价状态下持续发行股票。
6. 每股 HYPE 连续两个披露周期下降。
7. 质押收益下降且不足以覆盖公司开支。
8. 未披露的团队解锁造成显著供应冲击。
9. 财务报告、HYPE 托管证明或 dashboard 数据无法核对。
10. 管理层改变“无债务、以每股价值为核心”的资本配置纪律。

## 每周和每季度跟踪

### 每周

- HYPE price。
- PURR price。
- 公司 dashboard 的 HYPE held、basic shares、cash 和 warrants。
- 税前及税后 fully diluted NAV。
- PURR/NAV multiple。
- Hyperliquid 费用、Assistance Fund buyback、open interest 和 market share。

### 每季度

1. HYPE/basic share 是否增长？
2. HYPE/fully diluted share 是否增长？
3. Staking 和 validator 收入是多少？
4. 正常运营费用是多少？
5. Equity facility 发行价相对 NAV 是多少？
6. 回购是否发生在 NAV 折价时？
7. 现金是否足以覆盖至少 12 个月开支？
8. 是否新增债务、preferred stock、warrants 或其他稀释工具？
9. 递延税负债如何变化？
10. Hyperliquid 监管、安全和 token unlock 是否有新信息？

## PURR 与直接持有 HYPE

| 维度 | PURR | 直接 HYPE |
|------|------|-----------|
| 账户便利 | 可在美股券商和部分退休账户交易 | 需要支持 HYPE 的交易所或钱包 |
| 交易时间 | 美股时段 | 7×24 小时 |
| 质押 | 公司统一质押 | 投资者自行管理 |
| 公司税 | 有递延税和运营费用 | 取决于个人税务 |
| 稀释 | 有新股和 warrants | 有 token issuance/unlock |
| NAV 溢价 | 可能高于或低于资产价值 | 直接按币价交易 |
| 治理/托管 | 依赖公司董事会和托管控制 | 依赖个人操作和协议 |

如果投资者能合法、安全地直接持有并质押 HYPE，只有在 PURR 低于税后 NAV、资本配置能提高每股 HYPE，或账户限制使美股包装有明显价值时，PURR 才更有吸引力。

## 最终结论

PURR 提供了结构清晰、无债务的 HYPE 上市敞口，Hyperliquid 的协议费用、perpetual 市场地位和 HYPE buyback/burn 是值得研究的基本面。但 FY2026 的 $305.5M 净利润主要是 HYPE mark-to-market，不能外推为稳定盈利能力。

当前最重要的不是预测下一季度 EPS，而是每天重算税后 fully diluted NAV，并检查每股 HYPE 是否增长。使用公司最新 dashboard 股数后，PURR 在 $11.61 并非明显便宜。更稳健的做法是等待税后 NAV 折价，或等待监管、每股 HYPE 和质押现金收益提供更强验证，再逐步增加仓位。

## 主要来源

1. [Hyperliquid Strategies FY2026 业绩公告](https://www.prnewswire.com/news-releases/hyperliquid-strategies-inc-reports-financial-results-for-the-fiscal-year-ended-june-30-2026-302861372.html)
2. [公司 dashboard 输入 API](https://hypestrat.xyz/api/dashboard-inputs)
3. [FY2026 Form 10-K（SEC EDGAR）](https://www.sec.gov/Archives/edgar/data/2078856/000119312526370281/purr-20260630.htm)
4. [PURR 市场数据](https://stockanalysis.com/stocks/purr/)
5. [HYPE 历史价格](https://www.coingecko.com/en/coins/hyperliquid/historical_data)
6. [Hyperliquid 协议财务和 burn 方法](https://hl.eco/financials)
7. [DefiLlama PURR treasury 页面](https://defillama.com/digital-asset-treasury/PURR)

风险提示：以上内容仅供研究参考，不构成投资建议。
