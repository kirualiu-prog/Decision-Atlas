---
id: DS-034
title: MECE
title_zh: 相互獨立，完全窮盡
category: Problem Analysis
level: Core
difficulty: 3
importance: 4
status: Draft
related:
  - DS-035 Issue Tree
  - DS-040 Abstraction Ladder
  - DS-043 Decision Matrix
tags:
  - Structuring
  - Analysis
  - Communication
version: 0.1
---

# DS-034 MECE（相互獨立，完全窮盡）

> 問題一旦分錯類，後面的分析通常只是更整齊地混亂。

## 一句話定義

MECE 是一種拆解問題的原則，要求分類彼此不重疊，且合起來能完整覆蓋問題空間。

## 核心概念

許多分析看起來很完整，其實一邊重複、一邊漏掉。

MECE 的目的不是追求完美分類，而是降低重複討論與重大遺漏，讓後續推理更乾淨。

## 核心邏輯

先決定拆解維度，再檢查各類之間是否混疊，以及是否還有未被涵蓋的區塊。分類愈清楚，分析愈省力。

## 為什麼重要

MECE 能讓你在一開始就少掉很多重複、遺漏和混亂。

對分析、報告、研究設計和團隊分工來說，這是非常高效的整理原則。

## 使用時機

適合用在這些情境：

- 你要拆解一個複雜問題
- 團隊分類方式一直互相打架
- 你需要做一份更乾淨的分析框架

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

- [DS-035-Issue-Tree.md](/Users/jason/Documents/Decision-Atlas/models/03-Problem-Analysis/DS-035-Issue-Tree.md)
- [DS-040-Abstraction-Ladder.md](/Users/jason/Documents/Decision-Atlas/models/03-Problem-Analysis/DS-040-Abstraction-Ladder.md)
- [DS-043-Decision-Matrix.md](/Users/jason/Documents/Decision-Atlas/models/04-Decision-Science/DS-043-Decision-Matrix.md)

## 一句總結

> MECE 不是格式潔癖，而是避免後面一直在漏看和重算。
