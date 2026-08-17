# 游戏设计梦工厂 Skill (Game Design Workshop) 🎮

> 基于 Tracy Fullerton 经典著作《游戏设计梦工厂》（*Game Design Workshop*）的 AI Agent 全流程「以玩为中心（Playcentric Design）」游戏设计导师 Skill。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![AI Agent Skill](https://img.shields.io/badge/AI-Agent%20Skill-blueviolet.svg)](https://github.com/Wilson520403/game-design-skills)

[English](README.md) | 简体中文

---

## 📖 简介

《游戏设计梦工厂》（*Game Design Workshop*）是全球顶尖游戏设计院校与专业开发者的核心经典。全书倡导**「以玩为中心（Playcentric）」**的迭代设计哲学，核心信条为**“早失败、廉价失败（Fail Early, Fail Cheap）”**。

本 Skill 将书中的核心理念、形式/戏剧元素模型与实战评估方法论深度结构化，让 AI 能够充当你的资深游戏设计导师，支持：

1. **引导式 0 到 1 游戏设计共创 (Co-Design)**：从模糊概念出发，逐步明确核心体验目标、8 大形式元素、4 大戏剧元素、原型方案到 GDD 文档沉淀。
2. **游戏机制体检与诊断 (Mechanics Diagnostic)**：针对现有规则、数值与策划案，从玩家能动性、最优解支配、反馈回路失衡、心流曲线等维度进行深度体检与调优。
3. **全套实操模板与工具箱**：内置单页 Pitch 模板、Playcentric GDD 大纲、原型验证清单、测试观察方案与问卷。

---

## 📂 仓库与知识库结构

```
game-design-workshop/
├── SKILL.md                          # Skill 核心入口：方法论概览、触发声明、双模态交互工作流
├── README.md                         # 英文说明文档
├── README_CN.md                      # 中文说明文档 (简体中文)
├── LICENSE                           # MIT 开源许可证
└── references/
    ├── formal-elements.md            # 8 大形式元素（玩家/目标/规程/规则/资源/冲突/边界/结果）及反馈回路
    ├── dramatic-elements.md          # 4 大戏剧元素（前提/角色/戏剧弧线/世界观）与叙事玩法融合
    ├── prototyping-guide.md          # 实体纸面原型与数字灰模原型设计、假设驱动验证法
    ├── playtesting-and-metrics.md    # 5 阶段测试法、现场观察三铁律、非引导性访谈技巧与心流指标
    └── templates-and-checklists.md   # 5 套实战模板（One-page Pitch、GDD大纲、测试问卷、诊断体检表等）
```

---

## ⚡ 安装方式

通过你的 AI Agent 直接安装本 Skill：

### 方式 1：AI 提示词安装（推荐）

在与 AI 对话时发送以下指令：

```text
请帮我从 https://github.com/Wilson520403/game-design-skills.git 克隆并安装 Game Design Workshop skill 到我的全局 skills 目录。
```

### 方式 2：命令行克隆

```bash
git clone https://github.com/Wilson520403/game-design-skills.git temp-skills && cp -r temp-skills/game-design-workshop ~/.config/skills/ && rm -rf temp-skills
```

---

## 🎯 使用示例

安装完成后，在与 AI 交流时直接自然语言触发：

- **从 0 到 1 构思新游戏**: *“我想构思一款结合手语手势识别的解谜探险游戏，请根据《游戏设计梦工厂》的方法论带我梳理核心体验目标与形式元素。”*
- **诊断与改良已有机制**: *“我们做了一套卡牌行动点数（AP）分配机制，但测试时玩家总是只用同一种无脑打法，帮我用游戏设计梦工厂的方法诊断一下原因并给出调优建议。”*
- **生成测试问卷与原型清单**: *“针对我们当前的 BOSS 战核心机制，请出一份用于小组盲测的观察记录表和测试后访谈问卷。”*

---

## 📜 核心参考书目

- Tracy Fullerton, *Game Design Workshop: A Playcentric Approach to Creating Innovative Games* (4th Edition), CRC Press.

---

## 📄 License

本项目采用 [MIT License](LICENSE) 授权开源。
