---
timezone: Asia/Shanghai
---

> 请在上边的 timezone 添加你的当地时区，这会有助于你的打卡状态的自动化更新，如果没有添加，默认为北京时间 UTC+8 时区
> 时区请参考以下列表，请移除 # 以后的内容

timezone: Pacific/Honolulu # 夏威夷-阿留申标准时间 (UTC-10)

timezone: America/Anchorage # 阿拉斯加标准时间 (UTC-9)

timezone: America/Los_Angeles # 太平洋标准时间 (UTC-8)

timezone: America/Denver # 山地标准时间 (UTC-7)

timezone: America/Chicago # 中部标准时间 (UTC-6)

timezone: America/New_York # 东部标准时间 (UTC-5)

timezone: America/Halifax # 大西洋标准时间 (UTC-4)

timezone: America/St_Johns # 纽芬兰标准时间 (UTC-3:30)

timezone: America/Sao_Paulo # 巴西利亚时间 (UTC-3)

timezone: Atlantic/Azores # 亚速尔群岛时间 (UTC-1)

timezone: Europe/London # 格林威治标准时间 (UTC+0)

timezone: Europe/Berlin # 中欧标准时间 (UTC+1)

timezone: Europe/Helsinki # 东欧标准时间 (UTC+2)

timezone: Europe/Moscow # 莫斯科标准时间 (UTC+3)

timezone: Asia/Dubai # 海湾标准时间 (UTC+4)

timezone: Asia/Kolkata # 印度标准时间 (UTC+5:30)

timezone: Asia/Dhaka # 孟加拉国标准时间 (UTC+6)

timezone: Asia/Bangkok # 中南半岛时间 (UTC+7)

timezone: Asia/Shanghai # 中国标准时间 (UTC+8)

timezone: Asia/Tokyo # 日本标准时间 (UTC+9)

timezone: Australia/Sydney # 澳大利亚东部标准时间 (UTC+10)

timezone: Pacific/Auckland # 新西兰标准时间 (UTC+12)

---

# Muyec

1. 自我介绍

   web3新新人。

2. 你认为你会完成本次残酷学习吗？

   能

## Notes

<!-- Content_START -->

### 2024.12.10

1.Arbitrum是什么：Arbitrum 是一个旨在扩展以太坊的技术套件，其核心产品 Arbitrum Rollup 是一种继承以太坊安全性的 Optimistic Rollup 协议，通过降低交易费用和提高交易速度解决了以太坊每秒交易量有限的问题。

2.Arbitrum的技术特点：Arbitrum Rollup 通过将用户交易数据压缩后批量提交至以太坊，并采用“乐观假设”机制，仅在争议情况下触发 L1 验证，从而显著减轻以太坊主网的负担，同时继承以太坊的安全性。

3.多链支持与灵活选择：Arbitrum 支持多条链并行运行，在以太坊主网上，有 2 条 Arbitrum 链：一条 Arbitrum Rollup 链，称为[“Arbitrum One”，](https://portal.arbitrum.one/)一条 AnyTrust 链[，称为“Nova](https://nova.arbitrum.io/)”;用户和开发人员可以选择适合他们的安全/交易成本需求的任何选项。


### 2024.12.11

欺诈证明:欺诈证明是一种逐步细分争议的机制，旨在通过不断缩小争议范围来验证区块和机器状态的正确性。在质询过程中，首先会将全局状态和区块哈希分为两部分，然后逐渐集中到单个区块。在执行阶段，质询被分解为更小的步骤，响应方需要提供数据证明每个步骤的执行状态与预期一致。每一轮质询中，响应方选择相邻的段进行挑战，逐步反驳对方的断言，并细分争议范围。质询的“度数”决定了每次分段的数量，确保挑战不断向前推进。与传统的等分协议不同，本协议采用非对称方式，由挑战者选择要质询的段，响应方提供校样数据。当质询无法得到有效解决时，响应方的状态哈希会被置为 0，从而导致超时失败，最终通过合同升级诊断和修复错误。这种机制不仅确保了挑战过程的透明性，也为错误修复提供了时间窗口。

<!-- Content_END -->
