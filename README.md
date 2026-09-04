# AA农场｜把工作种下去，等 AI 农夫带着收成回来

AA农场把日常工作变成六种任务种子，让本机的 AI Agent 在隔离 worktree 中工作，并带着真实文件、代码差异、验收结果和必要截图回来。

它借用了 QQ 农场“播种—等待—收菜”的直觉，但种下去的不再是萝卜：可以是 Bug 修复、测试补全、功能开发、代码审查、文档整理或 CI 维护。

## 下载 macOS 版

**[前往官网下载 AA农场 v0.1.1](https://aa-farm.pages.dev/download?utm_source=github&utm_medium=repo&utm_campaign=v0.1.1)**

安装包同时支持 Apple Silicon 与 Intel Mac，经过 Developer ID 签名及 Apple 公证。也可以直接查看 [GitHub Releases](https://github.com/MarcelLeon/aa-farm-support/releases/latest)。

### 第一次播种

1. 下载 DMG，把 AA农场拖入“应用程序”。
2. 用 Finder 选择一个已有提交的 Git 项目，不需要手写绝对路径。
3. 从六种种子中选择一颗，说明你希望得到什么结果。
4. 默认只允许农夫写入项目根目录；需要缩小范围时，从项目内选择目录。
5. 等任务完成后，在“收成仓库”查看真实产出、diff、验收证据和截图，再决定是否收获。

系统要求：macOS 13 或更新版本。开始前需要已登录的 Codex CLI；也可以配置支持工具调用的 Ollama 或兼容模型服务。

> AA农场不售卖模型额度，也不会要求你把项目代码上传到 AA农场服务器。任务仍由你本机已有的 Agent 账号或本地模型执行。

## 获取帮助

- [报告可以复现的问题](https://github.com/MarcelLeon/aa-farm-support/issues/new/choose)
- [查看已知问题](https://github.com/MarcelLeon/aa-farm-support/issues)
- [阅读使用与常见问题](https://aa-farm.pages.dev/support)
- [阅读隐私说明](https://aa-farm.pages.dev/privacy)

提交前请移除 API Key、私有代码、个人文件路径、仓库名称和其他敏感信息。

## 支持边界

这个 Public 仓库只承载 Issues、FAQ、隐私说明和安装包，不包含 AA农场应用源码。应用源码与构建凭证保存在独立 Private 仓库。

安全问题不要发到公开 Issue，请使用 GitHub 的 [Private vulnerability reporting](https://github.com/MarcelLeon/aa-farm-support/security/advisories/new)。
