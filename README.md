# DeepSeek Note Helper



---

## 中文版

### 🚀 简介
**DeepSeek Note Helper** 是一个为 Obsidian 打造的**智能代理工作流引擎 (Agentic Workflow Engine)**。它将 AI 的深度逻辑推理与 Obsidian 的白板（Canvas）空间管理完美结合，让您的笔记库真正进化为“第二大脑”。

### 🌟 核心功能 (v2.5.6)

1.  **Canvas Flow (可视化 AI 工作流)**：
    *   在白板上通过标签（如 `#ds/input`, `#ds/step`）构建 AI 执行管道。
    *   支持并行任务处理与自动化结果生成。
2.  **Note to Canvas (笔记转白板)**：
    *   一键将长篇 Markdown 笔记转化为可视化的思维导图布局。
    *   支持**本地结构解析**（极速）与 **AI 语义重组**（深度理解）。
3.  **万能 AI 助手**：
    *   支持侧边栏对话、全库搜索 (RAG)、斜杠命令 (`/ds`) 原地润色。
    *   自动管理 YAML 属性与双向链接。

### 🛠️ 安装方法

由于本项目为**二进制分发版本**，您可以通过以下任一方式安装：

#### 方式 A：手动安装 (推荐)
1.  下载最新的 [Release 包](https://github.com/leoyang1984/obsidian-deepseek-note-helper/releases)。
2.  在您的 Obsidian 库中打开 `.obsidian/plugins/` 目录。
3.  在该目录下创建一个文件夹名为 `obsidian-deepseek-note-helper`。
4.  将解压后的 `main.js`, `manifest.json`, `styles.css` 放入该文件夹。
5.  在 Obsidian 设置 -> “第三方插件”中启用本插件。

#### 方式 B：通过 Obsidian BRAT 安装
1.  安装并启用 [Obsidian BRAT](https://github.com/TfTHacker/obsidian42-brat) 插件。
2.  在 BRAT 设置中添加本仓库的 GitHub 链接。

### ⚖️ 知识产权与授权
本项目受 **自定义商业禁用协议** 保护。严禁任何形式的商业行为、商业性抄袭或未经授权的分发。详情请参阅 `COMMERCIAL_LICENSE.md`。

---

## English Version

### 🚀 Introduction
**DeepSeek Note Helper** is an **Agentic Workflow Engine** for Obsidian. It seamlessly integrates AI logical reasoning with Obsidian Canvas spatial management, evolving your vault into a living "Second Brain".

### 🌟 Core Features (v2.5.6)

1.  **Canvas Flow (Visual AI Workflow)**:
    *   Build AI execution pipelines directly on Canvas using tags like `#ds/input` and `#ds/step`.
    *   Supports parallel branch processing and automatic result synthesis.
2.  **Note to Canvas (Whiteboard Generator)**:
    *   Instant transformation of long Markdown notes into a visual spatial topography.
    *   Dual modes: **Local Parsing** (instant structure) and **AI Recomposition** (semantic understanding).
3.  **Universal AI Assistant**:
    *   Native Sidebar Chat, Vault-wide search (RAG), and in-place Slash Commands (`/ds`).
    *   Automated metadata (YAML) management and link resolution.

### 🛠️ Installation

This is a **binary-only distribution**. You can install it using one of the following methods:

#### Method A: Manual Installation (Recommended)
1.  Download the latest [Release package](https://github.com/leoyang1984/obsidian-deepseek-note-helper/releases).
2.  Open your vault's `.obsidian/plugins/` directory.
3.  Create a folder named `obsidian-deepseek-note-helper`.
4.  Place `main.js`, `manifest.json`, and `styles.css` into that folder.
5.  Enable the plugin in Obsidian Settings -> Community Plugins.

#### Method B: Obsidian BRAT
1.  Install and enable the [Obsidian BRAT](https://github.com/TfTHacker/obsidian42-brat) plugin.
2.  Add this repository's GitHub URL in BRAT settings.

### ⚖️ License
This project is protected under a **Custom Non-Commercial License**. Commercial use, unauthorized redistribution, and plagiarism for profit are strictly prohibited. See `COMMERCIAL_LICENSE.md` for full terms.
