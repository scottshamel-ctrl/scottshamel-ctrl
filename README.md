### Shamel Scott

I build production systems around language models: pipelines that run unattended, fail loudly, and get checked against the real system instead of against what the model says it did. Under that are ten years of Linux and network operations.

**Open source**

- **[local-first-llm-gateway](https://github.com/scottshamel-ctrl/local-first-llm-gateway)**: an OpenAI-compatible endpoint that uses my own GPU when it's up and a cloud model when it isn't. Prompts marked private fail closed instead of leaving the machine. Handles Tailscale over SOCKS5. Zero deps, 29 tests.
- **[local-llm-guard](https://github.com/scottshamel-ctrl/local-llm-guard)**: calls a local LLM on the machine you're working on without freezing it. Single-flight pacing, timeouts derived from each request's output cap, bounded model residency. Zero deps, 29 tests.
- **[homenet-fit](https://github.com/scottshamel-ctrl/homenet-fit)**: six deterministic home-network compatibility tools that answer `unknown` instead of guessing. Evidence-cited rules, static site, 61 tests.

**Work:** TypeScript / Bun, Python, Bash · Claude Code, Codex, MCP · Ollama, OpenRouter, Anthropic, OpenAI · Hono, SQLite, DuckDB, Stripe · Cloudflare, Tailscale, Debian

[Portfolio](https://scottshamel.zo.space/portfolio) · [LinkedIn](https://www.linkedin.com/in/shamel-scott-/) · Astoria, NY
