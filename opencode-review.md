# OpenCode：开源 AI 编程助手的新选择

最近开源社区出了一个很有意思的项目，叫 OpenCode。

简单来说，它就是一个开源版的 Claude Code。功能上几乎一样强大，但核心区别在于——它不绑定任何一家 AI 厂商。

## 为什么值得关注

很多人用过 Claude Code，体验确实不错。但问题是，它只能用 Anthropic 的模型。

OpenCode 不一样。你可以接 Claude，可以接 OpenAI，可以接 Google，甚至可以跑本地模型。这个灵活性就很重要了。

为什么？因为 AI 模型这个领域变化太快。今天 Claude 最强，明天可能 GPT-5 出来又不一样了。价格也在不断往下走。你不想被锁死在某一家厂商上面。

OpenCode 给了你选择的自由。

## 它能干什么

说白了，就是一个终端里的 AI 编程助手。

它有两个内置的 Agent。一个叫 build，权限全开，帮你写代码、改文件、跑命令。另一个叫 plan，只读模式，专门用来分析代码、规划方案，不会乱动你的文件。

按 Tab 键就能切换，设计得很巧妙。

还有一点很实用：它支持客户端/服务端架构。什么意思？你可以在电脑上跑 OpenCode，然后用手机远程控制它。这个场景想象空间就大了。

## 安装方式

安装非常简单，一行命令搞定：

```bash
curl -fsSL https://opencode.ai/install | bash
```

或者用包管理器：

```bash
npm i -g opencode-ai@latest   # npm
brew install opencode          # macOS/Linux
scoop install opencode         # Windows
```

它还有桌面版，macOS、Windows、Linux 都支持。不喜欢命令行的，可以直接下载桌面应用。

## 我的看法

OpenCode 代表了一个趋势：AI 工具正在走向开源和去中心化。

以前我们用这些工具，只能接受厂商给什么就用什么。现在不一样了，社区在主动掌握选择权。

这个项目的开发者是 neovim 用户，还做过 terminal.shop。可以看出来，他们对终端体验有很深的执念。这种专注是好事。

如果你在找一个不绑定厂商、功能够用、开源透明的 AI 编程助手，OpenCode 值得试试。
