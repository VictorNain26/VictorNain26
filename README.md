# Victor Lenain

Full-stack engineer in Paris. I build LLM products end to end: agent orchestration, structured outputs, guardrails, retrieval, evaluation and tracing, plus the web apps and infrastructure around them.

Python · TypeScript · React · PostgreSQL · Docker · GitHub Actions

## Selected work

| Project | What it shows |
|---|---|
| [fabrique-cours-agents](https://github.com/VictorNain26/fabrique-cours-agents) | Page-generation service built as a hands-on course: LangGraph with human validation, a Temporal workflow (tested, not wired to the API), multi-provider fallback with a budget, structured-output repair, guardrails, Langfuse tracing and a deterministic regression gate in CI (fake provider). |
| [tomai-monorepo](https://github.com/VictorNain26/tomai-monorepo) | AI homework tutor for middle-school students (pre-launch, no users yet). The rule that matters most, never hand over the answer, is enforced by server code that checks each reply before the student sees it, not left to the prompt. A test bench replays simulated student conversations against the real tutor. Also: moderation of what goes in and out, and the cost of every model call recorded, with a daily budget per student. Bun, Hono, PostgreSQL, React, Mistral API. |
| [aubesonore](https://github.com/VictorNain26/aubesonore) | Self-hosted web radio on the air at [aubesonore.fr](https://aubesonore.fr/), one monorepo: a Python pipeline that discovers tracks, learns from my votes on a private page and from Discogs-EffNet audio embeddings, and schedules the antenna; the listener site (React PWA, Bun/Elysia, PostgreSQL); reproducible MusicBrainz lineage tables (same dump and code, same bytes). Deployed by a pull-based systemd timer gated on health checks. |

[victorlenain.fr](https://www.victorlenain.fr/)
