---
id: DS-007
title: Expected Utility
title_zh: 期望效用
category: Probability & Uncertainty
level: Core
difficulty: 3
importance: 4
status: Draft
prerequisites:
  - DS-004 Expected Value
related:
  - DS-041 Opportunity Cost
  - DS-042 Trade-off
  - DS-087 Prospect Theory
tags:
  - Decision Making
  - Risk
  - Utility
version: 0.1
---

# DS-007 Expected Utility（期望效用）

> 同樣的期望值，對不同的人，不一定有同樣的價值。

## 一句話定義

Expected Utility（期望效用）是把結果轉成主觀價值後，再用機率加權來比較選項的方法。

## 核心概念

Expected Value 只看數值大小，但真實決策還會受到風險承受度、目標、損失厭惡與資源限制影響。

所以有時候金額相同，感受與決策也會不同。

## 核心邏輯

先列出各種可能結果，再判斷每個結果對決策者真正有多大價值，最後用機率加權比較。

## 為什麼重要

期望效用把「同樣的數值，對不同人不一樣」這件事放進正式決策框架。

它能補上期望值看不到的風險承受度與主觀價值差異。

## 使用時機

適合用在這些情境：

- 你發現同樣期望值的選項，實際上風險感受差很多
- 你需要把風險承受度放進決策
- 你在比較高報酬但高 downside 的方案

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

- [DS-041-Opportunity-Cost.md](/Users/jason/Documents/Decision-Atlas/models/04-Decision-Science/DS-041-Opportunity-Cost.md)
- [DS-042-Trade-off.md](/Users/jason/Documents/Decision-Atlas/models/04-Decision-Science/DS-042-Trade-off.md)
- [DS-087-Prospect-Theory.md](/Users/jason/Documents/Decision-Atlas/models/07-Behavioral-Economics/DS-087-Prospect-Theory.md)

## 一句總結

> 決策不只是在算會賺多少，也是在算自己承受得起什麼。
