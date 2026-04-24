# Contributing to awesome-copilot

Thank you for your interest in contributing to **awesome-copilot**! This is a community-driven collection of GitHub Copilot instructions, prompts, agents, and workflows.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Adding a New Copilot Instruction](#adding-a-new-copilot-instruction)
- [Adding a New Agent](#adding-a-new-agent)
- [Adding a Plugin to the Marketplace](#adding-a-plugin-to-the-marketplace)
- [Submission Guidelines](#submission-guidelines)
- [Review Process](#review-process)

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/). By participating, you are expected to uphold this standard.

## How to Contribute

1. **Fork** this repository
2. **Clone** your fork locally
3. **Create a branch** for your contribution: `git checkout -b feat/my-new-instruction`
4. **Make your changes** following the guidelines below
5. **Commit** your changes with a descriptive message
6. **Push** to your fork and open a **Pull Request**

## Adding a New Copilot Instruction

Copilot instructions live in `.github/copilot-instructions.md` or as standalone `.instructions.md` files.

### Format

```markdown
---
title: "Your Instruction Title"
description: "A short description of what this instruction does"
category: "language|framework|workflow|general"
author: "your-github-username"
tags: ["tag1", "tag2"]
---

## Your Instruction Content

Write your Copilot instruction here...
```

### Quality Checklist

- [ ] Clear, concise title and description
- [ ] Tested with GitHub Copilot
- [ ] No sensitive data or credentials included
- [ ] Follows existing naming conventions
- [ ] Spell-checked (we use `codespell` — see `.codespellrc`)

## Adding a New Agent

Agent files live under `.github/agents/` and use the `.agent.md` extension.

```
.github/agents/your-agent-name.agent.md
```

Refer to `.github/agents/agentic-workflows.agent.md` for the expected structure and frontmatter format.

## Adding a Plugin to the Marketplace

The marketplace registry is at `.github/plugin/marketplace.json`.

Add your plugin entry following this schema:

```json
{
  "id": "unique-plugin-id",
  "name": "Plugin Display Name",
  "description": "What this plugin does",
  "author": "your-github-username",
  "category": "productivity|language|devops|testing",
  "url": "https://github.com/your-username/your-plugin",
  "tags": ["tag1", "tag2"],
  "version": "1.0.0"
}
```

## Submission Guidelines

- Keep PRs focused — one instruction, agent, or plugin per PR
- Use descriptive commit messages
- Update `.all-contributorsrc` if you are a first-time contributor (the bot will handle this automatically)
- Ensure your content passes the `codespell` check before submitting

## Review Process

All submissions are reviewed by maintainers. We aim to review PRs within **5 business days**. Feedback will be provided as PR comments.

Thank you for helping make **awesome-copilot** better for everyone! 🚀
