<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,10:0077b5,30:00a8e8,70:0969da,100:1f6feb&height=300&section=header&text=Xio-Shark&fontSize=90&fontColor=ffffff&animation=fadeIn&fontAlignY=42&desc=AI%20Agent%20%7C%20Code%20Reviewer%20%7C%20Shark%20Mode%20ON&descSize=22&descAlign=50&descAnimations=twinkling" alt="header" width="100%">
</p>

<p align="center">
  <a href="https://github.com/Xio-Shark">
    <img src="https://komarev.com/ghpvc/?username=Xio-Shark&label=Profile%20Visits&color=00a8e8&style=for-the-badge&logo=shark&logoColor=white" alt="visits" />
  </a>
  <img src="https://img.shields.io/badge/🦈-Shark%20Mode-ON-red?style=for-the-badge" alt="shark" />
  <img src="https://img.shields.io/badge/2027%20届-本科在读-brightgreen?style=for-the-badge" alt="status" />
</p>

---

## 🐟 滕彦翕 (Xio-Shark)

> **2027 届本科在读 | 物联网工程 @ 西北工业大学 | AI 产品 & 工程**

我围绕 **代码 Agent / AI 产品** 持续做评测设计、指标体系搭建与归因分析，同时独立实现生产级 Agent 工作流引擎。

<details>
<summary>🦈 <b>点击展开：鲨鱼的真实想法</b></summary>
<br/>

```python
class XioShark:
    def __init__(self):
        self.name = "滕彦唏"
        self.alias = "Xio-Shark"  # 不是 Xio-Shark，是 Shark！
        self.status = "正在用 AI 改变世界（或者至少改变自己的工作流）"
        self.fuel = "咖啡 + 好奇心"
    
    def daily_routine(self):
        return """
        08:00 - 醒来，思考 AI Agent
        10:00 - 写评测，发现新问题
        14:00 - 优化 Agent 工作流
        18:00 - 吃饭，继续想 AI
        22:00 - 睡觉（做梦还在 Debug）
        """

me = XioShark()
print(me.status)  # 输出：正在用 AI 改变世界（或者至少改变自己的工作流）
```

*警告：这条鲨鱼在写代码时会进入狂暴模式，请勿打扰 🦈*

</details>

---

## 🎯 AI 驱动的工作流

我的日常开发与分析工作系统性地使用 AI 工具提效，以下是我验证过的人机协作模式：

<table>
  <tr>
    <td width="50%" valign="top">

### 1. 评测体系设计
- **场景**：设计代码 Agent 结构化评测任务集
- **AI 用法**：Claude 生成 30 个候选场景 → **人工筛选**为 18 个高覆盖度任务
- **效果**：⏱️ 3天 → 1.5天，覆盖率更高
- **心得**：AI 做"发散"，人工做"收敛"

    </td>
    <td width="50%" valign="top">

### 2. 代码实现辅助
- **场景**：Go Agent 工作流引擎开发
- **AI 用法**：Copilot 辅助 ~30% 代码，Claude 梳理 DAG 状态机
- **效果**：🚀 加速 DAG 编排与 MCP 协议开发
- **心得**：核心逻辑必须人工审核

    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

### 3. 测试覆盖增强
- **场景**：补充边界测试场景
- **AI 用法**：生成并发取消、OOM、网络超时等边界用例
- **效果**：🧪 补充 20+ 高价值测试用例
- **心得**：AI 擅长发现人容易遗漏的角落

    </td>
    <td width="50%" valign="top">

### 4. 数据分析与归因
- **场景**：RAG 检索质量评测结果分析
- **AI 用法**：500 条结果 → AI 分类/聚类 → 人工定位根因
- **效果**：📊 快速提取 TOP3 问题模式
- **心得**：AI 处理数据，人工做决策

    </td>
  </tr>
</table>

> **原则**：AI 负责"从 0 到 0.7"，人工负责"从 0.7 到 1"

---

## 🚀 核心项目

