# Walter Salazar

**Senior AI Engineer · Full-Stack Engineer** — LLM agents, RAG, evals · Node.js/TypeScript · Java/Spring · React · AWS

San Salvador, El Salvador (UTC-6) · 14+ years shipping production software · 6+ years fully remote with US, Canadian and European teams · English C1

[LinkedIn](https://www.linkedin.com/in/waltersalazarg1989) · [sivargo.com](https://sivargo.com/en) · [live demo](https://sivargo.com/en/demo) · [nutrichefpao.com](https://nutrichefpao.com) · walter_salazarg@hotmail.com

---

## What I do

I build AI products that have to work in production: agents that answer questions over real business data, hybrid search that does not hallucinate, and the evals, tracing and cost controls that keep them honest. Before LLMs I spent a decade on backends in Java/Spring, .NET and Node.js for SaaS, enterprise and airline systems, so I am as comfortable designing a data pipeline or an incident runbook as I am designing a prompt.

Currently:

- **Senior Software Engineer @ FullStack Labs** (since 2022) — embedded on US/Canadian product teams. Today on **SmartDealer**, an AI analytics SaaS for US auto dealerships: a production LangGraph agent with 50+ tools over dealership financial, sales, inventory and service data; voice input (Deepgram); eval harnesses and Langfuse datasets; a DealerTrack DMS integration (15 Lambdas, Step Functions, 38 dbt models); releases and incident response.
- **Founder & Lead Engineer @ SivarGO** (since 2024) — an AI-first travel marketplace app for El Salvador, built solo: React Native app, Express/TypeScript API with 600+ endpoints, 161 Prisma models, a double-entry ledger, electronic invoicing, and **OlivIA**, an AI concierge with function calling, pgvector hybrid search, Cohere rerank and LLM-as-judge QA.

## Case studies (architecture, decisions and numbers — no source)

| Project | What it is | Highlights |
|---|---|---|
| [SivarGO](https://github.com/wsalazar1989/sivargo-case-study) | AI-first travel marketplace (iOS/Android) for stays, experiences, food, events and services | Agentic concierge, hybrid search, bookings & refunds ledger, host wallet, electronic invoicing, group plans |
| [NutriChef Pao](https://github.com/wsalazar1989/nutrichef-case-study) | Booking & patient-records platform for a nutrition practice | Next.js 16 PWA, Google Calendar sync, card payments with webhooks, magic-link auth, blue/green deploys |

## How I work with LLMs

- **Agents, not chatbots.** Tool loops with typed contracts (zod), explicit budgets per request, and deterministic guardrails around the model.
- **Evals before features.** Golden datasets, persona test banks and LLM-as-judge in CI; Langfuse tracing on every call so regressions are visible, not anecdotal.
- **Retrieval that is boring on purpose.** pgvector embeddings + keyword search + Cohere rerank, with a vocabulary router so "pupusas" and "cabañas" land in the right category.
- **Cost and latency are features.** Spend guardrails, Redis session memory, SSE streaming, cached tool results.

## Stack

`TypeScript` `Node.js` `Java 17` `Spring Boot` `Python` `React` `React Native (Expo)` `Next.js` `PostgreSQL / pgvector` `Prisma` `Redis` `dbt` `AWS (Lambda, Step Functions, ECS Fargate, RDS, S3, EventBridge, SQS, Cognito, CloudWatch)` `AWS CDK` `Docker` `GitHub Actions` `LangGraph` `LangChain` `OpenAI` `Cohere` `Deepgram` `Langfuse`

## Elsewhere

- MBA, EUDE Business School (Madrid) · B.Sc. Computer Science, UCA (San Salvador)
- Former software instructor at UCA (software architecture, Java, cloud microservices)
- Open to remote senior AI / full-stack roles, full-time or contractor (USD)
