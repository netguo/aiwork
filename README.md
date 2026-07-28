# AI Work

AI 技术选型与研究报告合集。

## 报告索引

### GitHub 生态分析

| 报告 | 说明 | 日期 |
|------|------|------|
| [Top 100 Stars](github-analysis/github-top-100-stars.html) | GitHub Star 前 100 仓库，可搜索 HTML 表格 | 2026-07-28 |
| [Top 200 分类（英文）](github-analysis/github-top-200-classified.html) | GitHub Star 前 200 仓库，按 12 类分类，每类按 Star 排序 | 2026-07-28 |
| [Top 200 分类（中文）](github-analysis/github-top-200-classified-zh.html) | 同上，所有简介翻译为中文，侧边栏导航 + 搜索 | 2026-07-28 |

### Agent 框架选型

| 报告 | 说明 | 日期 |
|------|------|------|
| [Agent 框架选型报告](agent-framework/agent-framework-selection-report.html) | 对比 LangChain / Dify / deer-flow，推荐 LangChain + LangGraph 作为团队 Agent 开发基座 | 2026-07-28 |

### RAG 框架选型

| 报告 | 说明 | 日期 |
|------|------|------|
| [RAG 框架选型报告（初版）](rag-framework/rag-framework-selection-report.html) | 从 Top 200 中筛选 RAG 框架，推荐 LangChain 内置 RAG + RAGFlow 分层方案 | 2026-07-28 |
| [RAG Top5 完善对比报告](rag-framework/rag-top5-comparison-report.html) | 重新从 GitHub 搜索 Top5 RAG 框架（RAGFlow / LlamaIndex / LightRAG / GraphRAG / Haystack），8 维度评分，推荐 RAGFlow + LightRAG 分层组合 | 2026-07-28 |

## 选型结论

| 维度 | 推荐 | 理由 |
|------|------|------|
| Agent 基座 | LangChain + LangGraph | 纯框架定位、分层架构、MIT 协议、行业事实标准 |
| RAG 生产层 | RAGFlow (86K Star) | DeepDoc 文档解析最强、UI 完善、引用溯源、多租户 |
| RAG 增强层 | LightRAG (38K Star) | 图+向量双层检索、极轻量、EMNLP 2025 论文背书 |

## 技术栈

- 数据来源：GitHub Search API
- 报告格式：独立 HTML 文件，浏览器直接打开即可查看
- 生成工具：WorkBuddy AI 助手
