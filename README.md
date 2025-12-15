1. 标题与引言 (Title & Intro)📝 源码 (Source Code)# 🌌 Lunatv / TvBox Interface Converter (iOS 26 Edition)

> 一个极具未来感、流畅且强大的影视接口配置转换工具。
> 
> **设计理念**：iOS 26 概念设计 | 极光玻璃拟态 | 物理级丝滑交互
👁️ 渲染预览 (Rendered Preview)🌌 Lunatv / TvBox Interface Converter (iOS 26 Edition)一个极具未来感、流畅且强大的影视接口配置转换工具。设计理念：iOS 26 概念设计 | 极光玻璃拟态 | 物理级丝滑交互2. 项目简介 (Description)📝 源码 (Source Code)## ✨ 项目简介

本项目是一个**单文件 (Single-File)** 的 HTML 工具，旨在解决 Lunatv 与 TvBox 两大主流影视配置格式之间的互转难题。

区别于传统的转换工具，本项目不仅在核心算法上实现了**全能无条件深度提取**，更在 UI/UX 上进行了革命性的升级，带来了媲美原生 iOS 应用的视觉与操作体验。
👁️ 渲染预览 (Rendered Preview)✨ 项目简介本项目是一个单文件 (Single-File) 的 HTML 工具，旨在解决 Lunatv 与 TvBox 两大主流影视配置格式之间的互转难题。区别于传统的转换工具，本项目不仅在核心算法上实现了全能无条件深度提取，更在 UI/UX 上进行了革命性的升级，带来了媲美原生 iOS 应用的视觉与操作体验。3. 核心特性 (Features)📝 源码 (Source Code)## 🎨 核心特性

### 1. 视觉体验 (Visuals)
- **iOS 26 极光玻璃拟态**：采用 `backdrop-filter` 高斯模糊与高通透白/黑叠加，配合背景动态流动的极光光球 (`Ambient Light`)，营造深邃的空间感。
- **自适应深浅模式**：
  - 🌞 **Day Mode**：定制的 `#EAF3F7` 莫兰迪云水蓝背景，配合晶莹剔透的磨砂面板与高对比度深岩灰文字。
  - 🌙 **Night Mode**：深邃的黑夜模式，光球更加耀眼，面板呈现为悬浮的暗色玻璃。

### 2. 强大的双向转换 (Dual-Core Conversion)
- **Mode A: Lunatv ➜ TvBox**
  - 标准化转换，自动匹配分类。
  - 智能补全 TvBox 所需的 `searchable` 等字段。
- **Mode B: TvBox ➜ Lunatv (全能还原)**
  - **无条件深度提取**：内置“贪吃蛇”递归算法，无视 TvBox 复杂的 JSON 嵌套结构。
  - **智能清洗**：自动去除 API 地址中冗余的后缀。
  - **零报错机制**：即使 JSON 格式损坏，也会尝试正则暴力提取。
👁️ 渲染预览 (Rendered Preview)🎨 核心特性1. 视觉体验 (Visuals)iOS 26 极光玻璃拟态：采用 backdrop-filter 高斯模糊与高通透白/黑叠加，配合背景动态流动的极光光球 (Ambient Light)，营造深邃的空间感。自适应深浅模式：🌞 Day Mode：定制的 #EAF3F7 莫兰迪云水蓝背景，配合晶莹剔透的磨砂面板与高对比度深岩灰文字。🌙 Night Mode：深邃的黑夜模式，光球更加耀眼，面板呈现为悬浮的暗色玻璃。2. 强大的双向转换 (Dual-Core Conversion)Mode A: Lunatv ➜ TvBox标准化转换，自动匹配分类。智能补全 TvBox 所需的 searchable 等字段。Mode B: TvBox ➜ Lunatv (全能还原)无条件深度提取：内置“贪吃蛇”递归算法，无视 TvBox 复杂的 JSON 嵌套结构。智能清洗：自动去除 API 地址中冗余的后缀。零报错机制：即使 JSON 格式损坏，也会尝试正则暴力提取。4. 技术栈 (Tech Stack)📝 源码 (Source Code)## 🛠️ 技术栈 (Tech Stack)

本项目无需后端，纯前端实现，所有依赖通过 CDN 引入，**开箱即用**。

- **Core**: HTML5, Vanilla JavaScript (ES6+)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Animation**: [SortableJS](https://sortablejs.github.io/Sortable/)
- **Fonts**: Google Fonts (SF Pro Display, JetBrains Mono)
👁️ 渲染预览 (Rendered Preview)🛠️ 技术栈 (Tech Stack)本项目无需后端，纯前端实现，所有依赖通过 CDN 引入，开箱即用。Core: HTML5, Vanilla JavaScript (ES6+)Styling: Tailwind CSSAnimation: SortableJSFonts: Google Fonts (SF Pro Display, JetBrains Mono)5. 如何使用 (Usage)📝 源码 (Source Code)## 🚀 如何使用 (Usage)

1. **下载**：下载本项目中的 `Lunatv2Tvbox_iOS26.html` 文件。
2. **运行**：直接使用 Chrome, Edge, Safari 或任意现代浏览器打开该文件。
3. **操作**：
   - 点击顶部的胶囊开关切换转换模式。
   - 拖拽文件或粘贴代码到输入框。
   - 点击“开始转换”。
👁️ 渲染预览 (Rendered Preview)🚀 如何使用 (Usage)下载：下载本项目中的 Lunatv2Tvbox_iOS26.html 文件。运行：直接使用 Chrome, Edge, Safari 或任意现代浏览器打开该文件。操作：点击顶部的胶囊开关切换转换模式。拖拽文件或粘贴代码到输入框。点击“开始转换”。6. 共创声明 (Footer)📝 源码 (Source Code)## 🤝 共同创造 (Co-Creation)

本项目由 **Human** 与 **Gemini AI** 共同创造。

- **遵循规则**：[2025.12.9 共创协议]
- **版本**：v1.0.0 (iOS 26 Concept)

---
*Designed with ❤️ for better streaming experience.*
👁️ 渲染预览 (Rendered Preview)🤝 共同创造 (Co-Creation)本项目由 Human 与 Gemini AI 共同创造。遵循规则：[2025.12.9 共创协议]版本：v1.0.0 (iOS 26 Concept)Designed with ❤️ for better streaming experience.
