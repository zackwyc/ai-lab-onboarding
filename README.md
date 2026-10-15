# AI-Lab 新进成员准入考核交付

作者：zackwyc
系统：Windows

## Task 01 现代 AI 编程环境与 CLI 协同工具

### 三件套对应情况
1. AI IDE / 工作台：Trae
2. 终端 AI Agent：OpenCode
3. 大模型 API：SiliconFlow / DeepSeek

### 环境配置步骤
1. 安装 Node.js LTS，终端执行 `node -v` 确认成功
2. 安装 OpenCode：`npm i -g opencode-ai`
3. 到 SiliconFlow 或 DeepSeek 开放平台创建 API Key
4. 设置环境变量（PowerShell）：
   - `$env:OPENAI_API_KEY="sk-你的key"`
   - `$env:OPENAI_BASE_URL="https://api.deepseek.com/v1"`
5. 在项目目录运行 `opencode` 启动工具

### 交互过程
在终端让 OpenCode 解释一段 Python 脚本、指出潜在 Bug 并给出优化建议，
随后让它写了一个批量重命名文件的脚本，输出正常。

### 截图
- IDE / 工作台界面：屏幕截图 2026-10-14 115641.png
- 终端成功交互：屏幕截图 2026-10-14 182722.png

### 踩坑记录
- 一开始鉴权失败，原因是 BASE_URL 写错，改成官方地址后正常。
- API Key 不要提交到仓库，写在 .env 并加入 .gitignore。

## Task 02 Markdown 笔记库
使用 Obsidian（或 VSCode + Markdown All in One）。
目录结构：
- 环境配置/
- 排错记录/
- 代码实验/
- 文献技术摘记/
已练习语法：多级标题、列表、表格、代码块高亮、超链接、本地与网络图片引用、LaTeX 公式 `$E=mc^2$`。
- 我说明一下,我这边还是未成年,API需要成年人才有权限用,我用我父母的后需要人脸,也跟着deepseek进行了很多流程来解决,来来回回有十几遍,最后实在没办法了所以只能提交这个了,希望理解一下
