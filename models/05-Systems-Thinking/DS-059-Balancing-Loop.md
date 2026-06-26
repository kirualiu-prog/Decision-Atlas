---
id: DS-059
title: Balancing Loop
title_zh: 平衡迴路
category: Systems Thinking
level: Core
difficulty: 3
importance: 4
status: Draft
related:
  - DS-057 Feedback Loop
  - DS-061 Delay
  - DS-068 Resilience
tags:
  - Systems
  - Stability
  - Dynamics
version: 0.1
---

# DS-059 Balancing Loop（平衡迴路）

> 不是所有回饋都會失控，有些回饋是讓系統回到某個範圍。

## 一句話定義

Balancing Loop（平衡迴路）是會抵消偏離、把系統拉回目標或穩定範圍的回饋迴路。

## 核心概念

體溫調節、庫存補貨、預算控制、排隊緩解，常都依靠平衡迴路。

這些機制讓系統不至於無限擴張，但如果設計不好，也可能造成僵化或反應過慢。

## 核心邏輯

當結果偏離目標，系統會產生反向作用把它拉回來。重點是觀察這個修正是否足夠快、足夠準。

## 為什麼重要

平衡迴路能解釋為什麼很多系統不會一直失控，而是會回到某個範圍。

看懂平衡迴路，也能幫你發現系統為什麼表面穩定，實際上卻很脆。

## 使用時機

適合用在這些情境：

- 某個系統看起來一直在拉回某個範圍
- 你要理解穩定性從哪裡來
- 你懷疑修正機制太慢或太強

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

- [DS-057-Feedback-Loop.md](/Users/jason/Documents/Decision-Atlas/models/05-Systems-Thinking/DS-057-Feedback-Loop.md)
- [DS-061-Delay.md](/Users/jason/Documents/Decision-Atlas/models/05-Systems-Thinking/DS-061-Delay.md)
- [DS-068-Resilience.md](/Users/jason/Documents/Decision-Atlas/models/05-Systems-Thinking/DS-068-Resilience.md)

## 一句總結

> 平衡迴路的價值，是讓系統不會每次偏離都一路滑到底。
