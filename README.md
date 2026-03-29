# Emerson Busson

**Software Engineer** building production-grade distributed systems with Go, TypeScript, and PostgreSQL.

I architect multi-tenant SaaS platforms, design microservice ecosystems, and ship full-stack products from database schema to deploy pipeline. Currently building [Advoq](https://github.com/emersonbusson/advoq) — a multi-tenant legal tech SaaS with 8 microservices, schema-per-tenant isolation, and LGPD compliance.

---

### Stack

```
Backend       Go 1.26 | chi | pgx | go-redis | goose migrations
Frontend      Next.js 16 | React 19 | TypeScript | StyleX | Zustand | TanStack Query
Database      PostgreSQL 18 (schema-per-tenant) | PgBouncer | Redis 8
Infra         Docker | Nginx | PgBouncer | Prometheus | Grafana | OpenTelemetry | Tempo
Testing       Go testing + Testify | Vitest | Playwright E2E | Testcontainers
Other         Rust | OpenAPI (Spectral + codegen) | GitHub Actions CI/CD
```

---

### What I Build

**[Advoq](https://github.com/emersonbusson/advoq)** — Multi-tenant Legal SaaS Platform

Production-grade SaaS for law offices with full tenant lifecycle management — from provisioning to LGPD-compliant data deletion.

- **8 Go microservices** (auth, core, provisioner, billing, docs, chat, scheduler, notifications) with clean layered architecture (handler → service → repository)
- **Schema-per-tenant PostgreSQL** — 5 isolated schemas per tenant, `search_path` enforcement on every transaction, PgBouncer connection pooling
- **JWT Ed25519 auth** with key rotation, refresh token rotation, RBAC permissions, rate limiting, and bcrypt concurrency semaphore
- **CRM module** — lead funnel state machine, kanban board, analytics, custom fields (JSONB), WhatsApp auto-lead creation, scheduler automations
- **Full observability** — OpenTelemetry distributed tracing (W3C Trace Context), Prometheus metrics, Grafana dashboards, structured log correlation
- **Security hardening roadmap** — 23 issues across 5 sprints: HSTS/CSP headers, PII encryption (AES-256-GCM), RLS, 2FA TOTP, Go fuzzing, Trivy scans, LGPD right to erasure
- **300+ tracked issues**, Conventional Commits, OpenAPI specs with CI validation, Playwright E2E suites

**Other projects:**

| Project | Stack | Description |
| :--- | :--- | :--- |
| [rust-email-service](https://github.com/emersonbusson/rust-email-service) | Rust | High-performance email delivery service |
| [oberonOS](https://github.com/emersonbusson/oberonOS) | Low-level | Operating system project |
| [super-view-project](https://github.com/emersonbusson/super-view-project) | Go | CLI tooling and internal services |
| [IDMT](https://github.com/emersonbusson/IDMT) | Next.js, TypeScript | Full-stack web application |
| [agenor-criminal](https://github.com/emersonbusson/agenor-criminal) | Next.js, TypeScript | Criminal law office platform |

---

### Currently Working On

- Security hardening sprints for Advoq (RLS, token rotation, PII encryption, audit logs)
- Advanced task board with Kanban, subtasks, comments, labels, and time tracking
- Google Calendar bidirectional sync module
- LLM-powered legal document generation engine

---

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-emersonbusson-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emersonbusson/)
