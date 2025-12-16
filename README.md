# 🌌 Lunatv / TvBox Interface Converter

> 一个极具未来感、流畅且强大的影视接口配置转换工具。
> 
> **设计理念**：概念设计 | 极光玻璃拟态 | 物理级丝滑交互

## 1. 项目简介 (Introduction)

本项目是一个**单文件 (Single-File)** 的 HTML 工具，旨在解决 Lunatv 与 TvBox 两大主流影视配置格式之间的互转难题。

区别于传统的转换工具，本项目不仅在核心算法上实现了**全能无条件深度提取**，更在 UI/UX 上进行了革命性的升级，带来了媲美原生 iOS 应用的视觉与操作体验。

## 2. 核心特性 (Features)

### 2.1 视觉体验 (Visuals)
- **iOS 26 极光玻璃拟态**：采用 `backdrop-filter` 高斯模糊与高通透白/黑叠加，配合背景动态流动的极光光球 (`Ambient Light`)，营造深邃的空间感。
- **自适应深浅模式**：
  - 🌞 **Day Mode**：定制的 `#EAF3F7` 莫兰迪云水蓝背景，配合晶莹剔透的磨砂面板与高对比度深岩灰文字。
  - 🌙 **Night Mode**：深邃的黑夜模式，光球更加耀眼，面板呈现为悬浮的暗色玻璃。
- **微交互**：所有按钮支持 iOS 风格的缩放回弹，Toast 通知采用优雅的顶部滑入动画。

### 2.2 强大的双向转换 (Dual-Core Conversion)
- **Mode A: Lunatv ➜ TvBox**
  - 标准化转换，自动匹配分类。
  - 智能补全 TvBox 所需的 `searchable`, `quickSearch` 等字段。
- **Mode B: TvBox ➜ Lunatv (全能还原)**
  - **无条件深度提取**：内置“贪吃蛇”递归算法，无视 TvBox 复杂的 JSON 嵌套结构（无论是 `urls`, `data`, `sites` 还是纯数组），只要包含数据，统统自动识别。
  - **智能清洗**：自动去除 API 地址中冗余的后缀（如 `ac=list`），还原最纯净的源地址。
  - **零报错机制**：即使 JSON 格式损坏，也会尝试正则暴力提取，绝不弹窗报错，保证用户体验。

### 2.3 生产力工具 (Productivity)
- **SortableJS 驱动的分类管理**：支持物理级丝滑的拖拽排序，手机/电脑端均有完美的触感反馈。
- **专业编辑器体验**：
  - **文件导入**：支持直接读取本地 `.json` / `.txt` 文件。
  - **窗口自由拖拽**：输入/输出框高度可自由调整 (`resize-y`)。
  - **批量替换**：内置查找替换工具栏，方便批量修改域名或 IP。
  - **代码字体**：集成 `JetBrains Mono`，让配置代码清晰易读。

## 3. 技术栈 (Tech Stack)

本项目无需后端，纯前端实现，所有依赖通过 CDN 引入，**开箱即用**。

- **Core**: HTML5, Vanilla JavaScript (ES6+)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (Utility-first CSS)
- **Icons**: [Font Awesome 6](https://fontawesome.com/)
- **Animation**: [SortableJS](https://sortablejs.github.io/Sortable/) (Drag & Drop)
- **Fonts**: Google Fonts (SF Pro Display, JetBrains Mono)

## 4. 如何使用 (Usage)

1. **下载**：下载本项目中的 `Lunatv2Tvbox.html` 文件。
2. **运行**：直接使用 Chrome, Edge, Safari 或任意现代浏览器打开该文件。
3. **操作**：
   - 点击顶部的胶囊开关切换转换模式。
   - 拖拽文件或粘贴代码到输入框。
   - 点击“开始转换”。
   - 在输出框中预览、编辑、复制或下载结果。

## 5. 共同创造 (Co-Creation)

本项目由 **Human** 与 **Gemini AI** 共同创造。

- **遵循规则**：[2025.12.9 共创协议]
- **版本**：v1.0.0 (iOS 26 Concept)

---
*Designed with ❤️ for better streaming experience.*
