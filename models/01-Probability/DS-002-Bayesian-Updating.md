---
id: DS-002
title: Bayesian Updating
title_zh: 貝葉斯更新
category: Probability & Uncertainty
level: Core
difficulty: 3
importance: 5
status: Stable
aliases:
  - Bayes' Rule
  - Bayesian Reasoning
  - 貝氏更新
prerequisites:
  - DS-001 Base Rate
related:
  - DS-003 Conditional Probability
  - DS-004 Expected Value
  - DS-016 Confirmation Bias
  - DS-097 Signal vs Noise
tags:
  - Probability
  - Decision Making
  - Statistics
  - Evidence
version: 1.0
---

# DS-002 Bayesian Updating（貝葉斯更新）

> 好的決策不是一次就做對，而是根據新證據持續修正。

## 一句話定義

Bayesian Updating（貝葉斯更新）是根據新證據，不斷調整原本信念（Prior）的思考方法。

## 核心概念

世界是不確定的。我們幾乎不可能在第一次判斷時，就掌握全部資訊。

真正重要的能力不是一開始就猜對，而是：

> 當新證據出現時，願意調整自己的判斷。

## 核心邏輯

原本相信什麼（Prior） → 出現新的證據（Evidence） → 更新信念（Posterior）

## 為什麼重要

這個模型把「願意修正」變成一種方法，而不是一種態度。

它幫助你避免兩種常見錯誤：完全不更新，或因單一新訊號過度更新。

## 使用時機

適合用在這些情境：

- 你本來已有初步判斷，但新證據正在進來
- 你需要持續校正而不是一次定案
- 你想分清楚哪些訊號值得改變看法

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

- [DS-003-Conditional-Probability.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-003-Conditional-Probability.md)
- [DS-004-Expected-Value.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-004-Expected-Value.md)
- [DS-016-Confirmation-Bias.md](/Users/jason/Documents/Decision-Atlas/models/02-Cognitive-Bias/DS-016-Confirmation-Bias.md)
- [DS-097-Signal-vs-Noise.md](/Users/jason/Documents/Decision-Atlas/models/09-Meta-Thinking/DS-097-Signal-vs-Noise.md)

## 一句總結

> 不要因為新證據放棄原本的判斷，也不要因為原本的判斷拒絕新證據。真正好的決策，是持續更新。
