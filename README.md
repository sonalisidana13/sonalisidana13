<p align="center">
  <img src="banner.svg" alt="Sonali Sidana — Senior Software Engineer & Tech Lead" width="100%" />
</p>

<br>

---

## 🔧 Tech Stack

<p align="center">

**Backend**<br>
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge&logo=fastapi&logoColor=white)

**Cloud & Infrastructure**<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure_Blob-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)

**Data & Search**<br>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**Observability**<br>
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![New Relic](https://img.shields.io/badge/New_Relic-008C99?style=for-the-badge&logo=newrelic&logoColor=white)

**Frontend**<br>
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![AngularJS](https://img.shields.io/badge/AngularJS-E23237?style=for-the-badge&logo=angularjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</p>

---

## 🏗 Personal Projects

### 📬 Event-Driven Notification Service with Rate Limiting
> `Java 21` `Spring Boot 3.2` `Apache Kafka` `Redis` `PostgreSQL` `Prometheus` `Docker`
> &nbsp; **[[GitHub ↗]](https://github.com/sonalisidana13/notification-service)**

Three independent microservices — `ingest → enricher → dispatcher` — with separate Kafka topics. Redis sliding window rate limiter via atomic Lua script (`EVALSHA`), partitioned by `userId/channel/tenant`. At-least-once delivery with idempotency; DLQ with exponential backoff + full jitter.

---

### 🗂 Cloud-Agnostic File Storage Microservice
> `Spring Boot 3` `PostgreSQL` `Cloudflare R2` `AWS S3` `Docker` `Flyway`
> &nbsp; **[[GitHub ↗]](https://github.com/sonalisidana13/Cloud-Agnostic-File-Storage-Microservice)** · **[[Live Demo ↗]](https://cloud-agnostic-file-storage-microse.vercel.app/)**

Pluggable `StorageProvider` abstraction (Cloudflare R2 / AWS S3) switchable via a single env var. Presigned URL flow bypasses the backend entirely. Tenant-scoped lifecycle tracking (`PENDING → UPLOADED → FAILED`) with a reconciliation poller that auto-recovers stale uploads every 60s.

---

### 🤖 AI Incident Explainer *(in progress)*
> `Java` `Elasticsearch` `Prometheus` `LLM APIs`
> &nbsp; **[[GitHub ↗]](https://github.com/sonalisidana13/Incident-Explainer)**

AI-powered tool that correlates logs and metrics to explain production incidents — RAG-based knowledge retrieval over historical incident data.

---

## 👩‍💻 About Me

Backend engineer with 6+ years building and scaling distributed systems — progressed from engineer to Tech Lead while staying hands-on in Java, Spring Boot, and AWS. I enjoy designing resilient architectures and diving deep into observability and reliability problems.

---

## 🧠 Currently Exploring

- Advanced distributed systems patterns
- AI-assisted engineering workflows
- Event-driven architecture at scale

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=sonalisidana13&theme=github_dark" width="100%" alt="GitHub Activity"/>
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=sonalisidana13&theme=github_dark" height="160" alt="Repos Per Language"/>
  &nbsp;&nbsp;
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=sonalisidana13&theme=github_dark" height="160" alt="Most Used Language"/>
</p>

---

## 🌍 Connect

<p align="center">
  <a href="https://sonalisidana.com"><img src="https://img.shields.io/badge/Portfolio-sonalisidana.com-0d1117?style=for-the-badge&logo=google-chrome&logoColor=5DCAA5&labelColor=0d1117&color=1D9E75"/></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/sonali-sidana-1310/"><img src="https://img.shields.io/badge/LinkedIn-sonali--sidana--1310-0d1117?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117&color=534AB7"/></a>
  &nbsp;
  <a href="mailto:sonalisidana13@gmail.com"><img src="https://img.shields.io/badge/Email-sonalisidana13@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117&color=D85A30"/></a>
</p>

<br>

<p align="center">
  <sub>⭐ I build systems that <strong>scale under load, stay observable, and solve real problems.</strong></sub>
</p>
