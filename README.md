# Juan Pablo Gonzalez Camera

### Senior AI & Systems Engineer

I build reliable AI workflows, integration systems, and local reference labs for voice runtimes, data platforms, and web security. My work emphasizes explicit state, testable boundaries, and failure recovery.

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
| [ai-coo-real-estate-lab](https://github.com/cameraphp/ai-coo-real-estate-lab) | Controlled AI-operations workflow with validated synthetic leads, deterministic retrieval, structured proposals, and a human approval gate. No external side effects. |
| [voice-agent-reliability-lab](https://github.com/cameraphp/voice-agent-reliability-lab) | Local voice-runtime lab with offline ASR, explicit turn ownership, idempotent booking tools, and deterministic fault replay. Real-audio validation remains pending. |
| [gcp-bigquery-ai-data-platform-lab](https://github.com/cameraphp/gcp-bigquery-ai-data-platform-lab) | Local-first data pipeline with validation, quarantine, deduplication, and read-only analytics. Uses DuckDB locally; GCP adapters and Terraform remain undeployed. |
| [durable-integration-worker-ts](https://github.com/cameraphp/durable-integration-worker-ts) | Local TypeScript reference for at-least-once webhook processing, with idempotency controls, bounded retries, dead letters, restart recovery, and CI. |
| [llm-eval-regression-lab](https://github.com/cameraphp/llm-eval-regression-lab) | Deterministic offline evaluation for LLM/RAG-style workflows, with versioned synthetic cases, structured-output checks, citation controls, and regression gates. |
| [legacy-web-hardening-lab](https://github.com/cameraphp/legacy-web-hardening-lab) | Local Docker Compose lab for PHP/Apache behind Nginx TLS, with proxy-boundary controls, backup verification, and migration/rollback exercises. |

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
