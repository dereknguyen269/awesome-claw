# Awesome OpenClaw 🦞

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated list of awesome [OpenClaw](https://github.com/openclaw/openclaw)-related projects on GitHub — skills, lightweight alternatives, dashboards, deployment tools, and more.

OpenClaw (formerly Clawdbot / Moltbot) is an open-source, self-hosted personal AI assistant that connects to messaging platforms you already use. This list tracks the ecosystem that has grown around it.

> There are 4,400+ repositories tagged `#openclaw` on GitHub. This list highlights the most useful and notable ones.

## Contents

- [Official](#official)
- [Skills & Plugins](#skills--plugins)
- [Lightweight Alternatives & Forks](#lightweight-alternatives--forks)
- [Dashboards & UIs](#dashboards--uis)
- [Deployment & Infrastructure](#deployment--infrastructure)
- [Memory & Context](#memory--context)
- [Integrations & Extensions](#integrations--extensions)
- [Awesome Lists & Resources](#awesome-lists--resources)
- [Community](#community)

---

## Official

Core repositories maintained by the OpenClaw team.

* [openclaw/openclaw](https://github.com/openclaw/openclaw) - The main OpenClaw personal AI assistant. Any OS. Any platform. The lobster way. 🦞 (TypeScript)
* [openclaw/clawhub](https://github.com/openclaw/clawhub) - Official skill directory for OpenClaw (TypeScript)
* [openclaw/skills](https://github.com/openclaw/skills) - Archive of all skills published on ClawHub (Python)
* [openclaw/lobster](https://github.com/openclaw/lobster) - Lobster workflow shell — a typed, local-first macro engine for composable pipelines and safe automations (JavaScript)

## Skills & Plugins

Skill collections, individual skills, and plugin resources.

* [aaronjmars/soul.md](https://github.com/aaronjmars/soul.md) - Build a personality for your agent — let OpenClaw ingest your data and build your AI soul
* [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) - Skill library covering Polymarket, crypto trading, DeFi operations, and automation
* [FreedomIntelligence/OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) - The largest open-source medical AI skills library for OpenClaw 🦞
* [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - Agent skills for Obsidian — teach your agent to use Markdown, Bases, JSON Canvas, and the CLI
* [LeoYeAI/openclaw-master-skills](https://github.com/LeoYeAI/openclaw-master-skills) - Curated collection of 339+ best OpenClaw skills, weekly updated from ClawHub, GitHub & community
* [prompt-security/clawsec](https://github.com/prompt-security/clawsec) - Complete security skill suite — drift detection, live recommendations, automated audits, and skill integrity verification
* [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - 5,400+ skills filtered and categorized from the official OpenClaw Skills Registry

## Lightweight Alternatives & Forks

Projects inspired by OpenClaw, reimplemented for different constraints — minimal footprint, security-first, edge devices, or alternative languages.

* [agentscope-ai/CoPaw](https://github.com/agentscope-ai/CoPaw) - Personal AI assistant easy to install on your own machine or cloud, supports multiple chat apps with extensible capabilities (Python)
* [DenchHQ/ironclaw](https://github.com/DenchHQ/ironclaw) - Personal AI assistant with CRM workflow automation skills (TypeScript)
* [gavrielc/nanoclaw](https://github.com/gavrielc/nanoclaw) - Lightweight personal Claude assistant that runs in Apple containers, built to be understood and customized (TypeScript)
* [HKUDS/nanobot](https://github.com/HKUDS/nanobot) - The ultra-lightweight OpenClaw — full assistant in ~4,000 lines of Python (Python)
* [inngest/utah](https://github.com/inngest/utah) - An OpenClaw-like Inngest-powered personal agent (TypeScript)
* [jlia0/tinyclaw](https://github.com/jlia0/tinyclaw) - TinyClaw — a team of personal agents that collaborate with each other (Python)
* [memovai/mimiclaw](https://github.com/memovai/mimiclaw) - Run OpenClaw on a $5 chip — no OS, no Node.js, no Mac mini required; local-first and privacy-first
* [microclaw/microclaw](https://github.com/microclaw/microclaw) - Agentic AI assistant that lives in your Telegram chats, inspired by nanoclaw
* [nullclaw/nullclaw](https://github.com/nullclaw/nullclaw) - Fastest, smallest autonomous AI assistant — 678 KB static binary written in Zig (Zig)
* [poco-ai/poco-agent](https://github.com/poco-ai/poco-agent) - OpenClaw alternative with a nicer Web UI, built-in IM support, and sandboxed runtime powered by Claude Code
* [princezuda/safeclaw](https://github.com/princezuda/safeclaw) - OpenClaw alternative with no LLM and no prompt injection — accepts natural language without a language model
* [qwibitai/nanoclaw](https://github.com/qwibitai/nanoclaw) - Security-focused OpenClaw alternative that runs in containers, built on Anthropic's Agents SDK (TypeScript)
* [RightNow-AI/openfang](https://github.com/RightNow-AI/openfang) - Open-source Agent Operating System built in Rust — 30 agents, 40 channels, 38 tools, single binary (Rust)
* [sipeed/picoclaw](https://github.com/sipeed/picoclaw) - Ultra-lightweight AI assistant in Go, runs on $10 hardware with under 10 MB RAM (Go)
* [warengonzaga/tinyclaw](https://github.com/warengonzaga/tinyclaw) - The original Tiny Claw — a personal autonomous AI companion 🐜 (TypeScript)
* [ysz/nanoClaw](https://github.com/ysz/nanoClaw) - Easy install, ultra-lightweight secure AI assistant inspired by OpenClaw 🦀
* [zeroclaw-labs/zeroclaw](https://github.com/zeroclaw-labs/zeroclaw) - Fast, small, and fully autonomous AI assistant infrastructure — deploy anywhere, swap anything 🦀 (Rust)

## Dashboards & UIs

Monitoring, orchestration, and visual interfaces for OpenClaw.

* [cft0808/edict](https://github.com/cft0808/edict) - OpenClaw multi-agent orchestration system with 9 specialized AI agents, real-time dashboard, and full audit trails (Python)
* [clawdeckio/clawdeck](https://github.com/clawdeckio/clawdeck) - Open source mission control for your OpenClaw agents 🦞
* [crshdn/mission-control](https://github.com/crshdn/mission-control) - AI agent orchestration dashboard (also known as Autensa) — Kanban task management with real-time agent dispatch via OpenClaw Gateway (TypeScript)
* [Curbob/LobsterBoard](https://github.com/Curbob/LobsterBoard) - Self-hosted drag-and-drop dashboard builder for OpenClaw with live system monitoring
* [farion1231/cc-switch](https://github.com/farion1231/cc-switch) - Cross-platform desktop All-in-One assistant tool for Claude Code, Codex, OpenCode, OpenClaw & Gemini CLI (Rust/TypeScript)
* [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) - Free, local, open-source 24/7 cowork app and OpenClaw UI for Gemini CLI, Claude Code, Codex, OpenCode, and more (TypeScript)
* [luccast/crabwalk](https://github.com/luccast/crabwalk) - Real-time companion monitor for OpenClaw agents 🦀
* [tugcantopaloglu/openclaw-dashboard](https://github.com/tugcantopaloglu/openclaw-dashboard) - Secure, real-time monitoring dashboard with auth, TOTP MFA, cost tracking, and memory browser

## Deployment & Infrastructure

Docker images, one-click deploy setups, Helm charts, and hosting configurations.

* [1Panel-dev/1Panel](https://github.com/1Panel-dev/1Panel) - Full-control VPS panel with one-click OpenClaw deployment (Go)
* [bfzli/clawhost](https://github.com/bfzli/clawhost) - Deploy OpenClaw in one click
* [coollabsio/openclaw](https://github.com/coollabsio/openclaw) - Fully featured & automated OpenClaw Docker images
* [essamamdani/moltbot-coolify](https://github.com/essamamdani/moltbot-coolify) - OpenClaw packaged for one-click deployment on Coolify
* [getumbrel/umbrel](https://github.com/getumbrel/umbrel) - Elegant home server OS with OpenClaw in its app store — runs on Raspberry Pi and more (TypeScript)
* [phioranex/openclaw-docker](https://github.com/phioranex/openclaw-docker) - Docker setup and configuration for OpenClaw
* [Scout-DJ/openclaw-nix](https://github.com/Scout-DJ/openclaw-nix) - One flake, fully hardened — NixOS module for secure OpenClaw deployment (Nix)
* [serhanekicii/openclaw-helm](https://github.com/serhanekicii/openclaw-helm) - Helm chart for deploying OpenClaw on Kubernetes 🦞

## Memory & Context

Memory systems and context management for OpenClaw and compatible agents.

* [HKUDS/MoChat](https://github.com/HKUDS/MoChat) - Reconnecting the world through AI agents — works with OpenClaw, nanobot & Claude Code
* [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - Memory layer for 24/7 proactive agents like OpenClaw — persistent, structured memory (Python)
* [volcengine/OpenViking](https://github.com/volcengine/OpenViking) - Open-source context database for AI agents — unifies memory, resources, and skills through a file system paradigm (Python)

## Integrations & Extensions

Bridges, adapters, and integrations that extend OpenClaw into other platforms.

* [freema/openclaw-mcp](https://github.com/freema/openclaw-mcp) - Secure bridge between Claude.ai and your self-hosted OpenClaw assistant with OAuth2 authentication
* [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) - The agent that grows with you — supports OpenClaw, Claude, Codex, and more (Python)
* [qwibitai/nanoclaw-telegram](https://github.com/qwibitai/nanoclaw-telegram) - NanoClaw Telegram channel integration
* [rookiestar28/ComfyUI-OpenClaw](https://github.com/rookiestar28/ComfyUI-OpenClaw) - Personal AIGC factory — integrates OpenClaw with ComfyUI for AI image and video generation
* [zhayujie/chatgpt-on-wechat](https://github.com/zhayujie/chatgpt-on-wechat) - Super AI assistant with active thinking and task planning, supports WeChat, DingTalk, Feishu, QQ, and more (Python)

## Awesome Lists & Resources

Other curated lists and community resource collections in the OpenClaw ecosystem.

* [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - Community collection of OpenClaw use cases for making life easier
* [rohitg00/awesome-openclaw](https://github.com/rohitg00/awesome-openclaw) - Curated awesome list for OpenClaw resources
* [vincentkoc/awesome-openclaw](https://github.com/vincentkoc/awesome-openclaw) - Curated list covering skills, plugins, memory systems, MCP tools, deployment stacks, and developer tooling

---

## Community

Contributions are welcome. Please read the [contribution guidelines](CONTRIBUTING.md) before opening a PR.

### How to contribute

1. Fork this repo.
2. Add a new bullet under the correct category.
3. Keep entries sorted alphabetically by repo name within each section.
4. Use the format: `* [owner/repo](link) - One sentence description (Language)`
5. Create a PR and link any supporting demos or docs.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
