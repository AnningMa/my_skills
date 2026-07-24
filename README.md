# AI Skills Collection

A curated collection of reusable AI agent skills.

Each skill is maintained in its own repository to keep development, versioning, and documentation independent. This repository serves as a central index for discovering all available skills.

---

## Available Skills

| Skill | Description | Status |
|-------|-------------|--------|
| ** Stock Picker** | 面向投资者的选股 Skill | 🚧 In Progress |
| ** Writing First Draft** | 帮助作者完成从灵感到初稿的写作 Skill | Complete |
| ** Multiplatform Information Search|利用AI进行多平台、全面的信息搜索| Complete

---

# 📈 Stock Picker

> 面向投资者的选股skill，根据用户的选股要求，制定策略、执行策略，并返回结构化选股报告。

### 功能

- 自动解析用户问句，精准定位用户深层意图
- 从「定性」「定量」两个维度，制定选股策略
- 连接数据源，进行股票筛选
- 根据选股结果，输出结构化选股报告


🔗 Repository

https://github.com/AnningMa/stock-picker-skill

---

# ✍️ Writing First Draft

> 帮助专业作者将零散想法逐步发展为完整文章的写作 Skill。

### 功能

- 深度追问，帮助澄清写作目标
- 梳理零散素材与潜在线索
- 构建逻辑清晰的文章框架
- 引导作者完成可迭代的初稿
- 强调作者参与，而非直接代写


🔗 Repository

https://github.com/AnningMa/writing-first-draft

---

## Philosophy

Rather than serving as isolated prompts, these skills encapsulate reusable workflows, reasoning strategies, and interaction patterns for modern AI agents.

---

# Multiplatform Information Search
> 缩小信息差，利用AI更高效地完整全平台信息检索

### 功能
- 支持中英文搜索、平台定向检索和来源交叉核验
- 为各平台定义首选入口、能力等级和失败降级路径
- 检测有效内容比例与正文可读率
- 支持内容 URL、标题、作者及引用反查
- 外部搜索失败时提供可复制的 App/站内搜索词
- 学术搜索优先使用 OpenAlex、Crossref、Semantic Scholar 和 arXiv

🔗 Repository
https://github.com/AnningMa/multi-platform-search-skill

## Roadmap

Coming soon:

- SOP-builder
- multi-platform-search
- -roduct-discoverer
