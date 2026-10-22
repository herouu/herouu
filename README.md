<h1 align="center">尘客</h1>

<p align="center">给 opencode 写插件，顺带折腾 RPA 和电路板。</p>

<p align="center">
  <a href="https://herouu.dpdns.org">博客</a> ·
  <a href="https://github.com/herouu?tab=repositories">全部仓库</a>
</p>

## 在做的

opencode 插件两个：一个补跨会话记忆，一个把 Command Code 的模型一次性接进来。都做成零依赖，不想装完还得配一堆环境。

博客里那套问答跑在 Cloudflare Worker 上，向量检索用 Vectorize。最近主要在调评估，光换模型和改 prompt 都试过了，收益一般。

另外是自动化：影刀建流，还有把自然语言直接变成嘉立创EDA 的工程文件。省下的时间没想象中多，好处是不用反复点鼠标。

## 项目

- **[opencode-commandcode](https://github.com/herouu/opencode-commandcode)** 一个 API key 接上 Command Code 的 70 多个模型，不用给每家单独开 key。<br><sub>TypeScript</sub>
- **[opencode-local-memory](https://github.com/herouu/opencode-local-memory)** opencode v2 本身没有跨会话记忆。这个插件把对话存本地，按关键词检索后塞回上下文。<br><sub>TypeScript</sub>
- **[chenke-nl2jlceda](https://github.com/herouu/chenke-nl2jlceda)** 一句话要求变成 tscircuit 电路，再导出嘉立创EDA专业版工程。中间要过 DFM 和 DRC，不然打样过不了。<br><sub>JavaScript</sub>
- **[shadowbot-visual-flow](https://github.com/herouu/shadowbot-visual-flow)** 影刀可视化流程用 MCP 建流时记的笔记。作用域和隐式输出编号最容易踩。<br><sub>MCP · 影刀</sub>

## 技术栈

### 语言

<img src="https://img.shields.io/badge/Python-4a5568?style=flat-square&labelColor=2d3748&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/Java-4a5568?style=flat-square&labelColor=2d3748&logo=openjdk&logoColor=white" alt="Java" /> <img src="https://img.shields.io/badge/Go-4a5568?style=flat-square&labelColor=2d3748&logo=go&logoColor=white" alt="Go" /> <img src="https://img.shields.io/badge/TypeScript-4a5568?style=flat-square&labelColor=2d3748&logo=typescript&logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/Rust-4a5568?style=flat-square&labelColor=2d3748&logo=rust&logoColor=white" alt="Rust" /> <img src="https://img.shields.io/badge/Vue-4a5568?style=flat-square&labelColor=2d3748&logo=vuedotjs&logoColor=white" alt="Vue" />

### AI · 数据

<img src="https://img.shields.io/badge/Jupyter-4a5568?style=flat-square&labelColor=2d3748&logo=jupyter&logoColor=white" alt="Jupyter" /> <img src="https://img.shields.io/badge/MCP-4a5568?style=flat-square&labelColor=2d3748" alt="MCP" /> <img src="https://img.shields.io/badge/RAG-4a5568?style=flat-square&labelColor=2d3748" alt="RAG" /> <img src="https://img.shields.io/badge/Vector%20Search-4a5568?style=flat-square&labelColor=2d3748" alt="Vector Search" /> <img src="https://img.shields.io/badge/MySQL-4a5568?style=flat-square&labelColor=2d3748&logo=mysql&logoColor=white" alt="MySQL" />

### 边缘 · 部署

<img src="https://img.shields.io/badge/Cloudflare%20Workers-4a5568?style=flat-square&labelColor=2d3748&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" /> <img src="https://img.shields.io/badge/Pages-4a5568?style=flat-square&labelColor=2d3748&logo=cloudflarepages&logoColor=white" alt="Pages" /> <img src="https://img.shields.io/badge/Docker-4a5568?style=flat-square&labelColor=2d3748&logo=docker&logoColor=white" alt="Docker" /> <img src="https://img.shields.io/badge/Linux-4a5568?style=flat-square&labelColor=2d3748&logo=linux&logoColor=white" alt="Linux" />

### 自动化 · 工具

<img src="https://img.shields.io/badge/opencode-4a5568?style=flat-square&labelColor=2d3748" alt="opencode" /> <img src="https://img.shields.io/badge/ShadowBot%20RPA-4a5568?style=flat-square&labelColor=2d3748" alt="ShadowBot RPA" /> <img src="https://img.shields.io/badge/EasyEDA-4a5568?style=flat-square&labelColor=2d3748" alt="EasyEDA" /> <img src="https://img.shields.io/badge/Git-4a5568?style=flat-square&labelColor=2d3748&logo=git&logoColor=white" alt="Git" />

## 其它

<details>
<summary>展开</summary>

- [services](https://github.com/herouu/services) — Windows 后台服务管理，拿来替 NSSM。
- [cmd_linux2win](https://github.com/herouu/cmd_linux2win) — 在 Windows 上敲 linux 命令。
- [go-mysqlstat](https://github.com/herouu/go-mysqlstat) — MySQL 状态采集。
- [vibe-img](https://github.com/herouu/vibe-img) — Cloudflare Pages 上的像素头像生成器。
- [workers-iot](https://github.com/herouu/workers-iot) — IoT worker，vibe coding 写的。
- [roughness](https://github.com/herouu/roughness) — 手绘风 Vue 组件库，fork 来的，按自己需要改过。

</details>

## 博客

<https://herouu.dpdns.org>，写前端、后端、AI（RAG 评估、多模态、知识图谱）、数据库、网络、物联网、运维。

有 bug 直接开 issue。
