<h1 align="center">Hi, I'm Animesh 👋</h1>

<p align="center">
  <b>ML &amp; Backend Engineer @ Deccan AI</b><br/>
  I build systems that run themselves — and I run my own workflow on them too.
</p>

<p align="center">
  <i>two things I care about most: <b>context</b> (giving agents the right knowledge) and <b>loops</b> (systems that keep working without me babysitting them)</i>
</p>

---

## 👨‍💻 About me

Early engineer (**#26**) at Deccan AI — joined at 0→1, now 200+ people and Series A.
By day I build high-throughput AI backends; on the side I build small autonomous
agents that live on my own hardware and handle the boring parts of my life.

- ⚙️ backend & distributed systems · 🤖 agents · 🔁 self-running loops · 📊 observability
- 📍 Hyderabad, India · open to remote AI-infra / backend roles

## 🛠️ Stuff I've built

**Production @ Deccan AI**
- **Media Studio** — multi-modal generation backend, **2.5M+ jobs/day**, 20+ models across 5 modalities · Celery · Kafka · Redis · PostgreSQL · Prometheus + Langfuse
- **AI Interviewer** — real-time GPT-4o voice agent on LiveKit
- **Talent Intelligence** — 7-microservice resume pipeline · CDC orchestrator · BM25 + Qdrant hybrid search over **600K+ docs**

**On the side**
- **context-layer** — a living, self-managing context layer for repos (MCP-mediated `docs/`, rendered for humans, auto-updated)
- **apply-agent** — a CDP-driven form-filler that applies to jobs, with a human in the approval seat
- **[how-llms-work](https://github.com/Animeshkr9044/how-llms-work)** — ground-up notes: embeddings → attention → transformers → LLMs → MoE
- **[keka-automation](https://github.com/Animeshkr9044/keka-automation)** — auto clock-in/out via macOS `launchd` + Chrome automation

## 🧠 How I manage context

Agents are only as good as what they know. I keep context **in the repo, as markdown**,
readable by the agent and rendered for humans — and I'm building tooling
(`context-layer`) so it updates itself and never goes stale.

```mermaid
flowchart LR
    Code["codebase"] --> Docs["docs/ + AGENTS.md<br/>(markdown context)"]
    Docs --> MCP["MCP layer"]
    MCP --> Agent["coding agent"]
    MCP --> Log["activity log<br/>(what the agent read / fetched / wrote)"]
    Docs --> View["rendered view<br/>(mermaid / HTML for humans)"]
    Agent -->|writes updates back| Docs
```

The principle: **one source of truth, two audiences** — the agent reads it, a human
sees it rendered, and every interaction is captured.

## 🔁 How I set up my loops

My Mac stays on at home as a little always-on server. I control it from Telegram,
and it acts through my email and the browser — but **nothing ships without my 👍**.

```mermaid
flowchart LR
    Me["me (on my phone)"] -->|screenshot a job / person| TG["Telegram"]
    TG --> Agent["agent on my always-on Mac"]
    Agent --> Gmail["Gmail (reads the thread)"]
    Agent --> PW["Playwright (fills forms)"]
    Agent -->|draft + context| Approve{"my approval?"}
    Approve -->|👍| Send["send / submit"]
    Approve -->|edit| Agent
```

Human-in-the-loop by design: the agent does the paperwork, I make the call. That
line — *it drafts, I decide* — is the whole point.

## 🧰 Stack

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/-Celery-37814A?logo=celery&logoColor=white)
![Kafka](https://img.shields.io/badge/-Kafka-231F20?logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?logo=qdrant&logoColor=white)
![GCP](https://img.shields.io/badge/-GCP-4285F4?logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![LiveKit](https://img.shields.io/badge/-LiveKit-1FD5F9?logo=livekit&logoColor=black)
![LLMs / RAG](https://img.shields.io/badge/-LLMs%20%2F%20RAG-6E56CF)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?logo=prometheus&logoColor=white)

## 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iamanimesh)
[![Email](https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=white)](mailto:animesh.kr9044@gmail.com)

<br/>

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=Animeshkr9044&show_icons=true&hide_border=true&count_private=true" alt="stats" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs?username=Animeshkr9044&layout=compact&hide_border=true&langs_count=8" alt="top langs" />
</p>
