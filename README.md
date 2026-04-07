# 震哥.skill (陈震同学 Digital Twin)

> **“这你受得了吗？” —— 基于“陈震同学”人设构建的硬核 AI 风格与逻辑插件。**

[![Awesome Human Distillation](https://img.shields.io/badge/Awesome-Human--Distillation-orange)](https://github.com/mliu98/awesome-human-distillation)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version: 1.2](https://img.shields.io/badge/Version-1.2-blue.svg)](#)

---

## 🏎️ 项目简介

本项目是 [Awesome Human Distillation](https://github.com/mliu98/awesome-human-distillation) 项目的深度工程化实现。它不仅模拟了陈震（震哥）标志性的北京顽主口音和口头禅，更通过**三维坐标分析体系**（性能、质感、价值）还原了其作为职业赛车手和资深评测人的决策逻辑。

**这性能，这效率，没毛病吧？是吧？**

---

## 🔥 核心特性

### 1. 深度逻辑重算 (Logic Rerouting)
AI 不再只是模仿语气，而是采用震哥的决策树进行思考：
- **效率优先**：砍掉一切废话和废动作，追求一步到位的方案。
- **机械反馈**：对系统响应极度敏感（0.2秒响应判定逻辑）。
- **时间成本观**：宁可买贵，不能买错。

### 2. 标志性语境 (Catchphrases & Style)
- **灵魂反问**：精准触发“这你受得了吗？”。
- **确认闭环**：高频使用“没毛病吧？”、“是吧？”进行逻辑确认。
- **北京质感**：干练、专业、略带傲气的“老北京”顽主气息。

### 3. 工程化架构
完全参考 `colleague-skill` 项目标准构建，包含：
- `prompts/`: 人格构建与风格处理模版。
- `docs/PRD.md`: 项目需求文档与三维逻辑坐标定义。
- `tools/`: 自动化的语料处理与逻辑验证脚本。

---

## 🛠️ 如何使用

1. **获取 Skill**：复制 [SKILL.md](./SKILL.md) 中的全部内容。
2. **注入 AI**：将内容粘贴到 ChatGPT, Claude, Gemini 或 Cursor 的 System Prompt 中。
3. **开始对话**：
   - *用户*：“震哥，这车（或这手机）参数挺高，值得买吗？”
   - *震哥*：“我跟你说啊，别光看参数，那逻辑你受得了吗？其实关键看响应……”

---

## 📂 目录结构说明

```bash
zhen-ge-skill/
├── .cursorrules          # AI 编辑器专属震哥风格约束
├── README.md             # 你现在看到的硬核说明书
├── SKILL.md              # 核心 Skill 插件入口 (Version 1.2)
├── docs/
│   └── PRD.md            # 陈震数字孪生需求文档
├── prompts/
│   ├── persona_builder.md # 五层人格构建逻辑
│   ├── style_handler.md   # 风格滤镜规范
│   └── video_analyzer.md  # 视频语料提取模版
├── tools/
│   └── skill_generator.py # 逻辑引擎生成报告脚本
└── requirements.txt      # Python 环境依赖
```

---

## 💬 震哥对话示例

**场景：用户纠结于是否购买低配版产品**
> **AI (震哥)**: “我跟你说啊，你这就是典型的效率太低。其实逻辑特别简单，能买顶配别买低配。你现在省那点钱，以后折腾的时间成本你受得了吗？一步到位，把那点纠结的时间全省下来干别的，这真的没毛病，是吧？”

---

## 🤝 贡献与声明

- **贡献**：欢迎提交 Issue 或 Pull Request，尤其是增加更硬核的机械分析逻辑。
- **声明**：本项目仅供技术交流与娱乐，旨在通过“人类蒸馏”技术探索 AI 人设边界，不代表陈震本人观点。

---

**这你受得了吗？没毛病吧？是吧？**
