# Hello-World

一个简单的 Hello World 入门项目。

## 使用方法

运行以下命令：

```bash
echo "Hello, World!"
```

## OpenCode vs Claude Code — 核心区别

| 维度 | **OpenCode** | **Claude Code** |
|------|-------------|----------------|
| **许可** | MIT 开源 | Anthropic 专有闭源 |
| **模型** | 75+ 提供商（Claude、GPT、Gemini、Ollama 本地模型等） | 仅 Claude 系列 |
| **价格** | 工具免费 + 自备 API Key | $20–200/月订阅 |
| **架构** | Client/Server + HTTP API，TUI 多面板界面 | 单体 CLI，终端聊天式 |
| **代理成功率** | ~74–76% | **~82%**（同模型下高出约 8 个百分点） |
| **任务速度** | 偏彻底（同任务 ~16 分钟） | 偏快速（同任务 ~9 分钟） |

### 各自独有优势

**Claude Code：**
- `/goal` 自主完成模式、检查点回滚（Esc 两次）
- Opus Thinking 深度推理、Vim 键绑定
- Hooks 自动化、Routines 定时任务
- MCP Tool Search（工具 token 用量降低 85%）

**OpenCode：**
- 多模型自由切换（同一会话中 Claude → Gemini → 本地模型）
- LSP 原生集成、Docker 会话隔离
- Ollama 本地模型（代码不离开机器，适合金融/医疗/国防合规场景）
- GitHub Actions 原生集成（`/opencode` 自动分类 Issue → 创建分支 → 修改 → 发 PR）

### 简单选择指南

- **开箱即用 + 最高成功率** → Claude Code
- **预算敏感 / 数据合规 / 多模型灵活** → OpenCode
- **最优策略**：日常用 OpenCode + 便宜模型，复杂问题切 Claude Code
