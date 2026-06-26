---
id: DS-033
title: Root Cause Analysis
title_zh: 根因分析
category: Problem Analysis
level: Core
difficulty: 3
importance: 5
status: Draft
related:
  - DS-032 Five Whys
  - DS-035 Issue Tree
  - DS-054 Postmortem
tags:
  - Problem Solving
  - Diagnosis
  - Systems
version: 0.1
---

# DS-033 Root Cause Analysis（根因分析）

> 真正值得修的，不是最吵的問題，而是最會反覆製造問題的原因。

## 一句話定義

Root Cause Analysis（根因分析）是系統性找出造成問題反覆出現的底層原因，而不是只修正表面症狀。

## 核心概念

根因不一定只有一個，也不一定離表面最近。

好的根因分析，不是找一個可以怪的點，而是找那個一旦修正，能最有效減少問題再發的原因組合。

## 核心邏輯

先分開現象、近因、促成因素和底層機制，再判斷哪些原因對結果最有槓桿，避免把偶發因素誤當根因。

## 為什麼重要

根因分析能把「反覆補洞」變成「真正減少再發」。

它很適合處理那些表面修好了，但過陣子又重新出現的問題。

## 使用時機

適合用在這些情境：

- 你在處理一個反覆發生的問題
- 團隊對原因有很多說法但沒有結構
- 你需要找出最值得修的那一層

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

- [DS-032-Five-Whys.md](/Users/jason/Documents/Decision-Atlas/models/03-Problem-Analysis/DS-032-Five-Whys.md)
- [DS-035-Issue-Tree.md](/Users/jason/Documents/Decision-Atlas/models/03-Problem-Analysis/DS-035-Issue-Tree.md)
- [DS-054-Postmortem.md](/Users/jason/Documents/Decision-Atlas/models/04-Decision-Science/DS-054-Postmortem.md)

## 一句總結

> 根因分析不是找最深的原因，而是找最值得修的原因。
