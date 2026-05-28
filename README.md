# Hi there, I'm Sonali Sidana 👋

🚀 **Senior Software Engineer · Tech Lead · Backend & Platform**

Backend platform engineer with 6+ years scaling a SaaS from 20K to 300K+ users across 200+ institutions — progressed from engineer to Tech Lead owning an 8-person team while staying hands-on in Java, Spring Boot, AWS, and distributed systems.

I specialize in **distributed systems**, **microservices architecture**, **cloud infrastructure**, and **observability-driven engineering**. I enjoy solving complex reliability and scalability problems at production scale.

[![Profile Views](https://visitor-badge.laobi.icu/badge?page_id=sonalisidana13.sonalisidana13)](https://github.com/sonalisidana13)

---

## 🔧 Tech Stack

**Backend**
Java · Spring Boot · REST APIs · Microservices · Apache Kafka · Redis

**Cloud & Infrastructure**
AWS (EC2, S3, RDS, Lambda, SQS, CloudWatch, Athena) · Azure Blob · DigitalOcean Spaces · Docker

**Data**
MySQL · Elasticsearch (multi-node) · PostgreSQL · NoSQL

**Observability**
Prometheus · Grafana · Loki · New Relic · JavaMelody

**Frontend**
ReactJS · AngularJS · JavaScript (ES6)

---

## 🏗 Projects

### 📬 Event-Driven Notification Service with Rate Limiting
*Java 21 · Spring Boot 3.2 · Apache Kafka · Redis · PostgreSQL · Prometheus · Docker*
&nbsp;[[GitHub]](https://github.com/sonalisidana13/notification-service)

- Architected 3 independent Spring Boot microservices (ingest → enricher → dispatcher) with intentionally separate Kafka topics — decoupling domain events from notification intent for independent replay, versioning, and consumer scaling.
- Implemented a Redis sliding window rate limiter via atomic Lua script (EVALSHA), partitioned by `userId/channel/tenant` — chose sliding window over token bucket to prevent burst accumulation.
- Designed at-least-once delivery with application-level idempotency via a `delivery_log` table; DLQ with exponential backoff + full jitter prevents thundering herd on mass failures.

---

### 🗂 Cloud-Agnostic File Storage Microservice
*Spring Boot · PostgreSQL · Cloudflare R2 · AWS S3 · Docker · Flyway · Render*
&nbsp;[[GitHub]](https://github.com/sonalisidana13/Cloud-Agnostic-File-Storage-Microservice) · [[Live Demo]](https://cloud-agnostic-file-storage-microse.vercel.app/)

- Personal implementation of the cloud-agnostic storage architecture I designed at Digii — built end-to-end in Spring Boot 3 to validate the HLD at a smaller scale.
- Pluggable `StorageProvider` abstraction (Cloudflare R2 / AWS S3) switchable via a single env var; presigned URL flow ensures files upload directly to storage, bypassing the backend entirely.
- Tenant-scoped metadata in PostgreSQL (Flyway) tracking full file lifecycle (`PENDING → UPLOADED → FAILED`); reconciliation poller auto-recovers stale uploads every 60s.

---

### 🤖 AI Incident Explainer *(in progress)*
*Java · Elasticsearch · Prometheus · LLM APIs*
&nbsp;[[GitHub]](https://github.com/sonalisidana13/Incident-Explainer)

- AI-powered tool that correlates logs and metrics to explain production incidents — RAG-based knowledge retrieval over historical incident data.

---

## 💡 What I've Built at Scale

- **Cloud-agnostic attachment microservice** — extracted from monolith, supports AWS S3 / Azure Blob / DigitalOcean Spaces across 30TB of data and 50+ product modules; reduced cloud storage costs by 50%.
- **Multi-node Elasticsearch architecture** — eliminated single-node downtime, layered Redis caching (event-driven invalidation + TTL), cut ES call volume by 50% and search latency by 40% under 1,000 concurrent users.
- **Multi-tenant outage diagnosis & fix** — identified JVM thread pool exhaustion via New Relic, isolated tenant onto a dedicated EC2 fleet, restored availability within 2 minutes.
- **Observability stack from scratch** — Prometheus, Grafana, Loki, New Relic, JavaMelody; proactive SLO tracking and incident detection across all production services.

---

## 🧠 Engineering Interests

- Distributed systems design and reliability
- Observability-driven engineering
- Cloud infrastructure optimization
- Event-driven architectures
- AI-assisted engineering workflows

---

## 🏆 LeetCode

[![LeetCode Stats](https://leetcard.jacoblin.cool/sonali_sidana?theme=dark&font=Monospace)](https://leetcode.com/sonali_sidana/)

---

## 🌍 Connect

[![Portfolio](https://img.shields.io/badge/Website-sonalisidana.com-black?style=flat&logo=Google-Chrome&logoColor=white)](https://sonalisidana.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/sonali-sidana-1310/)
[![GitHub](https://img.shields.io/badge/-GitHub-black?style=flat&logo=github)](https://github.com/sonalisidana13)
[![Email](https://img.shields.io/badge/Email-me-red?style=flat&logo=gmail)](mailto:sonalisidana13@gmail.com)

---

⭐ I build systems that **scale under load, stay observable in production, and solve real problems.**# Hi there, I'm Sonali Sidana 👋

🚀 **Senior Software Engineer · Tech Lead · Backend & Platform**

Backend platform engineer with 6+ years scaling a SaaS from 20K to 300K+ users across 200+ institutions — progressed from engineer to Tech Lead owning an 8-person team while staying hands-on in Java, Spring Boot, AWS, and distributed systems.

I specialize in **distributed systems**, **microservices architecture**, **cloud infrastructure**, and **observability-driven engineering**. I enjoy solving complex reliability and scalability problems at production scale.

[![Profile Views](https://visitor-badge.laobi.icu/badge?page_id=sonalisidana13.sonalisidana13)](https://github.com/sonalisidana13)

---

## 🔧 Tech Stack

**Backend**
Java · Spring Boot · REST APIs · Microservices · Apache Kafka · Redis

**Cloud & Infrastructure**
AWS (EC2, S3, RDS, Lambda, SQS, CloudWatch, Athena) · Azure Blob · DigitalOcean Spaces · Docker

**Data**
MySQL · Elasticsearch (multi-node) · PostgreSQL · NoSQL

**Observability**
Prometheus · Grafana · Loki · New Relic · JavaMelody

**Frontend**
ReactJS · AngularJS · JavaScript (ES6)

---

## 🏗 Projects

### 📬 Event-Driven Notification Service with Rate Limiting
*Java 21 · Spring Boot 3.2 · Apache Kafka · Redis · PostgreSQL · Prometheus · Docker*
&nbsp;[[GitHub]](https://github.com/sonalisidana13/notification-service)

- Architected 3 independent Spring Boot microservices (ingest → enricher → dispatcher) with intentionally separate Kafka topics — decoupling domain events from notification intent for independent replay, versioning, and consumer scaling.
- Implemented a Redis sliding window rate limiter via atomic Lua script (EVALSHA), partitioned by `userId/channel/tenant` — chose sliding window over token bucket to prevent burst accumulation.
- Designed at-least-once delivery with application-level idempotency via a `delivery_log` table; DLQ with exponential backoff + full jitter prevents thundering herd on mass failures.

---

### 🗂 Cloud-Agnostic File Storage Microservice
*Spring Boot · PostgreSQL · Cloudflare R2 · AWS S3 · Docker · Flyway · Render*
&nbsp;[[GitHub]](https://github.com/sonalisidana13/Cloud-Agnostic-File-Storage-Microservice) · [[Live Demo]](https://cloud-agnostic-file-storage-microse.vercel.app/)

- Personal implementation of the cloud-agnostic storage architecture I designed at Digii — built end-to-end in Spring Boot 3 to validate the HLD at a smaller scale.
- Pluggable `StorageProvider` abstraction (Cloudflare R2 / AWS S3) switchable via a single env var; presigned URL flow ensures files upload directly to storage, bypassing the backend entirely.
- Tenant-scoped metadata in PostgreSQL (Flyway) tracking full file lifecycle (`PENDING → UPLOADED → FAILED`); reconciliation poller auto-recovers stale uploads every 60s.

---

### 🤖 AI Incident Explainer *(in progress)*
*Java · Elasticsearch · Prometheus · LLM APIs*
&nbsp;[[GitHub]](https://github.com/sonalisidana13/Incident-Explainer)

- AI-powered tool that correlates logs and metrics to explain production incidents — RAG-based knowledge retrieval over historical incident data.

---

## 💡 What I've Built at Scale

- **Cloud-agnostic attachment microservice** — extracted from monolith, supports AWS S3 / Azure Blob / DigitalOcean Spaces across 30TB of data and 50+ product modules; reduced cloud storage costs by 50%.
- **Multi-node Elasticsearch architecture** — eliminated single-node downtime, layered Redis caching (event-driven invalidation + TTL), cut ES call volume by 50% and search latency by 40% under 1,000 concurrent users.
- **Multi-tenant outage diagnosis & fix** — identified JVM thread pool exhaustion via New Relic, isolated tenant onto a dedicated EC2 fleet, restored availability within 2 minutes.
- **Observability stack from scratch** — Prometheus, Grafana, Loki, New Relic, JavaMelody; proactive SLO tracking and incident detection across all production services.

---

## 🧠 Engineering Interests

- Distributed systems design and reliability
- Observability-driven engineering
- Cloud infrastructure optimization
- Event-driven architectures
- AI-assisted engineering workflows

---

## 🏆 LeetCode

[![LeetCode Stats](https://leetcard.jacoblin.cool/sonali_sidana?theme=dark&font=Monospace)](https://leetcode.com/sonali_sidana/)

---

## 🌍 Connect

[![Portfolio](https://img.shields.io/badge/Website-sonalisidana.com-black?style=flat&logo=Google-Chrome&logoColor=white)](https://sonalisidana.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/sonali-sidana-1310/)
[![GitHub](https://img.shields.io/badge/-GitHub-black?style=flat&logo=github)](https://github.com/sonalisidana13)
[![Email](https://img.shields.io/badge/Email-me-red?style=flat&logo=gmail)](mailto:sonalisidana13@gmail.com)

---

⭐ I build systems that **scale under load, stay observable in production, and solve real problems.**
