# 如何为本手册做出贡献

我们热烈欢迎并感谢每一位愿意为 `awesome-ai-development` 手册做出贡献的朋友！这是一个由社区驱动的项目，您的每一次贡献都能让它变得更好。

## 贡献方式

你可以通过多种方式为项目做出贡献，包括但不限于：

1. **修正错误：**
   * 修正拼写、语法或格式错误。
   * 修正事实性错误或过时的信息。
   * 修复损坏的链接。

2. **补充内容：**
   * 为你熟悉的 AI 工具添加新的章节或更详细的介绍。
   * 在现有章节中，补充新的使用技巧、代码示例或最佳实践。
   * 分享你在实际工作中应用 AI 的新场景和成功案例。

3. **提出建议：**
   * 通过创建 [Issue](https://github.com/your-username/awesome-ai-development/issues) 来提出你对改进手册内容或结构的建议。
   * 讨论某个工具的优缺点，或者提出一个值得被收录的新工具。

4. **翻译和本地化：**
   * 我们鼓励将本手册翻译成其他语言，让更多地区的开发者受益。

## 贡献流程

我们遵循标准的 GitHub Fork & Pull Request 工作流。

1. **Fork 仓库**
   点击仓库主页右上角的 "Fork" 按钮，将本仓库复刻到你自己的 GitHub 账户下。

2. **Clone 你的 Fork**
   将你复刻的仓库克隆到你的本地电脑：

   ```bash
   git clone https://github.com/YOUR-USERNAME/awesome-ai-development.git
   ```

3. **创建新分支**
   在进行任何修改之前，请务必创建一个新的分支。分支命名应能简要描述你的修改内容，例如 `fix/typo-in-readme` 或 `feat/add-new-tool-guide`。

   ```bash
   git checkout -b your-branch-name
   ```

4. **进行修改**
   在本地对相关文件进行修改和完善。

5. **在本地验证修改 (可选但推荐)**
   为了确保你的修改符合项目的格式规范，我们引入了 Markdown Linter。在提交前，请在项目根目录运行以下命令进行检查：

   ```bash
   # 安装 linter 工具
   pip install pymarkdownlnt

   # 扫描所有文档
   pymarkdown --config .pymarkdown.yml scan docs/**/*.md
   ```

   如果命令没有任何输出，说明检查通过。如果输出错误信息，请根据提示修复对应的文件。

6. **提交你的变更**
   编写清晰的提交信息，描述你所做的修改。

   ```bash
   git add .
   git commit -m "feat: Add guide for NewTool"
   ```

7. **推送到你的 Fork**
   将你的本地分支推送到你的 GitHub Fork。

   ```bash
   git push origin your-branch-name
   ```

8. **创建 Pull Request (PR)**
   回到你的 GitHub Fork 页面，你会看到一个提示，点击 "Compare & pull request" 按钮。填写 PR 的标题和描述，清晰地说明你的变更内容和原因，然后提交。

## 行为准则

我们希望为所有贡献者和用户创造一个友好、互相尊重、协作共赢的社区环境。请在参与贡献和讨论时，遵守我们的行为准则。

感谢你的时间和努力！
