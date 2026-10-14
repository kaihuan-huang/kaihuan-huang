# Kaihuan Huang

Backend / AI engineer building financial APIs, AI-assisted reviews and data pipelines in Python and Go, with FastAPI and PostgreSQL. San Francisco Bay Area · US permanent resident.

**Portfolio:** [kaihuan-huang.github.io](https://kaihuan-huang.github.io/), with twelve case studies, each number linked to where it was measured.

## Live demos

| Demo | What it shows |
|---|---|
| [Booking Agent](https://kaihuan-huang.github.io/booking-agent-demo/) | Bilingual (English / 中文) booking agent that books only on an explicit yes. On Nalu, rules plus a confirmation gate took held-out accuracy from 57% (model-only) to 85% (33/39) with 0 invented values. 31 tests. |
| [POS Platform](https://kaihuan-huang.github.io/ledger-demo/) | Run a restaurant shift; every tap is one transaction with its rows traced. Idempotent bookings, manager-approved refunds. 29 tests. |
| [Refund Agent](https://kaihuan-huang.github.io/refund-agent-demo/) | An LLM proposes refunds through tool calls but can't move money: fixed checks, human approval, hash-chained ledger. 16 tests. |
| [PII Detector](https://kaihuan-huang.github.io/pii-detector-demo/) | Masks cards, emails, phones and keys before text reaches a model; the local model runs on WebGPU with 0 network requests. |
| [Career OPS](https://kai-careerops.westus2.cloudapp.azure.com) | Job-market feed from employer ATS APIs (264,148 postings in the Sep 30 snapshot), extending open-source career-ops. |
| [Dispute Ingestion Service](https://github.com/kaihuan-huang/dispute-ingest) | Go prototype on synthetic card disputes: idempotent ingestion (20 concurrent redeliveries create one record), simplified Reg E / Reg Z deadlines, manual review for fraud signals, hash-chained ledger. `go test -race`. |
| [LLM Architecture Cards](https://kaihuan-huang.github.io/llm-arch-viz/) | What is inside an open-weight model, from its config alone. [Source](https://github.com/kaihuan-huang/llm-arch-viz), MIT. |

## Work

- **AI Engineer, Jackson Ventures** (Apr 2023–present): reservation service in production with real guests; IPOT POS backend (atomic settlement, refunds, audited voids); rebuilt Nalu, the bilingual booking agent (pre-launch); loan-draw review controls and a release gate for BloomFrontier (merged Oct 2026).
- **AI Engineer Intern, [Polygraf.ai](https://www.polygraf.ai/)** (Oct 2025–Jun 2026): PII detection and policy enforcement for text sent to AI tools; governance dashboard.
- **Founding Engineer, REAAI** (Feb 2022–Apr 2023): full-stack real-estate platform (Next.js, Node.js, MongoDB) on Azure.
- **MSc Computer Science with Artificial Intelligence**, University of York (Online, Sep 2023–Jan 2026).

**Stack:** Python, Go, FastAPI, SQLAlchemy, PostgreSQL (pgvector), Temporal · TypeScript, React / Next.js · Ollama · AWS, Azure, OpenTofu, Docker, GitHub Actions.

[Email](mailto:huangkaihuan0216@gmail.com) · [LinkedIn](https://linkedin.com/in/kaijacksonus/) · [Résumé](https://kaihuan-huang.github.io/resume.html)
