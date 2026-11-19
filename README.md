# AA农场｜让 AI 带着可核验的文件回来

AA农场是面向 macOS 的 AI 工作台：把任务要求、真实产出和验收证据放在一起，交付后由你审阅。

## 当前公开版本

**[前往官网下载 AA农场 v0.3.0](https://aa-farm.pages.dev/download?utm_source=github&utm_medium=repo&utm_campaign=v0.3.0)** · [GitHub Releases](https://github.com/MarcelLeon/aa-farm-support/releases/latest)

应用版本为 **v0.3.0**。安装包为 Universal（Apple Silicon / Intel），经过 Developer ID 签名及 Apple 公证；系统要求 macOS 13 或更新版本。Intel 实机运行仍欢迎反馈。

**官网更新（2026-11-19）**：统一 AF 品牌标志、适配导航栏，并将标志入场动画设为仅在刷新页面时播放；首次打开、站内跳转及前进后退保持静态，开启“减少动态效果”时不播放。这次是网站更新，应用版本仍为 v0.3.0。

- [访问官网](https://aa-farm.pages.dev/?utm_source=github&utm_medium=repo&utm_campaign=site-refresh-20261119)
- [查看本次网站部署](https://be5e6c73.aa-farm.pages.dev/)
- [个人助理与交付样例](https://aa-farm.pages.dev/personal-agent)
- [使用指南与常见问题](https://aa-farm.pages.dev/support)

## 选择你的第一份任务

### 个人助理：从资料到交付文件

先准备支持工具调用的本地模型服务，再选择资料目录，约定输出文件和验收条件。此入口不要求 Git 项目或 Codex 登录。

v0.3.0 的文件资料入口支持 UTF-8 普通文本和 JSON，尚不直接读取 PDF、图片或 Office 文件。资料变动后，旧证据不再适用于新合同；宿主读取实际交付文件并按约定核验，最终仍需人工审阅。

官网的报销样例使用合成票据：原合计 225 元，新增 5 元停车费后为 230 元。这是特定条件下的已验证样例，不是对所有任务的准确率承诺。

### 编程农场：把任务种进 Git 项目

1. 安装 AA农场，准备一个已有提交的 Git 项目。
2. 使用已安装并登录的 Codex CLI，或配置兼容的本地模型服务。
3. 选择 Bug 修复、测试补全、功能开发、代码审查、文档整理或 CI 维护任务，并明确写入范围和验收条件。
4. Agent 在隔离 worktree 中工作；完成后查看实际文件、diff 和验收证据，再决定是否收获。

AA农场不售卖模型额度。Codex 路线会按你的 Codex 配置将必要任务上下文发送给服务提供方；本地模型路线由配置的本地服务执行。详情见[隐私说明](https://aa-farm.pages.dev/privacy)。

## 获取帮助

- [报告可以复现的问题](https://github.com/MarcelLeon/aa-farm-support/issues/new/choose)
- [提交第一次收成反馈](https://github.com/MarcelLeon/aa-farm-support/issues/new?template=first-harvest.yml)
- [查看已知问题](https://github.com/MarcelLeon/aa-farm-support/issues)
- [阅读使用与常见问题](https://aa-farm.pages.dev/support)
- [阅读隐私说明](https://aa-farm.pages.dev/privacy)

提交前请移除 API Key、私有代码、个人文件路径、仓库名称和其他敏感信息。

## 支持边界

这个 Public 仓库承载 Issues、FAQ、隐私说明和安装包，不包含 AA农场应用源码。应用源码与构建凭证保存在独立 Private 仓库。

安全问题请使用 GitHub 的 [Private vulnerability reporting](https://github.com/MarcelLeon/aa-farm-support/security/advisories/new)，避免在公开 Issue 中披露。

