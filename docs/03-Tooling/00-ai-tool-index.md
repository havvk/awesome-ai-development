# AI 工具索引

这个索引旨在提供一个快速查找和对比不同 AI 工具的参考。这些工具在软件开发生命周期的不同阶段各有侧重。

### 核心工具：聊天与 IDE 集成

这些是开发者日常使用最高频的工具。

| 工具 | 主要平台 | 核心优势 | 最佳应用场景 |
| :--- | :--- | :--- | :--- |
| **[GitHub Copilot](./../01-Foundations/01-ide-integration/00-vscode-copilot.md)** | VS Code, JetBrains | 上下文感知代码补全, `/fix`, `/tests` 命令 | 日常编码、快速修复、生成单元测试 |
| **[JetBrains AI Assistant](./../01-Foundations/01-ide-integration/01-jetbrains-ai-assistant.md)** | JetBrains IDEs | 深度代码理解, 智能提交信息, 安全的重构 | JetBrains 全家桶用户的无缝体验 |
| **[Cursor](./../01-Foundations/01-ide-integration/04-cursor.md)** | 独立编辑器 | AI 原生交互, `@` 引用代码, `Cmd+K` 智能编辑 | 通过自然语言进行大规模代码修改和重构 |
| **[Google Gemini](./../01-Foundations/00-ai-assistants/00-chat-tools.md)** | Web, API, CLI | 实时搜索集成, 多模态能力, 优秀的创造力 | 技术调研、学习新框架、需要最新信息的任务 |
| **[OpenAI ChatGPT-4](./../01-Foundations/00-ai-assistants/00-chat-tools.md)** | Web, API | 强大的逻辑推理, 高质量代码生成, 生态丰富 | 复杂算法实现、深入的 Bug 分析 |
| **[Anthropic Claude](./../01-Foundations/01-ide-integration/03-claude.md)** | Web, API | 超长上下文窗口, 文档和代码库分析 | 遗留代码理解、API 文档分析、跨文件重构 |
| **[Gemini CLI](./../01-Foundations/01-ide-integration/02-gemini-cli.md)** | 命令行 | 与 Shell 命令结合, 直接操作文件系统 | 终端内的错误排查、自动化脚本编写 |

### 专项工具：特定领域的 AI 助手

这些工具专注于解决某一特定问题，并将其做到极致。

| 工具 | 专注领域 | 核心功能 | 备注 |
| :--- | :--- | :--- | :--- |
| **v0.dev by Vercel** | UI 生成 | 通过自然语言描述生成 React + Tailwind CSS 界面 | 能快速生成高质量的前端组件原型 |
| **Phind** | AI 搜索引擎 | 专为开发者优化的搜索引擎，回答会附带代码示例和来源 | 相比通用搜索引擎，结果更贴近开发需求 |
| **Codeium** | 代码补全 | 提供免费的、可自托管的 AI 代码补全方案 | Copilot 的一个有力竞争者，尤其受个人和小型团队欢迎 |
| **Tabnine** | 代码补全 | 强调个性化和隐私，可在本地或 VPC 中运行模型 | 适合对代码隐私有严格要求的企业 |
| **Mutable.ai** | 代码重构与改进 | 专注于代码质量、测试覆盖率和文档生成的 AI 平台 | 帮助团队自动化代码库的现代化改造 |
| **Mintlify** | 文档生成 | “为懒人准备的文档”，能自动为代码库生成专业文档 | 极大简化了编写和维护技术文档的工作 |

---

*这个列表会随着 AI 工具的快速发展而持续更新。欢迎社区贡献，补充更多优秀的工具！*