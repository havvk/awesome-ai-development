# 附录

本附录旨在提供一些补充信息、术语表或常用资源链接，以帮助读者更好地理解手册中的内容。

### 术语表 (Glossary)

*   **LLM (Large Language Model):** 大语言模型。指经过海量文本数据训练的、能够理解和生成自然语言的深度学习模型，是所有现代 AI Chat 工具的核心。

*   **Prompt:** 提示词。指向 AI 模型发出的指令或问题，是与 AI 交互的输入。

*   **Prompt Engineering:** 提示工程。研究如何设计和优化 Prompt，以引导 AI 模型产生更高质量、更相关输出的艺术和科学。

*   **上下文窗口 (Context Window):** 指 AI 模型在一次交互中能够处理和记忆的文本量（通常以 Token 计算）。更大的上下文窗口意味着模型可以理解更长的文档或更复杂的对话历史。

*   **Token:** 令牌。AI 模型处理文本的基本单位。一个 Token 可以是一个单词、一个词根或一个标点符号。例如，“Hello, world!” 可能会被分解为 4 个 Token: `Hello`, `,`, ` world`, `!`。

*   **微调 (Fine-tuning):** 在一个已经预训练好的通用大模型的基础上，使用一个更小、更专业的领域数据集对其进行额外训练，使模型在该领域的表现更好。

*   **RAG (Retrieval-Augmented Generation):** 检索增强生成。一种让 LLM 在回答问题前，先从一个外部知识库（如你的项目文档、数据库）中检索相关信息，然后结合检索到的信息来生成更准确回答的技术。

*   **代码坏味道 (Code Smell):** 代码中存在的某些模式，它们本身不一定是 Bug，但可能预示着深层次的设计问题，并可能在未来导致 Bug 或使代码难以维护。

*   **TDD (Test-Driven Development):** 测试驱动开发。一种先编写测试用例，再编写能让测试通过的代码的软件开发方法。

### 常用资源

*   **Hugging Face:** (https://huggingface.co/) - 全球最大的开源 AI 模型、数据集和工具的社区和平台。
*   **OpenAI Cookbook:** (https://github.com/openai/openai-cookbook) - OpenAI 官方提供的、关于如何高效使用其 API 的技巧和代码示例。

*(本页内容将持续更新...)*