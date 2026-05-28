<div align="center">

# Furkan Say

### AI Engineer · Backend Engineer · C# / .NET / Python / Rust / Java

[![Location](https://img.shields.io/badge/Adana-T%C3%BCrkiye%20·%20open%20to%20relocation%20%2F%20remote-0A66C2?style=flat-square&logo=googlemaps&logoColor=white)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-furkansay-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/furkansay)
[![Email](https://img.shields.io/badge/Email-info@furkansay.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:info@furkansay.com)
[![Website](https://img.shields.io/badge/Web-furkansay.com-1F4E79?style=flat-square&logo=googlechrome&logoColor=white)](https://furkansay.com)

</div>

---

### About

Backend engineer with **4+ years** of production C# / .NET experience. I design enterprise REST APIs and microservices on **Clean Architecture, DDD, and CQRS** — and I care about the numbers: cut a critical endpoint's latency **850 ms → 120 ms (−85%)** and reduced hot SQL queries by **60%** via stored-procedure and index tuning.

Now building **AI-augmented backends** — RAG pipelines, agent loops & tool calling, vector search and LLM integration, **built from primitives rather than frameworks**. M.Sc. thesis on **Transfer Learning & Domain Adaptation** for animal-behavior classification from wearable sensors.

📌 *Open to **AI Engineer / Backend** roles — remote & EU.*

---

### Tech Stack

**Languages**

![C#](https://img.shields.io/badge/-C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & Frameworks**

![.NET](https://img.shields.io/badge/-.NET%2010-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/-ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/-EF%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![MediatR](https://img.shields.io/badge/-MediatR-512BD4?style=flat-square)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)

`Clean Architecture` · `DDD` · `CQRS` · `Outbox Pattern` · `Event-Driven` · `Microservices` · `SOLID`

**Databases & Messaging**

![SQL Server](https://img.shields.io/badge/-SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![gRPC](https://img.shields.io/badge/-gRPC-244C5A?style=flat-square&logo=google&logoColor=white)

**AI / ML**

![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/-Anthropic-D97757?style=flat-square&logo=anthropic&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/-ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)

`RAG (from primitives)` · `Agent Loop & Tool Calling` · `RAGAS Eval` · `Hybrid Retrieval (Qdrant + BM25)` · `Reranking (RRF + cross-encoder)` · `OpenTelemetry Observability` · `Domain Adaptation`

**DevOps**

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Testcontainers](https://img.shields.io/badge/-Testcontainers-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### Featured Projects

#### [enterprise-ai-assistant](https://github.com/FurkanSay/enterprise-ai-assistant) · Multi-Tenant RAG Platform

Polyglot microservices showcase: **5 languages, 6 services**, gRPC-typed contracts in a single monorepo.

| Service | Stack | Role |
|---|---|---|
| Gateway · Identity | C# .NET 10 | Reverse proxy (YARP) · Auth · Tenant isolation |
| Documents | Java · Spring Boot 3 | Transactional file ops · Metadata |
| Processing | Rust · Axum | CPU-bound chunking · BM25 (tantivy) |
| AI Engine | Python · FastAPI | Embeddings · agent loop · tool registry · RAG |
| Realtime | TypeScript · NestJS | WebSocket fan-out |
| Frontend | Next.js | Chat UI · RAG citations · streaming |

> Multi-tenant SaaS · custom **agent loop + tool registry** (function calling, **no LangChain**) · Qdrant + BM25 **hybrid retrieval** with RRF & cross-encoder reranking · **RAGAS** evaluation · **OpenTelemetry + Jaeger** first-class · grounded RAG with citations.

---

#### [voice-notes-tr-ai](https://github.com/FurkanSay/voice-notes-tr-ai) · Offline Turkish Meeting Assistant

Solves the post-meeting "what did we decide, who does what" loss — **fully offline & GDPR/KVKK-compliant**, no data leaves the machine. Tauri v2 (**Rust** + TS) · Vite/React · faster-whisper (Whisper large-v3-turbo) transcription · Ollama / Gemma 3 for decision & action extraction · real-time capture with cpal + VAD.

---

#### [odoo-meet-assistant-rag-ai](https://github.com/FurkanSay/odoo-meet-assistant-rag-ai) · ERP-Integrated Meeting Assistant

Turns scattered meeting notes into tracked tasks **inside the ERP** and makes past meetings queryable in natural language. **4 custom Odoo 17 Python modules** · PostgreSQL + pgvector · Ollama (bge-m3, Gemma 3) RAG embedded into ERP workflows.

---

### Production Highlights

- 🏗️ Shipped **8 enterprise products from scratch** at ON Yazılım (Technopark) across healthcare, agritech & logistics — incl. on-device AI: trained a queen-bee detection model and deployed an **ONNX** model into tablet ground-control software.
- ⚡ **API p95 latency: 850 ms → 120 ms (−85%)** — profiling + async refactor.
- 🗄️ **Hot SQL queries: −60% runtime** — stored-procedure refactor + index tuning.
- 🔄 **Outbox Pattern + RabbitMQ** event-driven pipeline for cross-service eventual consistency.
- 🚢 Shipped **GoEksper SaaS** end-to-end as sole engineer (backend + UI, production).

---

### Education & Certifications

- 🎓 **M.Sc. Computer Engineering** · Mersin University · 2023–2026 · GPA 3.60 / 4.00
- 🎓 **B.Sc. Computer Engineering** · Adana ATÜ · 2018–2022
- 📜 Microsoft ASP.NET Core Developer Professional Certificate · Coursera, 2024

---

<div align="center">

<a href="https://github.com/FurkanSay">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=FurkanSay&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=default" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=FurkanSay&layout=compact&hide_border=true&langs_count=8&theme=default" />
</a>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Furkan%20Say-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/furkansay)
[![Email](https://img.shields.io/badge/Email-info@furkansay.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:info@furkansay.com)

</div>
