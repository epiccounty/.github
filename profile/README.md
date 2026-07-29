# Epic County

Epic County is an AI-native systems company. It builds Rust-based tools and infrastructure for AI coding agents, ships them as an ecosystem installed through a single CLI, and runs a research program on production theory for the AI economy.

The company has two arms: an **engineering** side developing open-source agent infrastructure, and **Epic County AI Labs**, a research division studying computational economics and AI-native production.

## Epic County AI Labs

The company's research division.

**AI Production Economics** — a research program on production theory for the AI-native economy.

Manuscripts in preparation. Publications and reproducible artifacts will be released here when ready.

## Open Source — Epic County Ecosystem

A Rust toolchain for AI-native development, installed and managed through the [`epiccounty`](https://github.com/epiccounty/epiccounty.com) CLI (`epiccounty install all`).

> The tools are currently published under [`@epicsagas`](https://github.com/epicsagas) and will migrate to the Epic County organization as the brand matures.

### Foundation

- [**llm-kernel**](https://github.com/epicsagas/llm-kernel) — Rust foundation library for AI-native apps. A 20-provider, 351-model catalog, async LLM client, MCP server, local ONNX embeddings, a knowledge graph, and safety utilities — each module behind a feature flag.

### Platforms

- [**epic-harness**](https://github.com/epicsagas/epic-harness) — Claude Code plugin that consolidates 30+ commands into 3 commands plus 26 context-triggered skills, and evolves new skills from your own failure patterns.
- [**alcove**](https://github.com/epicsagas/alcove) — HTTP API server that gives coding agents on-demand access to private project docs, with BM25 + vector hybrid search, tree-sitter code indexing, and doc-consistency policy enforcement.
- [**Episteme**](https://github.com/epicsagas/Episteme) — offline-first, single-binary knowledge graph that links design patterns, refactorings, and software laws through semantic relationships, exposed to agents via MCP.

### CLI Tools

- [**claudy**](https://github.com/epicsagas/claudy) — switch claude code between Anthropic, Z.AI, OpenRouter, Ollama, and custom endpoints with one command, with per-profile credential and config isolation.
- [**obsidian-forge**](https://github.com/epicsagas/obsidian-forge) — Rust CLI that scaffolds, automates, and maintains Obsidian vaults as a background daemon: inbox processing, graph strengthening, and git sync.

### Libraries

- [**llm-transpile**](https://github.com/epicsagas/llm-transpile) — transpiles raw documents (Markdown, HTML, plain text) into a token-optimized bridge format with adaptive compression that stays under budget.

## Links

- 🌐 [epiccounty.com](https://epiccounty.com)
- 📧 [hello@epiccounty.com](mailto:hello@epiccounty.com)
