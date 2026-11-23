<div align="center">

# Saravana Thiyagarajan

**Senior Backend Engineer · Payments & Distributed Systems**

Bengaluru, India

[Portfolio](https://thebackendguy.dev) · [LinkedIn](https://www.linkedin.com/in/saravana-sai/) · [Substack](https://saravanasai.substack.com/) · [Hashnode](https://saravanasai.hashnode.dev/) · [X](https://x.com/Sai_Saravana_)

</div>

<br>

I build backend systems that move money and can't afford to be wrong.

Most recently I owned the architecture of a Go payment platform serving **1.8M+ users at 300+ TPS**, built around an immutable double-entry ledger. Over five years, the common thread in my work has been **reliability, correctness and performance at scale**: from lending systems to logistics APIs to payments infrastructure.

<br>

## Selected work

**Payments platform & financial ledger** · *Aura Gold* · Go, PostgreSQL, AWS SNS/SQS<br>
Designed the immutable ledger that became the system of record for customer balances: atomic multi-entry postings, reversals, reconciliation, full audit trail and point-in-time balance reconstruction. Built event-driven payment workflows with idempotent consumers and exactly-once business semantics, and a modular workflow engine (validation → pricing → ledger posting → notifications → events) that lets new payment flows ship without compromising consistency.

**Shared platform services & RAG** · *Upland Software* · Go, Node.js<br>
Built reusable backend services adopted across multiple SaaS products, and a retrieval-augmented generation service that unified knowledge from several enterprise systems (+15% engagement). Moved long-running report generation to async workers with WebSocket progress, taking it from minutes to near real-time.

**Logistics API performance** · *Nextbrain* · Node.js, Redis, SQL<br>
Cut API response time 10x (~3s → <300ms) for a last-mile delivery platform handling 40K+ daily requests, through caching, query optimisation and CDN integration.

<br>

## Open source

| Project | What it is |
|:--|:--|
| [**goqueue**](https://github.com/saravanasai/goqueue) | ★ 225+ &nbsp;·&nbsp; Job queue for Go with pluggable in-memory, Redis and AWS SQS backends. Retries, DLQ, middleware pipeline, graceful shutdown. |
| [**stream&#8209;pulse**](https://github.com/saravanasai/stream-pulse) | Event-driven architecture for Laravel on Redis Streams. |
| [**loadbalancer**](https://github.com/saravanasai/loadbalancer) | HTTP load balancer in Go: connection pooling, round-robin routing, health checks. |

<br>

## Experience

| Role | Company | Years |
|:--|:--|:--|
| **Senior Backend Engineer** | Aura Gold | 2025 – 2026 |
| **Software Development Engineer** | Upland Software | 2023 – 2025 |
| **Software Engineer** | Nextbrain | 2022 – 2023 |
| **PHP Developer** | Exciteon | 2021 – 2022 |

<br>

## Writing

- [A Story About Indexes, Filters, and Where Databases Bend](https://saravanasai.substack.com/p/a-story-about-indexes-filters-and)
- More on databases, protocols and backend internals on [Substack](https://saravanasai.substack.com/) and [Hashnode](https://saravanasai.hashnode.dev/)

<br>

## Toolkit

<img src="https://skillicons.dev/icons?i=go,py,nodejs,ts,php,postgres,mysql,redis,kafka,mongodb,aws,docker,githubactions&perline=13" alt="Go, Python, Node.js, TypeScript, PHP, PostgreSQL, MySQL, Redis, Kafka, MongoDB, AWS, Docker, GitHub Actions" />

**Interested in** payments infrastructure, distributed systems and platform engineering.
