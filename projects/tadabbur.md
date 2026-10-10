# Tadabbur (Basaer al-Wahy)

A complete platform for reading and studying the Quran: web app, installable PWA, and a native mobile app, with an Arabic-first interface.

**Status:** live in production · **Site:** [basaer-wahy.com](https://www.basaer-wahy.com) · **Repo:** private

## What it does

- Full Quran text with the Madinah Mushaf 15-line page layout.
- Six-lens analytical study per verse (narration, language and grammar, coherence, rulings, rhetoric, practical guidance).
- Eleven study tools, including semantic search, concept maps, recitation variants and similar-verse disambiguation.
- Offline reading, sync across devices, daily reminders and reading-completion tracking.
- A documented public API (OpenAPI 3.1).

## Engineering highlights

- Monorepo with shared packages for contracts, domain logic, an API client and Arabic text utilities.
- Thousands of pre-rendered pages with incremental regeneration; serverless Postgres behind it.
- Content written in Markdown in Git, checked against classical sources through a scholarly MCP server before it is ingested.
- Mobile app in Flutter with an encrypted local corpus database.
- CI gates on text quality, lint, types, unit and end-to-end tests.

## Technology

Next.js 16, React 19, TypeScript, Drizzle ORM, Neon Postgres, Auth.js, Tailwind, Serwist PWA, Flutter, Drift, Turborepo, Vitest, Playwright, Vercel, Cloudflare R2.

## Interested?

Source is private. Contact [@ramyfrdwan](https://github.com/ramyfrdwan) for details or access.
