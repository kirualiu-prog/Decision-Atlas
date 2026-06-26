---
id: DS-003
title: Conditional Probability
title_zh: 條件機率
category: Probability & Uncertainty
level: Core
difficulty: 3
importance: 5
status: Stable
prerequisites:
  - DS-001 Base Rate
  - DS-002 Bayesian Updating
related:
  - DS-004 Expected Value
  - DS-016 Confirmation Bias
tags:
  - Probability
  - Statistics
  - Context
version: 1.0
---

# DS-003 條件機率（Conditional Probability）

> 任何機率，都依賴於你假設了什麼條件。

## 一句話定義

條件機率，是在某個條件成立的前提下，事件發生的機率。

## 核心概念

很多人問：

> 成功機率是多少？

真正的問題應該是：

> 在什麼條件下？

沒有條件，機率通常沒有意義。

## 核心邏輯

世界 → 設定條件 → 縮小母體 → 重新計算機率

條件改變，機率就改變。

## 為什麼重要

條件機率會逼你把模糊的「大概會不會發生」變成更精確的「在什麼前提下會發生」。

這能有效降低把不同母體混在一起比較的錯誤。

## 使用時機

適合用在這些情境：

- 你正在討論成功率、風險或命中率
- 你懷疑不同前提下的機率其實不同
- 你需要把樣本縮回正確母體再估算

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

- [DS-004-Expected-Value.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-004-Expected-Value.md)
- [DS-016-Confirmation-Bias.md](/Users/jason/Documents/Decision-Atlas/models/02-Cognitive-Bias/DS-016-Confirmation-Bias.md)

## 一句總結

> 不要問成功率，先問：在哪個條件下？
