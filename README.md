# Juan Pablo Gonzalez Camera

### Senior AI & Systems Engineer

I build reliable backend integrations and AI workflows, supported by independent engineering labs for agent reliability, evaluation, voice runtimes, data platforms, and web security. My work emphasizes explicit state, testable boundaries, and failure recovery.

> Public repositories are engineering demonstrations or open-source contributions, not claims of production deployment. They use synthetic data or local fixtures where appropriate and document scope, tests, trade-offs, and limitations without exposing client-confidential information.

## Focus areas

- **Reliable AI workflows** — structured outputs, tool boundaries, approval gates, evaluation, and secure retrieval.
- **Voice-runtime reliability** — turn ownership, interruption handling, uncertain tool results, and deterministic fault replay in a local lab.
- **Backend and integration reliability** — Python, TypeScript, APIs, idempotency, bounded retries, durable state, and observability.
- **Data-platform engineering** — validation, quarantine, deduplication, and read-only analytics, with a local-first GCP reference architecture.
- **Web and platform hardening** — Linux, Docker, PHP/Apache, Nginx, proxy boundaries, backup verification, and rollback exercises.

## Selected work

| Project | What it demonstrates |
| --- | --- |
| [creator-agent-reliability-lab](https://github.com/cameraphp/creator-agent-reliability-lab) | Synthetic TypeScript/Postgres creator workflow with durable jobs, scoped context, safe retries, validated drafts, and save/reopen recovery. Includes reproducible before/after evaluation. |
| [interactive-contradiction-resolution-lab](https://github.com/cameraphp/interactive-contradiction-resolution-lab) | Deterministic TypeScript lab for conflicting knowledge-base claims: evidence, exact proposed diffs, human approval, and auditable changes. Uses structured synthetic claims, not live model extraction. |
| [durable-integration-worker-ts](https://github.com/cameraphp/durable-integration-worker-ts) | Local TypeScript reference for at-least-once webhook processing, with idempotency controls, bounded retries, dead letters, and restart recovery. |
| [llm-code-evaluation-lab](https://github.com/cameraphp/llm-code-evaluation-lab) | Python evaluation of controlled code against idempotency, tenant-isolation, and background-job contracts, with evidence-backed scoring and feedback. Reviewer examples are synthetic; no real LLM is invoked. |
| [llm-eval-regression-lab](https://github.com/cameraphp/llm-eval-regression-lab) | Deterministic offline evaluation of LLM/RAG-style structured outputs, citations, and regression gates using versioned synthetic cases—not code-behavior evaluation or real-model benchmarking. |
| [legacy-web-hardening-lab](https://github.com/cameraphp/legacy-web-hardening-lab) | Local Docker Compose lab for PHP/Apache behind Nginx TLS, with proxy-boundary controls, backup verification, and migration/rollback exercises. |

### More engineering labs

- [AI COO Real Estate Lab](https://github.com/cameraphp/ai-coo-real-estate-lab): synthetic AI operations with a human approval gate and no external side effects.
- [Voice Agent Reliability Lab](https://github.com/cameraphp/voice-agent-reliability-lab): local voice runtime and deterministic fault replay; human acoustic validation remains pending.
- [GCP/BigQuery AI Data Platform Lab](https://github.com/cameraphp/gcp-bigquery-ai-data-platform-lab): local DuckDB reference; GCP adapters and Terraform remain undeployed.
- [IaC Change Control Lab](https://github.com/cameraphp/iac-change-control-lab): policy checks and digest-bound approval on synthetic plan-like inputs; no cloud access or infrastructure deployment.

[Full engineering-labs catalogue](https://solidscripts.io/en/engineering-labs/) · [Catálogo en español](https://solidscripts.io/laboratorios-ingenieria/)

## Open-source contributions

[Microsoft Agent Governance Toolkit — merged contribution](https://github.com/microsoft/agent-governance-toolkit/pull/3754): HIPAA-oriented healthcare identifier patterns, validation safeguards, and regression tests for regulated-workflow controls.

## Engineering principles

- Validate inputs and outputs, and keep tool boundaries explicit.
- Design for duplicate delivery, failure paths, retries, and recovery.
- Use reproducible fixtures where they make quality controls testable.
- Keep claims bounded by documented evidence and protect confidential data.

## Open to

Senior and staff-level opportunities in AI systems engineering, agentic workflows, LLM/RAG evaluation, backend integrations, data platforms, DevOps, and reliability engineering.

---

*Each repository's README is the source of truth for its scope, architecture, validation, and limitations.*
