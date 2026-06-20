# Daeseon Yoo

Backend engineer in Toronto, 6 years in production Java/Spring and SQL/PL-SQL across manufacturing, warehouse, and finance. Now building AI products end to end — LLM pipelines, RAG, agent loops, and vision — on top of that backend foundation.

I ship the boring parts that AI features need in production: transactions, migrations, CI/CD, audit trails.

## Selected work

| Project | What it does | Stack | Links |
|---|---|---|---|
| **Mimi** | YouTube → SRS English shadowing app. Transaction-safe async LLM pipeline with env-gated Gemini/Claude swap. 8 bounded contexts, 11 tables, 14 Playwright e2e, 292 commits. | Java 21 / Spring Boot, Next.js/TS, PostgreSQL, AWS ECS | [live](https://mimi.daeseon.ai) · [repo](https://github.com/Daeseon-AI-Factory/shadow-ai) |
| **DocVault** | Self-hosted insider-threat event collector. DB-trigger hash-chain tamper-evident audit log, operator AI assistant. 96 commits. | Go 1.26, PostgreSQL 16, htmx, osquery, AES-256-GCM | [live](https://docvault.daeseon.ai) · [repo](https://github.com/Daeseon-AI-Factory/docvault) |
| **ScreenBridge** | Translates abstract AI instructions into concrete screen pointer actions. Includes a Tauri→Swift migration retro. | Swift 6, ScreenCaptureKit, AXUIElement, Claude Sonnet vision | [repo](https://github.com/Daeseon-AI-Factory/jarvis-pc) |
| **Beside (곁)** | Private support-box PWA; one codebase scales zero-account-local → full prod by env var. | Next.js 16, Web Push, Drizzle, S3/R2, Terraform | [live](https://beside.daeseon.ai) |
| **Talkak** | Native macOS multi-pane terminal command deck for solo founders running BYO Claude Code/Codex. | Tauri 2 / Rust, React 19, xterm.js, tmux | [live](https://talkak.daeseon.ai) |

**What this isn't:** most of these are solo MVPs, not battle-tested-at-scale services. No team-of-50 traffic numbers here — the production-scale retros live in the blog below, from prior backend roles.

## Writing

I write at **[daeseon.ai](https://daeseon.ai)** (12 EN / 12 KO posts) — production war-story retros and concept write-ups, not motivational threads. A couple:

- *A SELECT That Stopped a Factory* — a query that took down a production line
- *You Can't Enforce What You Can't Observe* — concept write-up, multi-register

## Tech

Java/Spring · Go · TypeScript/Next.js · Swift · Rust/Tauri · PostgreSQL · AWS

## Contact

Toronto, Canada · [showep12@gmail.com](mailto:showep12@gmail.com) · [daeseon.ai](https://daeseon.ai)
