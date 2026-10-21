<h1 align="center">尘客</h1>

<p align="center">把 AI agent、RPA、EDA 串成流水线，做出来的东西写到博客里。</p>

<p align="center">
  <a href="https://herouu.dpdns.org">博客</a> ·
  <a href="https://github.com/herouu?tab=repositories">全部仓库</a>
</p>

<p align="center"><sub>不急，但不停。</sub></p>

## 在做什么

- **opencode 插件生态** — 给 opencode 写插件：本地记忆、模型接入，尽量做到零依赖、装上即用。
- **AI agent 与 RAG** — 博客站内跑着一套检索增强问答（Cloudflare Worker + Vectorize），更在意检索质量和评估结果，而不是只挂一个对话框。
- **RPA 与 EDA 自动化** — 影刀建流、自然语言直接生成嘉立创EDA 工程，把点鼠标的活换成脚本。

## 精选项目

- **[opencode-commandcode](https://github.com/herouu/opencode-commandcode)** — 一个 API key 就跑通 Command Code 的 70+ 模型（Claude / GPT / Gemini / DeepSeek / Qwen / Kimi / GLM），不必逐家配 key。<br><sub>TypeScript</sub>
- **[opencode-local-memory](https://github.com/herouu/opencode-local-memory)** — 给 opencode v2 补上跨会话记忆：零依赖落盘，按关键词检索后注入上下文。<br><sub>TypeScript</sub>
- **[chenke-nl2jlceda](https://github.com/herouu/chenke-nl2jlceda)** — 一句话描述需求 → tscircuit 电路 → 嘉立创EDA专业版 .epro，链路里带 DFM/DRC 校验。<br><sub>JavaScript</sub>
- **[shadowbot-visual-flow](https://github.com/herouu/shadowbot-visual-flow)** — 影刀 VisualFlow 用 MCP 编程建流的字段笔记：作用域、隐式输出、踩坑速查。<br><sub>MCP · 影刀</sub>

## 技术栈

### 语言

<img src="https://img.shields.io/badge/Python-4a5568?style=flat-square&labelColor=2d3748&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/Java-4a5568?style=flat-square&labelColor=2d3748&logo=openjdk&logoColor=white" alt="Java" /> <img src="https://img.shields.io/badge/Go-4a5568?style=flat-square&labelColor=2d3748&logo=go&logoColor=white" alt="Go" /> <img src="https://img.shields.io/badge/TypeScript-4a5568?style=flat-square&labelColor=2d3748&logo=typescript&logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/Rust-4a5568?style=flat-square&labelColor=2d3748&logo=rust&logoColor=white" alt="Rust" /> <img src="https://img.shields.io/badge/Vue-4a5568?style=flat-square&labelColor=2d3748&logo=vuedotjs&logoColor=white" alt="Vue" />

### AI · 数据

<img src="https://img.shields.io/badge/Jupyter-4a5568?style=flat-square&labelColor=2d3748&logo=jupyter&logoColor=white" alt="Jupyter" /> <img src="https://img.shields.io/badge/MCP-4a5568?style=flat-square&labelColor=2d3748" alt="MCP" /> <img src="https://img.shields.io/badge/RAG-4a5568?style=flat-square&labelColor=2d3748" alt="RAG" /> <img src="https://img.shields.io/badge/Vector%20Search-4a5568?style=flat-square&labelColor=2d3748" alt="Vector Search" /> <img src="https://img.shields.io/badge/MySQL-4a5568?style=flat-square&labelColor=2d3748&logo=mysql&logoColor=white" alt="MySQL" />

### 边缘 · 部署

<img src="https://img.shields.io/badge/Cloudflare%20Workers-4a5568?style=flat-square&labelColor=2d3748&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" /> <img src="https://img.shields.io/badge/Pages-4a5568?style=flat-square&labelColor=2d3748&logo=cloudflarepages&logoColor=white" alt="Pages" /> <img src="https://img.shields.io/badge/Docker-4a5568?style=flat-square&labelColor=2d3748&logo=docker&logoColor=white" alt="Docker" /> <img src="https://img.shields.io/badge/Linux-4a5568?style=flat-square&labelColor=2d3748&logo=linux&logoColor=white" alt="Linux" />

### 自动化 · 工具

<img src="https://img.shields.io/badge/opencode-4a5568?style=flat-square&labelColor=2d3748" alt="opencode" /> <img src="https://img.shields.io/badge/ShadowBot%20RPA-4a5568?style=flat-square&labelColor=2d3748" alt="ShadowBot RPA" /> <img src="https://img.shields.io/badge/EasyEDA-4a5568?style=flat-square&labelColor=2d3748" alt="EasyEDA" /> <img src="https://img.shields.io/badge/Git-4a5568?style=flat-square&labelColor=2d3748&logo=git&logoColor=white" alt="Git" />

## 更多项目

<details>
<summary>展开更多项目</summary>

- [services](https://github.com/herouu/services) — Windows 后台服务管理工具，拿来当 NSSM 用。
- [cmd_linux2win](https://github.com/herouu/cmd_linux2win) — 在 Windows 上直接敲 linux 命令。
- [go-mysqlstat](https://github.com/herouu/go-mysqlstat) — MySQL 运行状态采集的小工具。
- [vibe-img](https://github.com/herouu/vibe-img) — 跑在 Cloudflare Pages 上的确定性像素头像生成器。
- [workers-iot](https://github.com/herouu/workers-iot) — vibe coding 出来的 IoT worker。
- [roughness](https://github.com/herouu/roughness) — 手绘风格 Vue 组件库，fork 后按自己的需要改。

</details>

## 博客

博客在 <https://herouu.dpdns.org>，写前端、后端、人工智能（RAG 评估、多模态、知识图谱）、数据库、网络、物联网、运维开发这些题材。

踩过的坑基本都落在那里；上面这些仓库的问题，直接开 issue 就行。