<table>
  <tr>
    <td align="center" width="25%">
      <a href="https://github.com/Xio-Shark/Agent-Exec-Engine">
        <b>Agent-Exec-Engine</b>
      </a>
      <br/>
      <sub>Go</sub>
      <br/>
      <img src="https://img.shields.io/badge/生产级-Engine-blue?style=flat-square" alt="engine" />
      <br/>
      <small>DAG 调度 · ReAct · MCP · Docker 沙箱</small>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/Xio-Shark/agent-eval">
        <b>agent-eval</b>
      </a>
      <br/>
      <sub>Python</sub>
      <br/>
      <img src="https://img.shields.io/badge/评测-框架-green?style=flat-square" alt="eval" />
      <br/>
      <small>Kimi / Claude / Cursor 横向评测</small>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/Xio-Shark/rag">
        <b>rag</b>
      </a>
      <br/>
      <sub>Python/FastAPI</sub>
      <br/>
      <img src="https://img.shields.io/badge/RAG-QA%20Bench-orange?style=flat-square" alt="rag" />
      <br/>
      <small>离线评测 · 指标链路 · 数据驱动</small>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/Xio-Shark/sglang">
        <b>sglang</b>
      </a>
      <br/>
      <sub>Python/C++</sub>
      <br/>
      <img src="https://img.shields.io/badge/贡献-46%20tests-purple?style=flat-square" alt="sglang" />
      <br/>
      <small>通过 maintainer review ✓</small>
    </td>
  </tr>
</table>

---

## 🛠️ 技术栈

<p align="center">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI%20&%20Data-LLM%20评测%20·%20RAG%20·%20Prompt%20Engineering-ff69b4?style=for-the-badge" alt="AI" />
  <img src="https://img.shields.io/badge/Backend-Gin%20·%20FastAPI%20·%20gRPC%20·%20Redis-00add8?style=for-the-badge" alt="backend" />
  <img src="https://img.shields.io/badge/Infra-Docker%20·%20OpenTelemetry%20·%20Grafana-0db7ed?style=for-the-badge" alt="infra" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Xio-Shark&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117" height="180" alt="stats" />
  &nbsp;&nbsp;
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Xio-Shark&theme=tokyonight&hide_border=true&background=0d1117" height="180" alt="streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Xio-Shark&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" height="140" alt="top langs" />
</p>

---

## 🏆 Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Xio-Shark&theme=algolia&no-frame=true&no-bg=true&column=8&margin-w=10" alt="trophies" />
</p>

---

## 📈 Activity Graph

<p align="center">
  <a href="https://github.com/Xio-Shark">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=Xio-Shark&theme=tokyonight&hide_border=true&area=true&bg_color=0d1117&color=00a8e8" alt="activity" width="100%" />
  </a>
</p>

---

## 🐍 Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/Xio-Shark/Xio-Shark/output/github-snake-dark.svg" alt="snake" width="100%" />
</p>

---

## 🎯 鲨鱼今日状态

```
🦈 Xio-Shark Status Dashboard
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
☕ Coffee Level    [████████████████████] 100%
🧠 Brain Power    [██████████████░░░░░░]  70%
🐛 Bugs Remaining [██░░░░░░░░░░░░░░░░░░]  10%
📊 Code Quality   [████████████████░░░░]  80%
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Current Mission: Making Agents Smarter 🎯
```

---

## 🌐 联系我

<p align="center">
  <a href="mailto:xioshark.0127@gmail.com">
    <img src="https://img.shields.io/badge/📧%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="email" />
  </a>
  <a href="https://www.linkedin.com/in/your-linkedin">
    <img src="https://img.shields.io/badge/💼%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" />
  </a>
  <a href="https://twitter.com/your-twitter">
    <img src="https://img.shields.io/badge/🐦%20Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="twitter" />
  </a>
  <a href="https://www.nwpu.edu.cn">
    <img src="https://img.shields.io/badge/🎓%20NWPU-0077B5?style=for-the-badge" alt="nwpu" />
  </a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:00a8e8,70:0969da,100:1f6feb&height=120&section=footer&text=%E6%8E%A8%E5%8A%A8%E8%AF%84%E6%B5%8B%E7%BB%93%E8%AE%BA%E8%90%BD%E5%9C%B0%E4%B8%BA%E8%BF%AD%E4%BB%A3%E7%AD%96%E7%95%A5%20%F0%9F%A6%88&fontSize=22&fontColor=ffffff&animation=fadeIn" alt="footer" width="100%" />
</p>

<p align="center">
  <sub>Made with 💙 and too much ☕ by Xio-Shark</sub>
</p>
