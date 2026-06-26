---
id: DS-006
title: Law of Large Numbers
title_zh: 大數法則
category: Probability & Uncertainty
level: Core
difficulty: 2
importance: 4
status: Draft
prerequisites:
  - DS-001 Base Rate
  - DS-003 Conditional Probability
related:
  - DS-005 Regression to the Mean
  - DS-009 Variance
  - DS-015 Confidence Interval
tags:
  - Probability
  - Statistics
  - Sampling
version: 0.1
---

# DS-006 Law of Large Numbers（大數法則）

> 少量樣本容易講故事，大量樣本才比較接近現實。

## 一句話定義

大數法則是指，當觀察次數愈多，平均結果通常愈接近真實的長期機率。

## 核心概念

人很容易把少數幾次結果當成規律。

但很多現象在小樣本下，本來就會劇烈波動。只有當樣本逐漸增加，我們才更有機會看到穩定模式。

## 核心邏輯

少量觀察時，運氣的影響很大。

觀察次數增加後，偶然偏差會被攤平，結果才逐漸靠近母體真相。

## 為什麼重要

大數法則提醒你，不要用太少樣本就急著相信結論。

它能有效降低把短期波動、少數案例或偶然好壞誤讀成穩定規律的風險。

## 使用時機

適合用在這些情境：

- 你正在根據少量觀察做重要判斷
- 你懷疑一個結論只是小樣本偏差
- 你需要分清楚短期波動和長期規律

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

- [DS-005-Regression-to-the-Mean.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-005-Regression-to-the-Mean.md)
- [DS-009-Variance.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-009-Variance.md)
- [DS-015-Confidence-Interval.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-015-Confidence-Interval.md)

## 一句總結

> 沒有足夠樣本時，先懷疑結論，不要急著懷疑世界。
