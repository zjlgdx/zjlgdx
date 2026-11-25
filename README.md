# Yvan

全栈开发者，主要用 Swift、Rust 与 TypeScript 编写 macOS / iOS 原生应用、开源字体和 AI 开发工具。

博客记录 AI Agent 的实现、源码分析与工程实践，另有专题研究站与技术连载《从零手写 Agent》《Herdr 实战手记》。

[个人主页](https://aixie.de/) · [博客](https://blog.aixie.de/) · [研究](https://research.aixie.de/) · [应用目录](https://aixie.de/apps) · [RSS](https://blog.aixie.de/feed.xml)

## 应用与字体

- **[Parlance](https://parlance.work/)** — 面向 Claude Code、Codex 等终端智能体的 macOS 菜单栏工具。划词查看翻译与术语解释，用中文或英文写地道回复并贴回原输入框；附开源命令行版 [pl](https://github.com/zjlgdx/parlance)（`brew install zjlgdx/tap/parlance`）。Swift。
- **[Glyph](https://blog.aixie.de/notes/n-20261004-1633)** — 本地优先的 macOS 文本扩展工具，把常用提示词、邮箱与签名存成片段，用短触发词展开或搜索插入，支持填空模板。Swift · [下载](https://blog.aixie.de/download/glyph)。
- **[一粟 Yisu](https://yisu.aixie.de/)** — 三款手绘开源中英文字体（Yinni、Huasha、Louhen），兼顾繁简中文与拉丁字母。官网逐笔书写《兰亭集序》。[字体仓库](https://github.com/zjlgdx/yisu-fonts)。
- **[Wink](https://github.com/hey-yvan/Wink)** — macOS 应用启动与切换工具，把 Caps Lock 设为 Hyper 键，用全局快捷键唤起或收起应用。Swift · [官网](https://wink.aixie.de/)。
- **[PomoFox](https://github.com/hey-yvan/pomofox-releases/releases/latest)** — 像素风格的 macOS 菜单栏番茄钟。Swift。
- **素笺 Sujian**（开发中）— iPhone 上的 agent-first Markdown 笔记应用，纯文件存储与个人 R2 备份。Swift。
- **日课 Rike**（开发中）— iPhone 与 Apple Watch 上的 agent-first 力量训练教练。Swift。
- **展卷 Handscroll**（开发中）— 原生 iOS 长截图应用，支持自动拼接、网页整页与滚动截屏。Swift。

## 网站、工具与主题

- **[Research](https://research.aixie.de/)** — 个人研究发布平台，沉淀公开的专题调研与结构化报告。Cloudflare Workers。
- **[claude-quota-bar](https://github.com/hey-yvan/claude-quota-bar)** — Rust 编写的 Claude Code 终端状态栏，显示 5 小时与 7 天用量额度、上下文占用、缓存时长与 Git 状态。
- **[远山 Yuanshan](https://github.com/zjlgdx/claude-theme-yuanshan)** — 随会话状态响应的 Claude 护眼动态背景主题。TypeScript。
- **[Pinboard](https://github.com/zjlgdx/claude-theme-pinboard)** — 为 Claude 桌面与移动端设计的手工软木板主题。TypeScript。
- **[yapi-mcp-server](https://github.com/zjlgdx/yapi-mcp-server)** — 只读访问 YAPI 接口文档的 MCP Server。JavaScript。
- **[documentation-pdf-scraper](https://github.com/zjlgdx/documentation-pdf-scraper)** — 在线文档抓取与 Kindle 排版优化 PDF 生成器。JavaScript。

## 技术连载

- **[从零手写 Agent](https://blog.aixie.de/series)** — 从裸调用模型 API 起步，逐课实现工具调用、ReAct 与任务循环，再对照生产级 Harness 拆解职责。([源码仓库](https://github.com/zjlgdx/agent-from-scratch))
- **[Herdr 实战手记](https://blog.aixie.de/series)** — 终端多智能体工作流、Hooks 与状态检测实测记录。([源码仓库](https://github.com/zjlgdx/herdr-in-action))

## 近期手记

- [Parlance：读懂 coding agent 的话，说得地道](https://blog.aixie.de/notes/n-20261021-2110)
- [Glyph：从重复的提示词开始](https://blog.aixie.de/notes/n-20261004-1633)
- [让 Herdr 替我盯着：Hooks & State Detection](https://blog.aixie.de/notes/n-20260928-1556)
- [对照生产实现：从一个真实 Harness 的源码里学到什么](https://blog.aixie.de/notes/n-20260901-1510)
