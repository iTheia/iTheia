# Marlon "Gio" Martínez

**Backend Engineer — Microservices & AI** · Bogotá, Colombia

I build backend systems meant to survive production: distributed services on AWS, event-driven architectures, and LLM features that solve a real problem rather than demo well.

Seven years in, currently running day-to-day delivery for a cross-functional team of five. Most of my work is in TypeScript and Python — NestJS and Node on one side, pandas and LightGBM on the other. I care a lot about documentation, because the systems I've seen fail were rarely the ones nobody understood the code of; they were the ones nobody understood the *intent* of.

---

## Selected work

**[Elvia](https://github.com/iTheia/elvia)** — *System design + NestJS PoC*
A WhatsApp service that reaches Latin American technical-school graduates on graduation day and matches them to jobs through a guided conversation. Event-driven and serverless, because graduation dates cluster into spikes and the system is idle the rest of the time. The repo carries a full technical specification: four conversation flows including opt-out and mid-conversation reset, plus every technology choice recorded with its trade-offs.

**[Loan Management Microservices](https://github.com/iTheia/loan-management-microservices)** — *Python, TypeScript, Docker*
A two-service system: an API gateway and a standalone internal auth service. Auth issues short-lived access tokens signed with RSA and distributes the public key so other services validate independently — with a fallback validation endpoint for services that can't hold the key. Domain-driven layering, a base repository abstracting common persistence, Alembic migrations with seed data, and a Postman collection.

**[FitMe API](https://github.com/fitmeorg/fitme-api)** — *NestJS, MongoDB, BullMQ*
Backend for a fitness platform where users build routines, track streaks, and share activity. I owned the architecture — module boundaries, data model, and queue design — and ran live design and review sessions with the implementing engineer rather than writing most of the code myself. Also designed the mobile UI.

**[server-template](https://github.com/iTheia/server-template)** — *TypeScript*
A backend starter I keep so new services don't begin with a week of boilerplate.

---

## Stack

**Languages** TypeScript · Python · JavaScript · SQL · Bash
**Backend** NestJS · Node.js · Express · REST · GraphQL · WebSockets
**Architecture** Microservices · Event-driven · API Gateway · DDD · TDD
**AI / ML** OpenAI API · LangChain · RAG · pgvector · LightGBM · pandas
**Data** PostgreSQL · MongoDB · DynamoDB · Redis · Elasticsearch / OpenSearch
**Cloud** AWS (ECS, Lambda, EC2, S3, IAM) · Docker · CI/CD · Jenkins
**Also** RabbitMQ · Apache Spark (PySpark) · Datadog

---

## Elsewhere

[LinkedIn](https://linkedin.com/in/marlon-giovanni) · martinez.ded@gmail.com

Spanish (native) · English (C1) · Portuguese (learning)
