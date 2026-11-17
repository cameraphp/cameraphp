# Juan Pablo Gonzalez Camera

### Senior AI & Systems Engineer

I build reliable backend integrations and AI workflows, supported by independent engineering labs for agent recovery, code evaluation, CRM data synchronization, and wallet-facing backends. My work emphasizes explicit state, testable boundaries, and failure recovery.

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
| [Creator Agent Reliability Lab](https://github.com/cameraphp/creator-agent-reliability-lab) | Local TypeScript/Postgres creator workflows with durable jobs, scoped context, validated drafts, and save/reopen recovery. Includes reproducible before/after evaluation with simulated providers. |
| [GHL Multi-Account Data Hub Lab](https://github.com/cameraphp/ghl-multi-account-data-hub-lab) | TypeScript/PostgreSQL contact matching, field provenance, routing plans, and replayable webhooks across simulated GHL accounts. Unknown destinations wait for review before writes; automatic contact creation is deferred. |
| [LLM Code Evaluation Lab](https://github.com/cameraphp/llm-code-evaluation-lab) | Python evaluation of controlled code against idempotency, tenant-authorization, and job-retry contracts, with severity-gated scores and evidence-backed feedback. No live LLM or untrusted-code sandbox; reviewer examples are synthetic. |
| [Durable Integration Worker](https://github.com/cameraphp/durable-integration-worker-ts) | Local TypeScript reference for at-least-once webhook processing with idempotency controls, bounded retries, dead letters, and restart recovery. |
| [Web3 Backend Reliability Lab](https://github.com/cameraphp/web3-backend-reliability-lab) | Local TypeScript/Solidity SIWE authentication, recoverable EVM indexing, and reorg-aware outbox delivery with Postgres, viem, and Foundry/Anvil. No real funds or public-chain deployment; downstream effects are simulated. |
| [Legacy Web Hardening Lab](https://github.com/cameraphp/legacy-web-hardening-lab) | Local Docker Compose PHP/Apache environment behind Nginx TLS, with proxy-boundary controls, backup verification, and migration/rollback exercises. Independent reference, not a client deployment. |

### More engineering labs

- [Interactive Contradiction Resolution Lab](https://github.com/cameraphp/interactive-contradiction-resolution-lab): deterministic structured claims, exact proposed changes, human approval, and audit; no live model extraction.
- [LLM Eval Regression Lab](https://github.com/cameraphp/llm-eval-regression-lab): deterministic offline regression gates for structured outputs and citations; not code-behavior evaluation or real-model benchmarking.
- [AI COO Real Estate Lab](https://github.com/cameraphp/ai-coo-real-estate-lab): synthetic AI operations with a human approval gate and no external side effects.
- [Voice Agent Reliability Lab](https://github.com/cameraphp/voice-agent-reliability-lab): local voice runtime and deterministic fault replay; human acoustic validation remains pending.
- [GCP/BigQuery AI Data Platform Lab](https://github.com/cameraphp/gcp-bigquery-ai-data-platform-lab): local DuckDB reference; GCP adapters and Terraform remain undeployed.
- [IaC Change Control Lab](https://github.com/cameraphp/iac-change-control-lab): policy checks and digest-bound approval on synthetic plan-like inputs; no cloud access or infrastructure deployment.

[Full engineering-labs catalogue](https://solidscripts.io/en/engineering-labs/) · [Catálogo en español](https://solidscripts.io/laboratorios-ingenieria/) · [Experience & CV](https://solidscripts.io/en/experience-cv/)

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
