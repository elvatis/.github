# Elvatis

IT klar gedacht. Building open-source tooling for AI-native infrastructure and developer workflows.

## About

Elvatis is an independent software company based in Munich, Germany. We focus on practical AI integration, infrastructure automation, and developer tooling built for real-world use. Our open-source work revolves around the [OpenClaw](https://github.com/elvatis/openclaw-ispconfig) ecosystem: a plugin-based AI gateway that connects LLMs to your systems through natural language.

We write about what we build. No hype, no vendor lock-in. Just clear thinking on AI, security, and operations.

## What We Build

### AI Gateway and Orchestration

| Repo | Description |
|------|-------------|
| [openclaw-model-orchestrator](https://github.com/elvatis/openclaw-model-orchestrator) | Multi-model routing and orchestration across AI providers |
| [openclaw-cli-bridge-elvatis](https://github.com/elvatis/openclaw-cli-bridge-elvatis) | Bridge Codex, Gemini, and Claude Code CLIs as model providers |
| [agent-backends](https://github.com/elvatis/agent-backends) | Shared abstraction layer for CLI-based AI agent spawning |
| [conduit-bridge](https://github.com/elvatis/conduit-bridge) | Standalone OpenAI-compatible proxy for Grok, Claude, Gemini, ChatGPT |
| [conduit-vscode](https://github.com/elvatis/conduit-vscode) | VS Code extension: AI chat, inline edit, agent sessions, cost tracking |

### OpenClaw Plugins

| Repo | Description |
|------|-------------|
| [openclaw-memory-brain](https://github.com/elvatis/openclaw-memory-brain) | Auto-capture and recall personal memories and preferences |
| [openclaw-memory-docs](https://github.com/elvatis/openclaw-memory-docs) | Store and recall technical documentation and knowledge |
| [openclaw-memory-core](https://github.com/elvatis/openclaw-memory-core) | Shared library: vector store, embedding logic, JSONL persistence |
| [openclaw-docker](https://github.com/elvatis/openclaw-docker) | Manage Docker containers, logs, and Compose stacks via natural language |
| [openclaw-ispconfig](https://github.com/elvatis/openclaw-ispconfig) | Manage ISPConfig hosting, sites, DNS, mail, and databases |
| [openclaw-homeassistant](https://github.com/elvatis/openclaw-homeassistant) | Control Home Assistant entities and scenes via natural language |
| [openclaw-rss-feeds](https://github.com/elvatis/openclaw-rss-feeds) | Fetch RSS feeds, enrich with CVE data, publish digests to Ghost CMS |
| [openclaw-gpu-bridge](https://github.com/elvatis/openclaw-gpu-bridge) | Offload heavy compute (embeddings, BERTScore) to a remote GPU server |
| [openclaw-inwx](https://github.com/elvatis/openclaw-inwx) | Manage INWX domains and DNS records via natural language |
| [openclaw-ops-elvatis](https://github.com/elvatis/openclaw-ops-elvatis) | Operational automation for infrastructure monitoring and maintenance |
| [openclaw-self-healing-elvatis](https://github.com/elvatis/openclaw-self-healing-elvatis) | Self-healing guardrails and auto-fix for reversible failures |
| [openclaw-todo](https://github.com/elvatis/openclaw-todo) | Manage TODOs in markdown files with natural language |

### Developer CLI Tools

| Repo | Description |
|------|-------------|
| [commitprompt](https://github.com/elvatis/commitprompt) | AI-generated git commit messages from staged diffs |
| [failprompt](https://github.com/elvatis/failprompt) | Structured error reporting and AI-assisted debugging |
| [clawhub-scanner](https://github.com/elvatis/clawhub-scanner) | Scanner and validator for ClawHub skill packages |

## Blog

Technical writing at [blog.elvatis.com](https://blog.elvatis.com) covering:

- **AI Security** - supply chain threats, LLM attack surfaces, practical hardening
- **Infrastructure Automation** - self-healing systems, operational tooling, monitoring
- **AI Agent Architecture** - multi-model orchestration, autonomous workflows, AAHP protocol
- **Developer Tooling** - VS Code integrations, CLI utilities, AI-assisted development
- **NIS2 and Compliance** - practical guidance for mid-sized companies

Recent posts include: NIS2 compliance checklists, supply chain malware analysis across GitHub/npm/VS Code, autonomous agent workflows, and building a 49-LLM unified gateway.

## Contact

- Website: [elvatis.com](https://elvatis.com)
- Blog: [blog.elvatis.com](https://blog.elvatis.com)
- Email: emre.kohler@elvatis.com
- Location: Munich, Germany
