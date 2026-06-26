---
id: DS-005
title: Regression to the Mean
title_zh: 回歸平均
category: Probability & Uncertainty
level: Core
difficulty: 2
importance: 4
status: Stable
related:
  - DS-001 Base Rate
  - DS-004 Expected Value
  - DS-097 Signal vs Noise
tags:
  - Probability
  - Variation
  - Judgment
version: 1.0
---

# DS-005 回歸平均（Regression to the Mean）

> 極端表現，通常不會一直持續。

## 一句話定義

當某次表現特別高或特別低時，下一次往往更接近平均值。

## 核心概念

人類很喜歡解釋：

> 昨天超好，今天變差，一定有原因。

很多時候，原因只是自然波動。

## 核心邏輯

平均 → 偶然偏高 → 下一次 → 回到平均附近

## 為什麼重要

回歸平均能防止你把自然波動過度故事化。

很多看似神奇的好轉或惡化，其實只是極端值之後的正常回落。

## 使用時機

適合用在這些情境：

- 你正在解讀極端好或極端差的單次表現
- 你懷疑團隊把波動誤讀成改善或失敗
- 你需要判斷某次異常值是否值得大幅反應

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

- [DS-001-Base-Rate.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-001-Base-Rate.md)
- [DS-004-Expected-Value.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-004-Expected-Value.md)
- [DS-097-Signal-vs-Noise.md](/Users/jason/Documents/Decision-Atlas/models/09-Meta-Thinking/DS-097-Signal-vs-Noise.md)

## 一句總結

> 不是每一次起伏，都需要一個故事。
