# awesome-copilot

> A curated list of awesome GitHub Copilot instructions, prompts, agents, and extensions.

[![All Contributors](https://img.shields.io/github/all-contributors/awesome-copilot/awesome-copilot?color=ee8449&style=flat-square)](https://github.com/awesome-copilot/awesome-copilot/graphs/contributors)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat-square)](LICENSE)

A community-driven collection of GitHub Copilot resources including custom instructions, prompt files, agent workflows, and VS Code extensions to supercharge your AI-assisted development experience.

> **Personal fork note:** I'm using this as a reference while learning Copilot customization. Entries marked with ⭐ are ones I've personally tried and found useful.

---

## 📖 Contents

- [Custom Instructions](#-custom-instructions)
- [Prompt Files](#-prompt-files)
- [Agent Workflows](#-agent-workflows)
- [VS Code Extensions](#-vs-code-extensions)
- [MCP Servers](#-mcp-servers)
- [Tutorials & Articles](#-tutorials--articles)
- [My Notes](#-my-notes)
- [Contributing](#-contributing)
- [Contributors](#-contributors)

---

## 🧠 Custom Instructions

Custom instructions help shape how GitHub Copilot responds to your requests. Place these in `.github/copilot-instructions.md` in your repository.

| Name | Description | Author |
|------|-------------|--------|
| [General Best Practices](.github/copilot-instructions.md) | General coding best practices and style guidelines | Community |

---

## 📝 Prompt Files

Reusable `.prompt.md` files for common development tasks.

| Name | Description | Category |
|------|-------------|----------|
| [Agentic Workflows](.github/agents/agentic-workflows.agent.md) | Agent workflow definitions for complex multi-step tasks | Agents |

---

## 🤖 Agent Workflows

Pre-built agentic workflows for common development scenarios.

| Name | Description | Use Case |
|------|-------------|----------|
| [Agentic Workflows](.github/agents/agentic-workflows.agent.md) | Comprehensive agent definitions for development tasks | General Development |

---

## 🧩 VS Code Extensions

Extensions that enhance your GitHub Copilot experience.

See the full marketplace listing in [`.github/plugin/marketplace.json`](.github/plugin/marketplace.json).

---

## 🔌 MCP Servers

Model Context Protocol servers that extend Copilot's capabilities.

> More entries coming soon! [Contribute yours](#-contributing).

---

## 📚 Tutorials & Articles

- [GitHub Copilot Documentation](https://docs.github.com/en/copilot) — Official GitHub Copilot docs
- [Customizing GitHub Copilot](https://docs.github.com/en/copilot/customizing-copilot) — Guide to custom instructions and prompt files
- [GitHub Copilot for VS Code](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) — VS Code marketplace listing

---

## 🗒️ My Notes

<!-- Personal notes on things I've tried or want to explore -->

- Started exploring custom instructions for Go projects — the key is keeping them concise and focused on one concern per instruction file.
- TODO: try out the agentic workflow for code review automation
- The MCP servers section looks promising; want to experiment with the filesystem and GitHub MCP servers together.
