# Hi, I'm Saravana 👋

### Senior Backend Engineer · Payments & Distributed Systems

I build backend systems that move money and can't afford to be wrong.
Built a ledger + payment platform serving **1.8M+ users** at **300+ TPS** · Creator of [**GoQueue**](https://github.com/saravanasai/goqueue) · Bengaluru, India 🇮🇳

[![LinkedIn](https://img.shields.io/badge/LinkedIn-saravana--sai-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saravana-sai/)
[![Substack](https://img.shields.io/badge/Substack-saravanasai-FF6719?logo=substack&logoColor=white)](https://saravanasai.substack.com/)
[![Hashnode](https://img.shields.io/badge/Hashnode-blog-2962FF?logo=hashnode&logoColor=white)](https://saravanasai.hashnode.dev/)
[![X](https://img.shields.io/badge/X-Sai__Saravana__-000000?logo=x&logoColor=white)](https://x.com/Sai_Saravana_)

---

## 🧑‍💻 About Me

- **5+ years** building backend systems where reliability, correctness and performance at scale matter.
- Owned the architecture of a **Go-based payment platform** with an **immutable double-entry ledger** as the system of record for customer balances.
- Built **event-driven workflows** (SNS/SQS + PostgreSQL) with idempotent consumers and exactly-once business semantics.
- Earlier: shared platform services and a **RAG-based AI service** at Upland Software, a **10x API latency cut** (~3s → <300ms) at Nextbrain, and **lending systems for 50,000+ borrowers**.
- Interested in **payments infrastructure, distributed systems and platform engineering**.

---

## 💼 Experience

| Role | Company | Period | Highlights |
|---|---|---|---|
| **Senior Backend Engineer** | Aura Gold™ | Dec 2025 – Sep 2026 | Go payment platform for 1.8M+ users at 300+ TPS · immutable financial ledger with reversals, reconciliation & point-in-time balances · modular payment workflow engine |
| **Creator & Maintainer** | [GoQueue](https://github.com/saravanasai/goqueue) | Aug 2025 – Mar 2026 | Open-source Go job queue (225+ ⭐) with pluggable in-memory, Redis and AWS SQS backends |
| **Software Development Engineer I** | Upland Software | Nov 2023 – Dec 2025 | RAG service (+15% engagement) · async report generation with WebSocket progress · reusable platform services across SaaS products |
| **Software Engineer** | Nextbrain | Nov 2022 – Nov 2023 | API response ~3s → <300ms · last-mile delivery backend (40K+ daily requests) · multi-tenant Digital Signage SaaS |
| **PHP Developer** | Exciteon | Jun 2021 – Aug 2022 | Loan management system for 50K+ users · LoanStories loan origination + CRM · shared RBAC & rewards modules |

---

## 🔧 Tech Stack

**Languages**
Go • Python • Node.js / TypeScript • PHP

**Frameworks**
FastAPI • Express / NestJS • Laravel

**Data & Messaging**
PostgreSQL • MySQL • MSSQL • MongoDB • Redis • Kafka • ClickHouse

**Cloud & DevOps**
AWS (SNS, SQS, ECS, EKS, EC2, RDS, S3, VPC) • Docker • GitHub Actions

**Focus Areas**
Payment Systems • Financial Ledgers • Event-Driven Architecture • Distributed Systems • System Design • Database Internals

---

## 📌 Featured Projects

### [GoQueue](https://github.com/saravanasai/goqueue) ⭐ 225+
The flexible Go job queue that grows with you: start in-memory for development, scale to Redis for production, or deploy to AWS SQS in the cloud.
- Pluggable backends, so you can switch infrastructure without changing application code.
- Built-in retries, dead-letter queues, middleware pipeline, graceful shutdown and observability.

### [Laravel Stream-Pulse](https://github.com/saravanasai/stream-pulse)
Laravel package for **Event-Driven Architecture** using Redis Streams.
- Scalable event publishing and consuming directly inside Laravel.
- Suited to real-time apps and microservice event workflows.

### [Load Balancer (Go)](https://github.com/saravanasai/loadbalancer)
Custom HTTP load balancer exploring **connection pooling, round-robin routing and backend health checks**.

---

## ✍️ Writing & Talks

- 📝 [**A Story About Indexes, Filters, and Where Databases Bend**](https://saravanasai.substack.com/p/a-story-about-indexes-filters-and): indexes on every column, a query returning 20 rows, and CPU still spiked. A deep dive into why.
- 📚 More on databases, protocols, load balancing and backend internals on [Substack](https://saravanasai.substack.com/) and [Hashnode](https://saravanasai.hashnode.dev/).
- 🎤 Tech talks on the Node.js event loop, thread pool contention and deployment strategies.

---

*"Great engineering is not just about code — it's about designing systems that scale, adapt, and endure."*
