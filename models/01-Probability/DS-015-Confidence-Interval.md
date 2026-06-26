---
id: DS-015
title: Confidence Interval
title_zh: 信賴區間
category: Probability & Uncertainty
level: Core
difficulty: 4
importance: 4
status: Draft
prerequisites:
  - DS-006 Law of Large Numbers
  - DS-009 Variance
related:
  - DS-001 Base Rate
  - DS-014 Monte Carlo Thinking
  - DS-097 Signal vs Noise
tags:
  - Statistics
  - Estimation
  - Uncertainty
version: 0.1
---

# DS-015 Confidence Interval（信賴區間）

> 好的估計不是報一個數字，而是誠實承認它大概落在哪裡。

## 一句話定義

Confidence Interval（信賴區間）是用一個範圍表達估計值的不確定程度，而不是只給單一點估計。

## 核心概念

單一數字看起來乾淨，但很容易製造假的確定感。

在樣本有限、波動存在時，更有用的問題不是「估計值是多少」，而是「它大概落在什麼範圍，精度有多高」。

## 核心邏輯

樣本有波動，估計就有誤差。信賴區間就是把這個誤差範圍顯示出來，提醒我們不要把估計值當成事實本身。

## 為什麼重要

信賴區間能把假確定感拆掉，讓估計回到更誠實的樣子。

它不只是在表達不確定，更是在提醒你結論的強度其實有限。

## 使用時機

適合用在這些情境：

- 你需要比較兩組資料的估計差異
- 你想知道樣本結論有多穩
- 你懷疑單一數字會誤導判斷

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
- [DS-014-Monte-Carlo-Thinking.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-014-Monte-Carlo-Thinking.md)
- [DS-097-Signal-vs-Noise.md](/Users/jason/Documents/Decision-Atlas/models/09-Meta-Thinking/DS-097-Signal-vs-Noise.md)

## 一句總結

> 有區間的估計比較不漂亮，但通常比較誠實。
