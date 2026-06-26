---
id: DS-037
title: Bottleneck Analysis
title_zh: 瓶頸分析
category: Problem Analysis
level: Core
difficulty: 2
importance: 4
status: Draft
related:
  - DS-032 Five Whys
  - DS-036 Constraint Theory
  - DS-063 Leverage Point
tags:
  - Operations
  - Throughput
  - Analysis
version: 0.1
---

# DS-037 Bottleneck Analysis（瓶頸分析）

> 當一條流程變慢，先找最窄的地方，不要先怪整條路。

## 一句話定義

Bottleneck Analysis（瓶頸分析）是找出流程、系統或組織中最限制速度與產出的環節。

## 核心概念

瓶頸不一定最顯眼，也不一定最忙。

有時候真正的瓶頸是等待、交接、審批、依賴關係，而不是表面上看起來工作量最大的人或步驟。

## 核心邏輯

觀察流程的等待、阻塞、排隊與返工位置。誰讓上游堆積、讓下游斷料，誰就更可能是瓶頸。

## 為什麼重要

瓶頸分析能讓你更快把精力集中到會影響整體 throughput 的地方。

很多表面忙碌和真瓶頸並不是同一件事，這個工具正好能拆開它們。

## 使用時機

適合用在這些情境：

- 某個流程總是慢，但不確定真正卡在哪
- 大家都覺得自己很忙，卻無法解釋整體進度
- 你需要找出最值得優先疏通的環節

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
- [DS-036-Constraint-Theory.md](/Users/jason/Documents/Decision-Atlas/models/03-Problem-Analysis/DS-036-Constraint-Theory.md)
- [DS-063-Leverage-Point.md](/Users/jason/Documents/Decision-Atlas/models/05-Systems-Thinking/DS-063-Leverage-Point.md)

## 一句總結

> 瓶頸分析不是找最辛苦的人，而是找最卡住系統的人或步驟。
