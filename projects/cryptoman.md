# CryptoMan

An automated spot-trading bot with grid and dollar-cost-averaging strategies, optional AI sentiment input, and a live dashboard.

**Status:** active development · **License:** MIT · **Repo:** private

## What it does

Runs a 20-second loop over a basket of assets. Each cycle observes the market, scores signals, plans rebalancing, acts through the exchange API and records state. Paper-trading mode is the default way to start.

## Highlights

- Five-phase cycle: observe, think, plan, act, record.
- Exchange REST and WebSocket integration; SQLite (WAL) persistence.
- Optional Vertex AI / Gemini sentiment analysis behind a feature flag.
- Authenticated server-sent-events dashboard and a Telegram bot for alerts and control.
- CI-enforced lint, type checks and tests; audit reports tracked in the repo.

## Technology

Python 3.13, FastAPI, SQLite, Vertex AI, Docker, pytest, Ruff, mypy, GitHub Actions.

## Interested?

Source is private. Contact [@ramyfrdwan](https://github.com/ramyfrdwan).
