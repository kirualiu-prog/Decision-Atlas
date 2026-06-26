---
id: DS-009
title: Variance
title_zh: 變異
category: Probability & Uncertainty
level: Core
difficulty: 3
importance: 4
status: Draft
prerequisites:
  - DS-004 Expected Value
related:
  - DS-006 Law of Large Numbers
  - DS-008 Randomness
  - DS-015 Confidence Interval
tags:
  - Probability
  - Risk
  - Statistics
version: 0.1
---

# DS-009 Variance（變異）

> 平均值告訴你大概會去哪，變異告訴你路上會多顛簸。

## 一句話定義

Variance（變異）是在描述結果分散程度，也就是結果偏離平均值的幅度有多大。

## 核心概念

兩個選項可以有相同的平均結果，但波動完全不同。

如果只看平均值，不看變異，就可能低估風險，或誤判策略穩定性。

## 核心邏輯

平均值衡量中心，變異衡量波動。波動愈大，單次結果與長期平均之間的落差就可能愈大。

## 為什麼重要

變異讓你知道同樣平均值背後，風險體驗可能完全不同。

如果不看變異，很多看似穩定或划算的策略，其實只是把波動藏起來了。

## 使用時機

適合用在這些情境：

- 你要比較相同平均值但不同波動的選項
- 你需要判斷風險是否可承受
- 你懷疑單次結果與長期結果落差很大

## Key Questions

- 這個模型在這個情境真的適用嗎？
- 它最重要的前提或限制是什麼？
- 如果用這個模型看問題，決策會因此改變什麼？

## Failure Modes

- 把模型套到不適合的問題
- 把模型當成唯一答案
- 記住名詞，卻沒有回到實際判斷

## Concept Boundary

這個模型提供的是一種特定視角，不會單獨取代完整分析。

比較好的用法，通常是和相鄰模型一起交叉檢查。

## Related Models

- [DS-006-Law-of-Large-Numbers.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-006-Law-of-Large-Numbers.md)
- [DS-008-Randomness.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-008-Randomness.md)
- [DS-015-Confidence-Interval.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-015-Confidence-Interval.md)

## 一句總結

> 平均決定方向，變異決定你能不能撐到那個方向成真。
