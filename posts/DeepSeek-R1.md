---
title: "Adam Optimizer"
date: 2025-08-29
categories: [RL, Optimizer]
---

![猫猫镇楼](../images/maomao3.png)

# 结论

这一章节Deepseek-R1的一些特别结论, 结论比较分散

### 代码数学训练集应该先训练

实验证明，先做代码训练再做数学训练，比从通用 LLM 开始更有利于推理能力

### 统一范式

他们把 SFT、RFT、DPO、PPO、GRPO 放到一个统一框架下看待，强调这些方法本质上都是“简化版的 RL”

### 强化学习 (RL) 在做什么

RL 的作用更多是让输出分布更稳定，把正确答案更容易排在 Top-K，而不是提升“基本能力”

# Follow的一些工作

[TinyZero](https://x.com/jiayi_pirate/status/1882839370505621655)

[simpleRL-reason](https://hkust-nlp.notion.site/simplerl-reason)
