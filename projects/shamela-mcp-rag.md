# shamela-mcp-rag

A local-first ingestion and hybrid search engine for a large Arabic Islamic-texts library, exposed to AI assistants as an MCP server.

**Status:** active · **License:** MIT · **Repo:** private

## What it does

Ingests library books from two source formats, normalizes Arabic text, chunks by page while keeping volume and page citations, and serves keyword plus semantic search. AI clients such as Claude Desktop connect over MCP and get citation-grade answers.

## Highlights

- 54 MCP tools and 8 resources over stdio.
- Hybrid retrieval: full-text (FTS5) and dense vectors (LanceDB, BGE-M3) fused with Reciprocal Rank Fusion.
- Arabic-specific NLP: normalization, lemma and root expansion, diacritization, diacritic-preserving highlighting.
- Domain tools for commentary mapping, jurisprudence comparison, recitation variants, grammar and narrator chains.
- Guardrails that flag weak or fabricated narrations automatically.
- Publishing pipeline from manuscript to formatted Google Docs, with right-to-left and footnote handling.
- Autonomous research agents built on smolagents.

## Technology

Python 3.12, FastMCP, LanceDB, SQLite FTS5, FastAPI, smolagents, Ollama, Ruff, mypy, pytest, GitHub Actions.

## Interested?

Source is private. Contact [@ramyfrdwan](https://github.com/ramyfrdwan).
