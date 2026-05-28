# Dae-Seon Yoo

Backend engineer in Toronto. Six years building and modernizing production systems — mostly Java/Spring and SQL/PL-SQL across manufacturing, warehouse, and finance domains. I work closest to the data and transaction layer: API design, transaction boundaries, and concurrency/reliability across multi-server systems. Lately I've been building Spring services and small products that use LLMs.

## Projects

**[TubeShadow](https://github.com/Daeseon-AI-Factory/shadow-ai)** — a YouTube-clip language shadowing trainer.
Spring Boot · Next.js · PostgreSQL · AWS

The core piece is an async, event-driven LLM analysis pipeline: provider calls run *outside* the DB transaction (Spring `AFTER_COMMIT` + `@Async`) so a multi-second LLM call never holds a connection, with a `PENDING → READY / FAILED` state machine and a runtime-selectable Claude/Gemini provider interface.

**[Dalkkak](https://github.com/Daeseon-AI-Factory/ddalkkak)** — a multi-pane macOS terminal for running AI coding agents.
Rust · Tauri · React · tmux

Each pane is a PTY backed by its own tmux session, so terminal sessions survive app restarts and React remounts.

## Tech

Java · Spring Boot · SQL/PL-SQL (Oracle, PostgreSQL) · C# / .NET · TypeScript · React / Next.js · Rust · AWS · Docker · Linux

## Links

- Case studies: [daeseon.ai](https://www.daeseon.ai)
- LinkedIn: https://www.linkedin.com/in/daeseonyoo/ 
- Email: showep12@gmail.com
