# Daeseon Yoo

Backend engineer in Toronto, 6 years in production Java/Spring and SQL/PL-SQL across manufacturing, warehouse, and finance. Now building AI products end to end — LLM pipelines, RAG, agent loops, and vision — on top of that backend foundation.

I ship the boring parts AI features need in production: transactions, migrations, CI/CD, audit trails. Each project below has a source-verified **architecture deep-dive** — measured numbers, real file references, and an honest "what it doesn't do."

## Selected work

| Project | What it does | Highlights (measured) | Links |
|---|---|---|---|
| **Mimi** | YouTube → SRS English-shadowing app. Async LLM pipeline pinned off the DB connection (`@TransactionalEventListener(AFTER_COMMIT)` + a bounded `CallerRuns` pool), repository-layer multi-tenant isolation, Gemini→OpenAI→Claude fallback with hand-rolled retry. | 8,892 LOC · 49 endpoints · 121 tests · AWS ECS Fargate | [live](https://mimi.daeseon.ai) · [repo](https://github.com/Daeseon-AI-Factory/shadow-ai) · [architecture →](https://daeseon.ai/projects/shadow-ai/architecture) |
| **DocVault** | Self-hosted insider-threat event collector. Tamper-evident audit hash-chain enforced in Postgres triggers (advisory-locked against a read-then-write race), chunked authenticated AES-GCM, server-enforced operator AI assistant. | 17,783 LOC · 23 tables · 102 routes | [live](https://docvault.daeseon.ai) · [repo](https://github.com/Daeseon-AI-Factory/docvault) · [architecture →](https://daeseon.ai/projects/docvault/architecture) |
| **ScreenBridge** | Translates abstract AI instructions into concrete on-screen pointer actions — Accessibility + OCR ranked above LLM coordinates. Documented Tauri→Swift migration retro. | 5,808 LOC · Swift 6 strict concurrency | [repo](https://github.com/Daeseon-AI-Factory/jarvis-pc) · [architecture →](https://daeseon.ai/projects/jarvis-pc/architecture) |
| **Beside (곁)** | Private support-box PWA; one codebase scales zero-account-local → full production infra by env var alone. A multi-agent security pass fixed real issues. | 6,822 LOC · Terraform · Web Push | [live](https://beside.daeseon.ai) · [architecture →](https://daeseon.ai/projects/beside/architecture) |
| **Talkak** | Native macOS multi-pane terminal command deck for solo founders running their own Claude Code / Codex. tmux-persistent panes, no server. | 3,605 Rust + 12k TS LOC | [live](https://talkak.daeseon.ai) · [architecture →](https://daeseon.ai/projects/talkak/architecture) |

**What this isn't:** most of these are solo MVPs, not battle-tested-at-scale services. No team-of-50 traffic numbers here — the production-scale war stories live in the blog, from prior backend roles.

## Writing

**[daeseon.ai](https://daeseon.ai)** — production war-story retros and concept write-ups, not motivational threads:

- *A SELECT That Stopped a Factory* — a query that took down a production line
- *The TLS Certificate Nobody Was Watching Expired* — an outage and the gap behind it
- *You Can't Enforce What You Can't Observe* — concept write-up, multi-register

## Tech

Java/Spring · Go · TypeScript/Next.js · Swift · Rust/Tauri · PostgreSQL · AWS

## Contact

Toronto, Canada · [showep12@gmail.com](mailto:showep12@gmail.com) · [daeseon.ai](https://daeseon.ai)
