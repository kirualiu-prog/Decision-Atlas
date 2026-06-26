---
id: DS-052
title: Minimax
title_zh: 最小最大損失
category: Decision Science
level: Core
difficulty: 3
importance: 4
status: Draft
related:
  - DS-013 Risk vs Uncertainty
  - DS-021 Loss Aversion
  - DS-070 Antifragility
tags:
  - Decision Making
  - Risk
  - Worst-case
version: 0.1
---

# DS-052 Minimax（最小最大損失）

> 當你很難知道最好結果時，至少先避免最糟結果把你帶走。

## 一句話定義

Minimax 是優先選擇那個能把最壞情況損失壓到較低的方案。

## 核心概念

在高不確定性、資訊不足或失敗代價極高時，追求平均最好未必合理。

這時候先控制 downside，往往比追求 upside 更重要。

## 核心邏輯

比較各選項的最壞情況，選擇最壞結果相對可承受的那個。這不是最賺，而是最不容易毀滅。

## 為什麼重要

Minimax 能在高不確定和高代價場景裡，把注意力拉回生存。

當你根本看不清上行時，先把最壞結果壓低，通常是更聰明的起點。

## 使用時機

適合用在這些情境：

- 失敗代價極高
- 資訊不足，無法可靠估計平均結果
- 你需要先確保不出局

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

- [DS-013-Risk-vs-Uncertainty.md](/Users/jason/Documents/Decision-Atlas/models/01-Probability/DS-013-Risk-vs-Uncertainty.md)
- [DS-021-Loss-Aversion.md](/Users/jason/Documents/Decision-Atlas/models/02-Cognitive-Bias/DS-021-Loss-Aversion.md)
- [DS-070-Antifragility.md](/Users/jason/Documents/Decision-Atlas/models/05-Systems-Thinking/DS-070-Antifragility.md)

## 一句總結

> Minimax 的核心不是悲觀，而是在看不清時先確保不出局。
