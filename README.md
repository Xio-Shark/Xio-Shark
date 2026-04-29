## Hi, I'm 滕彦翕 (Xio-Shark) 👋

> 2027 届本科在读 | 物联网工程 @ 西北工业大学 | AI 产品 & 工程

我围绕**代码 Agent / AI 产品**持续做评测设计、指标体系搭建与归因分析，同时独立实现生产级 Agent 工作流引擎。

---

## 🔧 AI 驱动的工作流 (AI Workflow)

我的日常开发与分析工作系统性地使用 AI 工具提效，以下是我验证过的人机协作模式：

### 1. 评测体系设计
- **场景**：设计代码 Agent 结构化评测任务集
- **AI 用法**：将 Agent 核心功能描述给 Claude，生成 30 个候选测试场景 → **人工筛选合并**为 18 个高覆盖度任务集
- **效果**：评测设计时间从 3 天缩短到 1.5 天，覆盖率比纯人工设计更高
- **关键判断**：AI 做"发散"、人工做"收敛"，效率最优

### 2. 代码实现辅助
- **场景**：Go Agent 工作流引擎开发
- **AI 用法**：GitHub Copilot 辅助生成 ~30% boilerplate 代码，核心逻辑人工审核；Claude 辅助梳理 DAG 调度状态机，迭代 3 轮后确定方案
- **效果**：加速 DAG 编排与 MCP 协议模块开发，同时保证核心链路质量

### 3. 测试覆盖增强
- **场景**：补充边界测试场景
- **AI 用法**：利用大模型生成并发取消、OOM、网络超时等边界测试用例
- **效果**：补充 20+ 高价值测试用例，覆盖人工容易遗漏的异常链路

### 4. 数据分析与归因
- **场景**：RAG 检索质量评测结果分析
- **AI 用法**：将 500 条评测结果输入模型，先由 AI 分类/聚类 → 人工深入定位根因
- **效果**：快速提取 TOP3 问题模式，缩短分析周期

### 5. 文档与知识整理
- **场景**：技术文档、评测报告、论文速读
- **AI 用法**：AI 生成初稿/提取三要素 → 人工校验逻辑与事实
- **原则**：AI 负责"从 0 到 0.7"，人工负责"从 0.7 到 1"

---

## 🚀 核心项目

| 项目 | 技术 | 亮点 |
|------|------|------|
| [**Agent-Exec-Engine**](https://github.com/Xio-Shark/Agent-Exec-Engine) | Go | 生产级 Agent 工作流引擎 — DAG 调度 · ReAct · MCP · Docker 沙箱 · 114 测试 |
| [**agent-eval**](https://github.com/Xio-Shark/agent-eval) | Python/评测方法论 | Kimi Code / Claude Code / Cursor / Hermes Agent 系统性横向评测 |
| [**rag**](https://github.com/Xio-Shark/rag) | Python/FastAPI | RAG QA Bench — 离线评测 · 指标链路 · 数据驱动选型 |
| [**sglang**](https://github.com/Xio-Shark/sglang) | Python/C++ | 向上游贡献 46 个单元测试，通过 maintainer review |

---

## 🛠 技术栈

**语言**: Go (主力) · Python · TypeScript · C++  
**AI & 数据**: Prompt Engineering · RAG · LLM 评测 · scikit-opt · pandas  
**后端**: Gin · FastAPI · gRPC · Redis · PostgreSQL · Docker  
**可观测性**: OpenTelemetry · Prometheus · Grafana  
**工具**: Claude · Cursor · GitHub Copilot · Kimi Code

---

## 📫 联系我

- 📧 xioshark.0127@gmail.com
- 💼 [投递简历 / 合作请联系邮箱]

> *"推动评测结论落地为迭代策略"*
