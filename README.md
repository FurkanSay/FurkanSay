<div align="center">

# Furkan Say

### AI-Augmented Backend Engineer · C# / .NET · Python · Polyglot Microservices

[![Location](https://img.shields.io/badge/Adana-Türkiye-0A66C2?style=flat-square&logo=googlemaps&logoColor=white)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-furkansay-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/furkansay)
[![Email](https://img.shields.io/badge/Email-info@furkansay.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:info@furkansay.com)
[![Profile views](https://komarev.com/ghpvc/?username=FurkanSay&style=flat-square&color=blue)](#)

</div>

---

### About

Backend engineer with **5+ years** of production C# / .NET experience. I design enterprise REST APIs and microservices grounded in **Clean Architecture, DDD, and CQRS**, and I care about the numbers behind them — cut a critical endpoint's p95 from **850 ms → 120 ms (−85%)** and reduced hot SQL queries by **60%** through stored-procedure refactoring and index tuning.

Currently building **AI-augmented backends**: RAG pipelines, vector databases, and LLM integration. M.Sc. thesis on **Cross-Species IMU Behavior Recognition via Domain Adaptation** (PyTorch · DANN · BiLSTM-Attention · cWGAN-GP).

📌 *Open to Backend / AI Engineer roles — EU & remote.*

---

### Tech Stack

**Languages**

![C#](https://img.shields.io/badge/-C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Backend & Frameworks**

![.NET](https://img.shields.io/badge/-.NET%2010-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/-ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/-EF%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![MediatR](https://img.shields.io/badge/-MediatR-512BD4?style=flat-square)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

**Architecture**

`Clean Architecture` · `Domain-Driven Design` · `CQRS` · `Outbox Pattern` · `Event-Driven` · `Microservices` · `SOLID` · `DRY` · `KISS`

**Databases & Caching**

![SQL Server](https://img.shields.io/badge/-SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)

**Messaging & Integration**

![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![gRPC](https://img.shields.io/badge/-gRPC-244C5A?style=flat-square&logo=google&logoColor=white)
![MQTT](https://img.shields.io/badge/-MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![WebSockets](https://img.shields.io/badge/-WebSockets-010101?style=flat-square)
`Modbus TCP` · `Webhooks`

**AI / ML**

![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/-Anthropic-D97757?style=flat-square&logo=anthropic&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
`RAG Pipelines` · `Vector Databases` · `Prompt Engineering` · `Domain Adaptation`

**DevOps & Tooling**

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Testcontainers](https://img.shields.io/badge/-Testcontainers-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### Featured Projects

#### [enterprise-ai-assistant](https://github.com/FurkanSay/enterprise-ai-assistant) · Multi-tenant RAG Platform

Polyglot microservices showcase: **5 languages, 6 services**, gRPC-typed contracts in a single monorepo.

| Service | Stack | Role |
|---|---|---|
| Gateway · Identity | C# .NET 10 | Reverse proxy (YARP) · Auth · Tenant isolation |
| Documents | Java · Spring Boot 3 | Transactional file ops · Metadata |
| Processing | Rust · Axum | CPU-bound chunking · BM25 (tantivy) |
| AI Engine | Python · FastAPI | Embeddings · RAG · LLM orchestration |
| Realtime | TypeScript · NestJS | WebSocket fan-out |
| Frontend | Next.js | Chat UI · RAG citations · streaming |

> Multi-tenant SaaS · Qdrant vectors · OpenTelemetry first-class · grounded RAG with citations & session forking.

---

#### NexusPLC · Real-time PLC Monitoring & Control

C# / WPF desktop app unifying **Modbus TCP (WEG, Delta) + snap7 (Siemens) + MQTT** behind a single communication layer. Redis caching, RabbitMQ fan-out for mobile clients.

---

#### M.Sc. Thesis · Cross-Species IMU Behavior Recognition

Domain Adaptation deep learning pipeline in PyTorch — three-phase training protocol combining **DANN + BiLSTM-Attention + cWGAN-GP** across a 72-experiment comparison matrix.

---

### Production Highlights

- ⚡ **API p95 latency: 850 ms → 120 ms (−85%)** — profiling + async strategy refactor
- 🗄️ **Hot SQL queries: −60% runtime** — stored procedure refactor + index optimization
- 🔄 **Outbox Pattern + RabbitMQ** event-driven pipeline for cross-service eventual consistency
- 🚢 Shipped **GoEksper SaaS** end-to-end as sole engineer (backend + UI, production)

---

### Education & Certifications

- 🎓 **M.Sc. Computer Engineering** · Mersin University · 2023–2026 · GPA 3.60 / 4.00
- 🎓 **B.Sc. Computer Engineering** · Adana ATÜ · 2018–2022
- 📜 Microsoft ASP.NET Core Developer Professional Certificate · Coursera, 2024
- 📜 Foundational C# Certification · Microsoft & freeCodeCamp, 2023

---

### GitHub Stats

<div align="center">

<a href="https://github.com/FurkanSay">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=FurkanSay&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=default" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=FurkanSay&layout=compact&hide_border=true&langs_count=8&theme=default" />
</a>

</div>

---

<div align="center">

### Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Furkan%20Say-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/furkansay)
[![Email](https://img.shields.io/badge/Email-info@furkansay.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:info@furkansay.com)
[![GitHub](https://img.shields.io/badge/GitHub-FurkanSay-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/FurkanSay)

</div>
