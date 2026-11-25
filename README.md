# Hi, I'm Pranav Krishna Danda

**Software Engineer · Python backend on AWS · LLM features with tests · Hyderabad, India**

I build Python backend services, queue pipelines and LLM features, with tests that prove they work. My day job is in a regulated (FDA 21 CFR Part 11) clinical-trial product.

Software Engineer at **Oovacha** since Oct 2025 (intern from Mar 2025): protocol-ingestion pipeline, study-onboarding API, Part 11 audit trail, and backend test coverage from 82% to 95%. Before that, I built a RAG chatbot, classification models and Django APIs as an intern at **Mushroom Solutions**.

Right now I'm focused on reliable backends, fail-closed validation of LLM output, and testing.

---

## Selected projects

| Project | What it does | Stack |
|---|---|---|
| [Driftline](https://github.com/pranavkrishnadanda/Driftline) · [live demo](https://pranavkrishnadanda.github.io/Driftline/demo/) | Version-aware knowledge engine: answers only from documents in force on a given date, with verified citations. 0% outdated citations vs 20.8% for plain RAG on FDA drug labels (40-question sample, real Claude) | Python, FastAPI, LangGraph, Postgres + pgvector, Redis Streams, Next.js |
| [Sluice](https://github.com/pranavkrishnadanda/sluice) | Self-planning agentic pipeline for drifting data files; accuracy graded by code against exact ground truth; 1,371 tests | Python, FastAPI, DuckDB, Polars, LiteLLM, Postgres |
| [MergeSignal](https://github.com/pranavkrishnadanda/MergeSignal) | Flags merges that git reports as clean but that break at runtime; tree-sitter across 6 languages, 643 tests, published on PyPI | Python, tree-sitter |
| [Aura](https://github.com/pranavkrishnadanda/Aura) | Clinical question answering from indexed guidelines; citations checked server-side, refuses when nothing relevant is indexed; 329 tests incl. Playwright | Python, FastAPI, Next.js, Postgres + pgvector |
| [ai-observability-platform](https://github.com/pranavkrishnadanda/ai-observability-platform) | Distributed log ingestion and real-time anomaly detection with Kafka + Claude Haiku | FastAPI, Kafka, Redis, PostgreSQL, React |

Driftline and Sluice were designed by me and built with AI coding agents; every change is checked by the tests and CI.

> Most of my production work at Oovacha is proprietary and lives outside public repos.

---

## Open source

- [botocore#3803](https://github.com/boto/botocore/pull/3803) — Fix for a `ReferenceError` in `RequestSigner` when the signer outlives its session.

---

## What I write about

I document engineering decisions, failure modes, and lessons from building AI systems in production:

- [I Gave an AI Agent Access to a Production Database](https://pranavkrishna.hashnode.dev/i-gave-an-ai-agent-access-to-a-production-database-here-s-what-actually-happened)
- [Building a Thinking-First Multi-Agent Room](https://pranavkrishna.hashnode.dev/building-a-thinking-first-multi-agent-room-not-another-fake-agent-demo)

More at [pranavkrishna.hashnode.dev](https://pranavkrishna.hashnode.dev).

---

## Let's connect

- [LinkedIn](https://www.linkedin.com/in/pranavkrishnadanda/)
- [Portfolio](https://pranavkrishnadanda.github.io/)
- [Email](mailto:pranavkrishna317@gmail.com)

Open to full-time Software Engineer roles in **backend** and **AI systems**, in Hyderabad or Bengaluru.
