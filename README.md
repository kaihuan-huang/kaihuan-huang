# Kaihuan Huang

AI engineer building LLM agents for money-moving workflows, with the controls finance teams need to go agentic: eval gates before launch, human confirmation before any agent action, audit trails, PII masking and duplicate-free processing. San Francisco Bay Area · US permanent resident.

## Live demos

| Demo | What it shows |
|---|---|
| [Refund Agent](https://kaihuan-huang.github.io/refund-agent-demo/) | An LLM agent that proposes refunds with tool calls but can't move money: fixed checks, human approval, then a hash-chained ledger entry. Includes a recorded run where the model over-refunds and the approver catches it. |
| [Booking Agent](https://kaihuan-huang.github.io/booking-agent-demo/) | A bilingual (English / 中文) booking agent that books only on an explicit yes. The model-only pilot got 57% of messages right; rules plus a confirmation gate got 85% with 0 invented values. Compare against your own local LLM, and see [what is inside that model](https://kaihuan-huang.github.io/booking-agent-demo/model-architecture.html). |
| [Tamper-Evident Ledger](https://kaihuan-huang.github.io/ledger-demo/) | Payments, refunds and voids as a hash-chained event log. Edit, delete or rewrite a row and verification points to it. |
| [PII Detector](https://kaihuan-huang.github.io/pii-detector-demo/) | Finds cards, emails, phones and API keys before text reaches a model. The model runs in your browser with 0 network requests; its [architecture card](https://kaihuan-huang.github.io/pii-detector-demo/model-architecture.html) explains why a 1.4B mixture-of-experts fits there. |
| [LLM Architecture Cards](https://kaihuan-huang.github.io/llm-arch-viz/) | What is inside an open-weight model, from its config alone: attention layout, FFN, parameter split, one decoder layer with weight shapes, memory arithmetic, cross-checked against the Hub. [Source](https://github.com/kaihuan-huang/llm-arch-viz), MIT. |

## Work

- **AI Engineer, [IPOT (Jackson Ventures)](https://ipot.food/)** (Apr 2026–present): rebuilt Nalu, the bilingual booking agent, after measuring the LLM-only pilot at 57% (now 85%, 0 invented values, eval gate in CI; in pre-launch testing); built the Reservation API from the first commit, now in production with real guests; own POS money movement (atomic settlement, tips, refunds, audited voids).
- **AI Engineer Intern, [Polygraf.ai](https://www.polygraf.ai/)** (Oct 2025–Jun 2026): layered English/Chinese PII detector, a pure-function policy engine, masked LLM chat, and a Postgres transactional-outbox pipeline feeding a hash-chained audit trail.
- **MSc Computer Science with Artificial Intelligence**, University of York (2025) · Certificate in Full Stack Web Development, UC Berkeley Extension (2022).

**Stack:** Python, FastAPI, SQLAlchemy 2.0, PostgreSQL (pgvector), Redis · TypeScript, React / Next.js · Ollama, Claude Code · AWS (ECS Fargate, RDS, KMS), OpenTofu, Docker, GitHub Actions, Twilio.
**Spoken:** English, Mandarin, Cantonese, Spanish.

[LinkedIn](https://linkedin.com/in/kaihuanhuang/)
