# Hi, I'm Miryam 👋

**AI Engineer · Agentic Systems & LLM Integration · Fullstack**

I build AI systems for production, not demos - where the model advises and plain code holds the authority, so autonomy limits are *provable rather than probable*.

📍 Israel  ·  📧 [miryamizadka@gmail.com](mailto:miryamizadka@gmail.com)  ·  💼 [LinkedIn](https://www.linkedin.com/in/miryam-zadka/)

---

## Featured Projects

### 🤖 [ApprovalFlow](https://github.com/miryamizadka/invoice-approval-workflow) - AI-governed invoice approval platform
9 event-driven microservices where a LangGraph agent recommends and a deterministic router decides.

- **Provable autonomy ceiling** - tests force the agent to approve at 100% confidence and inject adversarial prompts; the router still escalates to a human.
- **RAG over company policy** - a deterministic floor of always-included rules plus TF-IDF retrieval, so the agent sees and cites only the relevant clauses.
- **Payment saga** with compensation, idempotency and ETag concurrency - no double payments, no negative budgets.
- **One distributed trace** across the whole async journey (Dapr → Jaeger), verified by script.
- JWT RBAC · bulkhead & throttling · CI/CD to GHCR · 600+ tests

`Python` `FastAPI` `LangGraph` `Dapr` `Redis` `PostgreSQL` `Traefik` `Jaeger` `Docker` `GitHub Actions`

### 🧭 [Bug Triage Workflow](https://github.com/miryamizadka/bug-triage-workflow) - agentic triage pipeline
The same "model proposes, code decides" principle, on a second framework.

- An LLM classifies bug reports into a strict Pydantic schema; deterministic red-flag rules override it on security, data-loss and outage signals.
- Routing logic testable with no API key · LLM eval set · PII-free audit log · human-in-the-loop gates · CI on every push

`Microsoft Agent Framework` `Groq` `Pydantic` `Docker` `GitHub Actions`

---

## In production

🏥 **GPT-4 intake agent** - bpreven, 2025. A conversational agent in a live digital-health platform serving real patients: structured questionnaires and free-form conversation within clinical boundaries, persisted as structured Q&A for clinician review.

🔧 **Questionnaire flow engine** - bpreven, 2025. A React Flow editor with edit and simulation modes, backed by server-side topological-sort cycle detection.

📱 **Marketplace app** - SmartApp, current. Sole mobile developer in a cross-functional team: Flutter for iOS & Android, 10+ production features, race-condition-safe token refresh, full RTL/LTR localization.

> Production code lives in private company repos.

---

## More projects

- 🚗 **[Smart Car Wash Pro 2.0](https://github.com/miryamizadka/Smart-Car-Wash-backend)** - solo-built booking platform: Node.js/Express, real-time tracking with Socket.io, Haversine-based unit assignment, automated PDF invoices. [Frontend](https://github.com/miryamizadka/Smart-Car-Wash-frontend)
- 📚 **[Digital Library System](https://github.com/miryamizadka/digital-library-system)** - 7 GoF design patterns in one coherent C# domain, built on SOLID.
- 🎓 **[Grade Management System](https://github.com/miryamizadka/Grade-management-system)** - ASP.NET Core REST API with role-based access control and custom exception middleware.

---

## Tech

**AI:** LangGraph · Microsoft Agent Framework · OpenAI API / GPT-4 · RAG · structured output · evals · guardrails · human-in-the-loop

**Architecture:** Microservices · Event-driven · Dapr · Sagas & compensation · Idempotency · JWT/RBAC · distributed tracing · CI/CD

**Languages & frameworks:** Python · TypeScript · C# · Dart · SQL · FastAPI · ASP.NET Core · Node.js · React · Redux · Flutter

**Data & tools:** PostgreSQL · SQL Server · Redis · Docker · Git · GitHub Actions

---

## Background

- **Software Engineering Diploma** - MAHAT (Israeli Ministry of Labor) · GPA 96 · Final project 100/100
- **AI Engineering & Microservice Architecture** - ZioNet, 2026
- **KamaTech Excellence Program** - algorithms, ML, computer vision, deep learning

*Open to AI Engineer, Backend and Fullstack roles where AI meets real production systems.*
