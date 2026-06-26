---
id: DS-014
title: Monte Carlo Thinking
title_zh: 蒙地卡羅思維
category: Probability & Uncertainty
level: Core
difficulty: 4
importance: 4
status: Draft
prerequisites:
  - DS-004 Expected Value
  - DS-010 Distribution Thinking
related:
  - DS-009 Variance
  - DS-012 Fat Tail
  - DS-015 Confidence Interval
tags:
  - Simulation
  - Forecasting
  - Risk
version: 0.1
---

# DS-014 Monte Carlo Thinking（蒙地卡羅思維）

> 好的預測不是算一次，而是反覆模擬很多次。

## 一句話定義

Monte Carlo Thinking 是用大量隨機模擬來理解一個決策可能產生哪些結果，以及各結果大概出現的範圍。

## 核心概念

真實世界常同時包含多個不確定變數，彼此還會互相影響。

這種時候，單點估算通常太脆弱。與其問「最可能是多少」，不如反覆模擬，看看結果分布會長什麼樣。

## 核心邏輯

先為關鍵變數設定合理範圍，再多次抽樣組合，觀察整體輸出如何分布。重點不是神準預測，而是看清結果區間與尾端風險。

## 為什麼重要

蒙地卡羅思維能把單一脆弱估計，轉成更誠實的結果區間。

它特別適合處理多變數、高不確定、非線性的預測問題。

## 使用時機

適合用在這些情境：

- 你要預測多個變數共同影響的結果
- 你想看到結果分布而不是單點答案
- 你需要測試不同假設下的尾端風險

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

- [DS-009-Variance.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-009-Variance.md)
- [DS-012-Fat-Tail.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-012-Fat-Tail.md)
- [DS-015-Confidence-Interval.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-015-Confidence-Interval.md)

## 一句總結

> 當世界太多變，與其假裝精準，不如先把可能性跑一遍。
