# Juan Pablo Gonzalez Camera

### Senior AI & Systems Engineer

I build reliable AI workflows, integration systems, and web-platform reference labs that are designed to be tested, inspected, and safely improved.

> Public repositories are controlled engineering demonstrations or open-source contributions. They use synthetic data or local fixtures where appropriate and document scope, tests, trade-offs, failure modes, and recovery boundaries without exposing client-confidential information.

## Focus areas

- **Reliable AI systems** — structured outputs, explicit tool boundaries, approval gates, workflow state, and safe automation.
- **Evaluation and secure retrieval workflows** — versioned synthetic cases, evidence grounding controls, refusal/insufficient-evidence behavior, and regression gates.
- **Backend and integration reliability** — TypeScript, Python, REST APIs, idempotency, bounded retries, durable state, recovery, and structured observability.
- **Web and platform hardening** — Linux, Docker, PHP/Apache, Nginx, secure proxy boundaries, validation, backup verification, migration, and rollback thinking.

## Selected work

| Project | What it demonstrates |
| --- | --- |
| [ai-coo-real-estate-lab](https://github.com/cameraphp/ai-coo-real-estate-lab) | Controlled AI-operations workflow: validated synthetic lead intake, deterministic property retrieval, structured proposals, correlation IDs, and a human approval gate with no external side effects. |
| [durable-integration-worker-ts](https://github.com/cameraphp/durable-integration-worker-ts) | Tested local TypeScript reference for durable, idempotency-aware, at-least-once webhook processing with strict validation, bounded retries, dead letters, restart recovery, structured logs, and CI. |
| [llm-eval-regression-lab](https://github.com/cameraphp/llm-eval-regression-lab) | Deterministic local/offline evaluation and regression lab for LLM/RAG-style workflows, using versioned synthetic cases, structured-output checks, citation controls, refusal handling, and prompt/model traceability. |
| [legacy-web-hardening-lab](https://github.com/cameraphp/legacy-web-hardening-lab) | Tested local Docker Compose lab: a legacy-style PHP/Apache origin behind an Nginx TLS edge, with origin restriction, forwarded-header sanitation, secure lab sessions, backup verification, and migration/rollback exercises. |
| [Microsoft Agent Governance Toolkit contribution](https://github.com/microsoft/agent-governance-toolkit/pull/3754) | Merged contribution to Microsoft’s toolkit: HIPAA-oriented healthcare identifier patterns, validation safeguards, and regression-test coverage for regulated-workflow controls. |

## Engineering principles

```text
Validate inputs and outputs.
Make behavior, assumptions, and tool boundaries explicit.
Design for duplicate delivery, failure paths, retries, and recovery.
Use deterministic fixtures where they make quality controls reproducible.
Keep operational claims bounded by documented evidence.
Protect confidential data and prefer safe, observable defaults.
```

## Open to

Senior and staff-level opportunities in AI systems engineering, agentic workflows, LLM/RAG evaluation, backend and platform engineering, secure integrations, DevOps, and reliability engineering.

---

*For each repository, the README is the source of truth for scope, architecture, reproducible validation, and limitations.*
