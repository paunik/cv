# Nikola Paunović

### Senior Backend Engineer & Team Lead

Berlin, Germany · EU work authorization (German permanent residency) · German B1/B2

[nikola.paunovic1511@gmail.com](mailto:nikola.paunovic1511@gmail.com) · [LinkedIn](https://www.linkedin.com/in/nikola-paunović-np) · [GitHub](https://github.com/paunik) · [weekpace.com](https://weekpace.com)

---

## Summary

Backend engineer with 10+ years building and owning data-heavy consumer systems. Deep on Go and PostgreSQL at scale — recently cut a hot user-stats endpoint from ~20 s to sub-200 ms on a 400 GB+ database. Hands-on daily with Claude Code and agentic stacks (LangGraph, Mem0, pgvector).

---

## Experience

### Senior Software Developer & Team Lead — [Gaiali](https://get-yuno.com/) / Yuno
_June 2021 – Present · Berlin_

General-knowledge audio learning app (10-minute stories and quizzes). 1M–10M downloads, 10k–30k monthly active users.

- Cut user-stats endpoint p95 latency from **~20 s to under 200 ms** (100× improvement) through query redesign and targeted indexing on a 400 GB+ Postgres database.
- Own end-to-end Postgres performance on the 400 GB+ database — schema design, query tuning, index strategy, vacuum/autovacuum — and set the conventions the rest of the team follows.
- Drove the backend reliability work that brought on-call pages to under 1 per month, with clear escalation paths and runbooks for the services I own.
- Designed Redis-backed async pipelines for notifications and content processing, handling 2M+ notifications per month; chose Redis over heavier queues to keep the stack simple for a small team.
- Integrated Claude Code into my daily workflow; measurably faster feature delivery and cleaner diffs, and established the team patterns for AI-assisted development.
- Mentored 4 engineers on Go, Postgres, and system design as the backend team grew from 2 to 4; run architecture reviews and code reviews as the final technical owner.
- Prototyping agentic features with LangGraph, Mem0, and pgvector to extend product capabilities into adaptive learning.

**Stack:** Go, Vapor (Swift), Postgres, Redis, TypeScript, React, Next.js, Python, AWS, Heroku.

### Senior Software Developer — [LegalOne GmbH](https://legal.one/)
_June 2017 – May 2021 · Berlin_

German traffic-law SaaS, 50+ microservices.

- Shipped and owned 7+ production Go services; used CQRS to let read and write paths scale and evolve independently.
- Wrote services test-first with Gherkin-style specs and automated end-to-end tests, making behavioural intent explicit and catching regressions before deploy.
- Built async workflows in RabbitMQ — event logs, retries, and dead-letter queues — so downstream services recovered cleanly when producers failed.
- Used Elasticsearch as a read-side cache to take pressure off the write-path databases for read-heavy screens.
- Delivered across Go and PHP/Symfony side by side, owning features end-to-end; deployed on Kubernetes with Helm.

**Stack:** Go, PHP (Symfony), Vue, Docker, Kubernetes, AWS, Elastic Stack, RabbitMQ, MySQL, MongoDB.

### Senior Software Developer — [HolyCode](https://www.holycode.rs/) (Knip AG, insurance)
_February 2016 – November 2016_

- Built a custom CRM with NLP/OCR pipelines that automated insurance-document intake and cut manual data entry for the operations team.
- Delivered client-facing backend APIs and external-service integrations for the core insurance workflow.

**Stack:** PHP (Symfony), React, Python (NLP/OCR), MySQL, Memcached, Docker, Kubernetes, AWS.

### Software Developer — [Htec](https://htecgroup.com/)
_February 2015 – February 2016_

- Delivered custom CRM solutions for multiple clients in an outsourced model; PHP/Symfony, Angular, Docker, Kubernetes, MySQL, MongoDB.

---

## Side Projects

### [WeekPace](https://weekpace.com)

- Shipped a privacy-first Apple Watch running app in Swift; live on the App Store as a solo side project.
- Building a running-coach agent on top (LangGraph, Mem0, pgvector on FastAPI) — testbed for the memory, retrieval, and tool-calling patterns I'm bringing into day-job work.
- [Why I'm building WeekPace](./running.html)

---

## Technical Skills

- **Languages:** Go (production), Swift, PHP, TypeScript, Python
- **Databases:** PostgreSQL (advanced), Redis, MySQL, MongoDB, Elasticsearch
- **AI & Agentic:** Claude Code (daily), LangGraph, Mem0, pgvector, FastAPI, RAG
- **Infra & Cloud:** AWS, Kubernetes, Docker, Helm, Heroku
- **Messaging:** RabbitMQ, event-driven / CQRS patterns
- **Practices:** Microservices, CQRS, REST, gRPC, CI/CD, observability

---

## Education

**Bachelor's Degree, Computer Science** — [VISER](https://www.viser.edu.rs/?userLanguage=eng), Belgrade, Serbia · 2006 – 2009
