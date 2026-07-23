<h1 align="center">Hi, I'm Animesh 👋</h1>

<p align="center">
  <b>ML &amp; Backend Engineer @ Deccan AI</b><br/>
  I build systems that run themselves — and I run my own workflow on them too.
</p>

<p align="center">
  <i>two things I think about all day: <b>context</b> and <b>loops</b></i>
</p>

---

## 👨‍💻 About me

Early engineer (**#26**) at Deccan AI — joined at 0→1, now 200+ and Series A.
I work on high-throughput AI backends, agents, and observability. Off the clock I
build small autonomous agents that live on my own hardware and handle the boring
parts of my day.

📍 Hyderabad, India · open to remote AI-infra / backend roles

## 🧠 How I think about context

An agent is only as good as what it knows. Most teams dump knowledge in once —
a README, a wiki, a `CLAUDE.md` — and then let it rot while the code moves on.

I don't think context should be a document you maintain. It should be a document
that **maintains itself**: living where the work lives (the repo), written as
markdown so the agent can read it, rendered so a human can *see* it, and updated
as a side effect of the work actually happening. One source of truth, two
audiences, always current.

```mermaid
flowchart LR
    Code["the work<br/>(code + changes)"] --> Ctx["context<br/>(markdown, in the repo)"]
    Ctx --> Agent["agent reads it"]
    Ctx --> Human["human sees it rendered<br/>(mermaid / HTML)"]
    Agent -->|writes back as it works| Ctx
    Agent --> Log["every read / write / fetch<br/>is captured"]
```

Get context right and everything downstream — agents, teammates, future-you — gets
cheaper.

## 🔁 On being a loop engineer

I'd rather design the loop than do the task. Anything I do more than twice, I want
running on its own.

But automation without a human at the decision point is just faster mistakes. So
the loops I build follow one rule: **the loop does the work, I make the call.** It
drafts, it fetches, it fills things in — then it stops, shows me, and waits. My Mac
stays on at home; I steer it from my phone; nothing ships without my 👍.

```mermaid
flowchart LR
    Trigger["a trigger<br/>(a message, a push, a schedule)"] --> Loop["the loop<br/>(runs on its own)"]
    Loop --> Work["does the work<br/>(draft / fetch / fill)"]
    Work --> Gate{"my call?"}
    Gate -->|👍| Act["it acts"]
    Gate -->|nope| Loop
    Loop --> Obs["observable the whole way<br/>(I can see what it did)"]
```

Good loops are **autonomous, observable, and interruptible.** That's the kind of
engineer I am.

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
