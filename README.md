# ai-applied

> Catch the balance and build.

Curated list of AI-applied tools and resources — coding agents, skills, and infra.\
No bloat — only what's genuinely useful.

## Disclaimer

This is **my** list. Use this as reference to explore.\
There is no one correct way to use Claude Code and other coding agents. Every engineer uses their tools differently.

## Contents

- [Skills & Plugins](#skills--plugins)
- [Tooling](#tooling)
- [Agents](#agents)
- [Design & Web](#design--web)
- [Infra](#infra)
- [Reference](#reference)

---

## Skills & Plugins

- [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) — Collection of Claude Code skills
- [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) — Official Anthropic plugin marketplace for Claude Code
- [anthropics/skills](https://github.com/anthropics/skills) — Official reference skills from Anthropic
- [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) — Multi-phase codebase security audit with independently verified findings
- [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) — Always-on skill against over-engineering: smallest complete change, never cuts validation or security
- [janestreet/agent_skills](https://github.com/janestreet/agent_skills) — Jane Street's Socratic tutor skill: diagnostic, 0–5 skill map, spaced review, final assessment
- [mattpocock/skills](https://github.com/mattpocock/skills) — TypeScript-focused Claude Code skills
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) — Researches what people said about a topic in the last 30 days (Reddit, X, HN, YouTube…)
- [obra/superpowers](https://github.com/obra/superpowers) — Skill framework extending Claude Code's baseline capabilities

## Tooling

- [phuryn/claude-usage](https://github.com/phuryn/claude-usage) — Usage/cost dashboard with VS Code sidebar
- [pingdotgg/t3code](https://github.com/pingdotgg/t3code) — One interface for Claude Code, Codex and other agents on desktop, web and phone; runs on your own subscriptions
- [rtk-ai/rtk](https://github.com/rtk-ai/rtk) — Trims noisy bash/tool output before it reaches the model
- [sirmalloc/ccstatusline](https://github.com/sirmalloc/ccstatusline) — Customizable statusline for Claude Code

## Agents

- [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) — Agent harness for learning: probes your level, plans a path, teaches step by step with checks (BYOK or Claude Code CLI)
- [anomalyco/opencode](https://github.com/anomalyco/opencode) — Open-source terminal coding agent
- [earendil-works/pi](https://github.com/earendil-works/pi) — Minimal, extensible coding agent harness you adapt yourself: no built-in sub-agents or plan mode
- [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) — Agent framework from Nous Research

## Design & Web

- [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Official Chrome DevTools for agents (MCP + CLI): performance traces, network, console, automation
- [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI) — Node-based GUI for diffusion models
- [emilkowalski/skills](https://github.com/emilkowalski/skills) — UI/animation skills from a Vercel/Linear design engineer: animate, review, perf, break-ui
- [GoogleChrome/modern-web-guidance](https://github.com/GoogleChrome/modern-web-guidance) — Skill with modern web platform guides and browser support data, steers agents off legacy patterns
- [JCodesMore/ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template) — Template for migrating a site onto a new stack
- [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) — Catalog of style-preset skills to avoid generic AI-slop design
- [meta/astryx](https://github.com/meta/astryx) — Meta's React design system built for people and agents: 150+ accessible components, CSS-variable theming, CLI
- [Nutlope/hallmark](https://github.com/Nutlope/hallmark) — Design skill with build/audit/redesign/study verbs and slop-detection gates
- [pbakaus/impeccable](https://github.com/pbakaus/impeccable) — Design-language extension skill
- [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) — Curated design resources for AI-assisted workflows

## Infra

- [ag-ui-protocol/ag-ui](https://github.com/ag-ui-protocol/ag-ui) — Open event-based protocol between agents and app frontends: streamed text, tool calls, shared state, human-in-the-loop
- [alibaba/open-code-review](https://github.com/alibaba/open-code-review) — BYOK AI code review CLI from Alibaba: line-level comments on diffs or whole files, CI-ready
- [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) — MCP server for n8n workflow automation
- [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) — Crawls whole sites into LLM-ready markdown or structured data
- [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything) — Generates agent-ready CLIs for desktop software (GIMP, LibreOffice, Obsidian, ...), plus a community registry of ready ones
- [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook) — Self-hosted, BYOK NotebookLM alternative
- [MemPalace/mempalace](https://github.com/MemPalace/mempalace) — Local-first long-term memory for AI agents
- [microsoft/markitdown](https://github.com/microsoft/markitdown) — Converts documents to markdown for LLM use
- [morluto/rea](https://github.com/morluto/rea) — MCP server for agent-driven reverse engineering of apps and binaries
- [NVIDIA/OpenShell](https://github.com/NVIDIA/OpenShell) — Policy-based sandbox for coding agents: kernel-level file/network limits, credentials injected on egress
- [open-webui/open-webui](https://github.com/open-webui/open-webui) — Self-hosted web UI for local/remote LLMs
- [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy) — Framework for programming LLM pipelines: declarative modules, optimizers tune prompts against a metric
- [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) — Browser automation CLI for agents: pages as compact text with element refs, one shell call per step
- [vercel-labs/json-render](https://github.com/vercel-labs/json-render) — Generative UI: the model answers with screens built only from components you approve

## Reference

- [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) — Collected leaked system prompts from AI products
- [dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) — Reference guide on prompt engineering
