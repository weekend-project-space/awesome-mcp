
# awesome-mcp

Awesome Model Context Protocol Resource List

## ZH (中文)

### 什么是MCP?

MCP（模型上下文协议，Model Context Protocol）是一种为 AI Agent 的 LLM（大型语言模型）与第三方应用之间提供通信、共享信息的开放协议。它的开放性意味着任何人都可以基于 MCP 构建自己的第三方应用，扩展 AI 的能力边界。

### AI Agent 是什么？

我们可以这样简单理解 AI Agent 的工作流程：
```
构建提示词（上下文内嵌）=> llm => 得到执行的命令 => 执行 => 反馈调整新的提示词
```

MCP 的作用在于优化这一流程，让 LLM 能够更高效地与外部工具和数据交互。

### 官方怎么定义 MCP 的

根据 Anthropic 的官方描述，MCP 是一个开源标准，旨在解决 AI 系统与外部工具和数据源连接的复杂性问题。它通过提供一个统一的协议，让大型语言模型（LLM）能够轻松访问和管理多样化的外部资源，例如数据库、应用程序或开发环境，从而提升 AI 的上下文理解能力和实用性。

[介绍模型上下文协议](https://www.anthropic.com/news/model-context-protocol)

### 如何使用

想快速上手 MCP？官方提供了详细的文档和 SDK 支持，开发者可以通过以下资源开始构建自己的 MCP 应用：

- [MCP 文档](https://modelcontextprotocol.io/introduction)  
- [Python SDK](https://github.com/anthropic/model-context-protocol-python)  
- [TypeScript SDK](https://github.com/anthropic/model-context-protocol-typescript)

## MCP 相关资源链接

以下是一些实用的资源，帮助你深入了解和使用 MCP：

### 官方资源
- [MCP GitHub 主仓库](https://github.com/anthropic/model-context-protocol) - MCP 的核心代码和贡献指南  
- [Anthropic 博客](https://www.anthropic.com/blog) - 了解 MCP 的最新动态和开发故事  
