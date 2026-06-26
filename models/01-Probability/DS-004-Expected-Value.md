---
id: DS-004
title: Expected Value
title_zh: 期望值
category: Probability & Uncertainty
level: Core
difficulty: 2
importance: 5
status: Stable
prerequisites:
  - DS-001 Base Rate
  - DS-002 Bayesian Updating
  - DS-003 Conditional Probability
related:
  - DS-042 Trade-off
  - DS-043 Decision Matrix
  - DS-044 Decision Tree
tags:
  - Probability
  - Decision Making
  - Long-term Thinking
version: 1.0
---

# DS-004 期望值（Expected Value）

> 好的決策，不是看最好的結果，而是看平均長期結果。

## 一句話定義

Expected Value（EV）是每個可能結果乘上其發生機率後的加總。

## 核心概念

人容易問：

> 最好會怎樣？

高手問：

> 平均而言，我會得到什麼？

EV 代表長期重複決策後，平均得到的價值。

## 核心邏輯

每種結果 × 發生機率 → 全部加總 → Expected Value

## 為什麼重要

期望值能把決策從單次運氣拉回長期平均。

它很適合對抗「只記得最好或最糟一次」這種直覺偏差。

## 使用時機

適合用在這些情境：

- 你要比較多個有不同機率與結果的選項
- 你想避免只被單次輸贏影響
- 你需要把決策放回長期重複情境來看

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

- [DS-042-Trade-off.md](/Users/jason/Documents/Decision-Atlas/models/04-Decision-Science/DS-042-Trade-off.md)
- [DS-043-Decision-Matrix.md](/Users/jason/Documents/Decision-Atlas/models/04-Decision-Science/DS-043-Decision-Matrix.md)
- [DS-044-Decision-Tree.md](/Users/jason/Documents/Decision-Atlas/models/04-Decision-Science/DS-044-Decision-Tree.md)

## 一句總結

> 一次結果可能運氣，長期期望值才是能力。
