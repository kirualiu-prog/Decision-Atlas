---
id: DS-012
title: Fat Tail
title_zh: 厚尾
category: Probability & Uncertainty
level: Core
difficulty: 4
importance: 5
status: Draft
prerequisites:
  - DS-009 Variance
  - DS-010 Distribution Thinking
related:
  - DS-011 Black Swan
  - DS-013 Risk vs Uncertainty
  - DS-014 Monte Carlo Thinking
tags:
  - Probability
  - Risk
  - Distribution
version: 0.1
---

# DS-012 Fat Tail（厚尾）

> 有些世界裡，極端結果不是例外，而是規則的一部分。

## 一句話定義

Fat Tail（厚尾）是指分布尾端比常態分布更厚，代表極端事件發生的機率比直覺以為的更高。

## 核心概念

很多人習慣把風險想成「大多差不多，偶爾小偏差」。

但在金融、市場、平台成長、災害與複雜系統裡，極端結果往往不是異常值，而是系統本來就會產生的結果。

## 核心邏輯

若分布具有厚尾特性，平均值和常態直覺就會失靈。少數極端案例可能主導整體結果，因此不能只看中心區域。

## 為什麼重要

厚尾會提醒你，極端案例不一定是例外，它可能就是系統的一部分。

一旦看錯分布形狀，很多看似合理的風險管理都會太樂觀。

## 使用時機

適合用在這些情境：

- 你在處理金融、市場、平台或災害風險
- 你懷疑少數極端值正在主導結果
- 你想檢查常態分布假設是否失真

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

- [DS-011-Black-Swan.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-011-Black-Swan.md)
- [DS-013-Risk-vs-Uncertainty.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-013-Risk-vs-Uncertainty.md)
- [DS-014-Monte-Carlo-Thinking.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-014-Monte-Carlo-Thinking.md)

## 一句總結

> 厚尾世界裡，最貴的錯誤就是把極端事件當作雜訊。
