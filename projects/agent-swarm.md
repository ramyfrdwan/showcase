# agent-swarm

Production-grade multi-agent orchestration for Claude Code and Gemini, built on the Model Context Protocol (MCP).

**Status:** active · **Repo:** private

## What it does

An orchestrator classifies each request, splits complex work into a dependency graph of sub-tasks, and routes each one to a specialist agent (coding, debugging, architecture, docs, security and others). Work moves through a gated delivery pipeline: define, plan, build, verify, review, ship.

## Highlights

- Six MCP servers: one orchestrator and several specialists, each with its own tool surface.
- Weighted routing across 16 specialist domains, with bilingual (English and Arabic) matching and feedback from past routing corrections.
- DAG task decomposition with parallel execution groups and structured handoffs between agents.
- Quality gates that distinguish measured checks from self-attested ones, plus an LLM-review quorum for sign-off.
- Shared SQLite context store for tasks, findings, handoffs and a searchable lessons-learned knowledge base.
- A skills library (75 skills) loaded through server-side, routed and ambient channels.
- Documentation-versus-code drift detection and utilization reporting from the CLI.

## Technology

TypeScript (strict), Node.js, MCP SDK, SQLite, Vitest, Swift menu-bar companion app, shell installers.

## Interested?

This repo is private. Contact [@ramyfrdwan](https://github.com/ramyfrdwan) for a walkthrough or access.
