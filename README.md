[![MseeP.ai Security Assessment Badge](https://mseep.net/pr/nowledge-co-nowledge-mem-badge.png)](https://mseep.ai/app/nowledge-co-nowledge-mem)

# Nowledge Mem

<div align="center">

<img src="https://github.com/user-attachments/assets/249e8b3e-54a2-49eb-b28a-07c2cfaf2236" width="200" alt="Nowledge Mem Logo">

**The Context Manager just works, build your Knowledge Flywheel**

**Privacy-first. Graph-native. AI-integrated.**

[![Get Mem](https://img.shields.io/badge/Get-Mem-00A3A3?style=flat&logo=rocket&logoColor=white)](https://mem.nowledge.co/)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=flat&logo=discord&logoColor=white)](https://nowled.ge/discord)
[![Docs](https://img.shields.io/badge/Docs-Read-orange?style=flat&logo=readthedocs&logoColor=white)](https://nowled.ge/mem-docs)

---

</div>

[Nowledge Mem](https://mem.nowledge.co/) is the **local-first, graph-augmented personal context manager** that preserves conversations and insights from your AI interactions. Stop opening 5 AI apps to find *that one conversation*. Type → found.

Mem can persist entire conversation threads across all your AI tools while also distilling key insights into searchable memories. Everything connected through an intelligent knowledge graph.

#### Ways to Use Mem

##### Capture Knowledge

- **🤖 MCP Integration** | Works with [Claude Code](https://github.com/nowledge-co/community/tree/main/nowledge-mem-claude-code-plugin), [Claude Desktop](https://github.com/nowledge-co/claude-dxt), [Cursor](https://mem.nowledge.co/docs/integrations), Github Copilot, Gemini CLI, Qwen Code & more, [ref config](./mcp.json)
- **🌐 Browser Extension** | One-click imports from ChatGPT, Claude, Gemini, Perplexity (Chrome, Firefox, Edge, Arc)
- **📂 Thread Import** | Upload conversation files from Cursor, ChatWise, Markdown exports or Claude Code/Codex command

> [!NOTE]
> General MCP Configuration:

```json
{
  "mcpServers": {
    "nowledge-mem": {
      "url": "http://localhost:14242/mcp",
      "type": "streamableHttp",
      "headers": {
        "APP": "<MCP Client App Name here>"
      }
    }
  }
}
```

##### Access Your Knowledge

- **⌨️ Global Launcher (⌘⇧K)** | Paste memories anywhere without leaving your workflow
- **🔍 In-App Search** | Deep exploration with semantic search, keywords, and graph navigation
- **🤝 Agent Access** | Let AI agents autonomously search and save memories during tasks

##### Advanced Features

- **🕸️ Knowledge Graph** | Auto-extract entities and relationships for semantic connections
- **🎯 Topic Clustering** | Discover natural groupings and expertise areas via graph algorithms
- **📊 Visual Exploration** | Interactive graph view to explore connections and patterns


## 🚀 Quick Links

- 📚 **[Documentation](https://mem.nowledge.co/docs)** | Learn how to use Nowledge Mem
- 📖 **[Blog Post](https://www.nowledge-labs.ai/blog/nowledge-mem)** | Deep dive into our vision
- 🔌 **Claude Code Plugin** | Install via marketplace:

  ```bash
  claude plugin marketplace add nowledge-co/community
  claude plugin install nowledge-mem@nowledge-community
  ```

- 🐛 **[Report Bug](https://github.com/nowledge-co/community/issues/new?template=bug_report.md)** | Found an issue? Let us know
- 💡 **[Request Feature](https://github.com/nowledge-co/community/issues/new?template=feature_request.md)** | Share your ideas
- 💌 **[Send Feedback](mailto:hello@nowledge-labs.ai)** | We'd love to hear from you


---

<div align="center">

**Built with ❤️ by [Nowledge Labs](https://nowledge-labs.ai)**

</div>
