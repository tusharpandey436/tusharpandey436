<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0f,30:0d1117,60:1a1a2e,100:16213e&height=220&section=header&text=TUSHAR%20PANDEY&fontSize=52&fontColor=00f7ff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20Backend%20Architect&descAlignY=58&descSize=18&descColor=7efff5" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2400&pause=800&color=00F7FF&center=true&vCenter=true&width=900&lines=🧠+Building+Production-Grade+AI+Systems;⚡+RAG+Pipelines+%7C+LLM+Integration+%7C+System+Design;🔗+FastAPI+%7C+Supabase+%7C+Gemini+%7C+Postgres;🚀+From+Zero+to+Deployed+—+End+to+End;📦+Scalable+APIs+%7C+Vector+Search+%7C+Hybrid+Retrieval" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-00ff88?style=for-the-badge&logo=statuspage&logoColor=black" />
  <img src="https://img.shields.io/badge/Focus-AI%20%2B%20Backend-00f7ff?style=for-the-badge&logo=openai&logoColor=black" />
  <img src="https://img.shields.io/badge/Level-Production%20Grade-ff6b6b?style=for-the-badge&logo=rocket&logoColor=white" />
</p>

---

<img align="right" width="360" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" />

## 🧠 Identity Stack

```yaml
┌──────────────────────────────────────────────┐
│  name       :  Tushar Pandey                 │
│  role       :  AI Engineer & Backend Arch    │
│  location   :  India 🇮🇳                      │
│  available  :  Freelance + Full-time         │
├──────────────────────────────────────────────┤
│  core       :  RAG Pipelines                 │
│               LLM Orchestration              │
│               Backend Architecture           │
│               System Design @ Scale          │
├──────────────────────────────────────────────┤
│  stack      :  Python · FastAPI · Supabase   │
│               Gemini · Postgres · Docker     │
│               LangChain · ChromaDB           │
├──────────────────────────────────────────────┤
│  philosophy :  "If it's not scalable,        │
│                it's not finished."           │
└──────────────────────────────────────────────┘
```

<br clear="right"/>

---

## 🚀 Featured Project — AI Teams Bot

> **Production RAG system deployed in a real enterprise environment.**

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212897777-3d5c2e1d-b4fc-45d5-a09e-22b01d6a0945.gif" width="680" />
</p>

### 🏗️ System Architecture

```mermaid
flowchart TD
    A([👤 User Query]) --> B[🤖 Teams Bot Interface]
    B --> C[⚡ FastAPI Gateway]
    C --> D{🧠 RAG Engine Core}

    D --> E[📄 Document Ingestion]
    D --> F[🔪 Smart Chunking]
    D --> G[🧬 Embedding Generator]

    E -->|PDF·DOCX·XLSX| F
    F --> G
    G --> H[(🗄️ Supabase Vector DB)]

    C --> I[🔍 Hybrid Retriever]
    H --> I
    I --> J[📊 Reranker · BM25 + Semantic]
    J --> K[💎 Gemini 1.5 Pro LLM]
    K --> L([✅ Response + Source Citations])

    style A fill:#00f7ff,color:#000,stroke:none
    style L fill:#00ff88,color:#000,stroke:none
    style D fill:#1a1a2e,color:#00f7ff,stroke:#00f7ff
    style K fill:#ff6b6b,color:#fff,stroke:none
    style H fill:#7c3aed,color:#fff,stroke:none
```

### ⚡ What Makes It Production-Ready

| Feature | Status | Detail |
|---|---|---|
| 🧠 Vague query handling | ✅ | Query expansion + intent parsing |
| 📄 Multi-format ingestion | ✅ | PDF, DOCX, XLSX, TXT, HTML |
| 🔗 Source citations | ✅ | Every answer traces back to docs |
| ⚡ Hybrid retrieval | ✅ | BM25 + Semantic + Reranker |
| 🛡️ Error resilience | ✅ | Fallback chains, graceful degradation |
| 🚀 Scalable infra | ✅ | Docker + async FastAPI + Supabase |
| 📊 Observability | ✅ | Logging, latency tracking, eval metrics |

```python
# Core RAG pipeline — simplified
async def query_pipeline(user_query: str) -> RAGResponse:
    expanded     = await query_expander.run(user_query)
    candidates   = await hybrid_retriever.fetch(expanded, top_k=20)
    reranked     = await reranker.score(candidates, query=user_query)
    context      = build_context(reranked[:5])
    answer       = await gemini.generate(context, user_query)
    return RAGResponse(answer=answer, sources=reranked[:5])
```

<p align="center">
  <a href="https://github.com/tusharpandey436/YOUR-REPO">
    <img src="https://img.shields.io/badge/📁 View Repository-0d1117?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" />
  </a>
  <a href="https://your-demo-link">
    <img src="https://img.shields.io/badge/🎥 Watch Demo-ff0000?style=for-the-badge&logo=youtube&logoColor=white" />
  </a>
</p>

---

## ⚔️ Tech Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,docker,redis,git,linux,vscode&theme=dark" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,react,nodejs,supabase,gcp,aws,nginx&theme=dark" />
</p>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/RAG-Advanced-8b5cf6?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/LLM-Gemini%201.5%20Pro-f59e0b?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Vector%20DB-Supabase%20pgvector-3ecf8e?style=for-the-badge&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Orchestration-LangChain-1c3c3c?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Hybrid%20Search-BM25%20%2B%20Semantic-00f7ff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Infra-Docker%20%2B%20Async-2496ed?style=for-the-badge&logo=docker&logoColor=white" />
</p>

---

## 📊 GitHub Intelligence

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tusharpandey436&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=00f7ff&icon_color=00f7ff&text_color=c9d1d9&ring_color=00f7ff" height="175" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tusharpandey436&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f7ff&text_color=c9d1d9&langs_count=8" height="175" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=tusharpandey436&theme=tokyonight&hide_border=true&background=0d1117&ring=00f7ff&fire=ff6b6b&currStreakLabel=00f7ff&sideLabels=c9d1d9&dates=7efff5" width="700" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=tusharpandey436&bg_color=0d1117&color=00f7ff&line=00f7ff&point=ff6b6b&area=true&hide_border=true" width="900" />
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tusharpandey436/tusharpandey436/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tusharpandey436/tusharpandey436/output/github-contribution-grid-snake.svg" />
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/tusharpandey436/tusharpandey436/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

## 🎯 Current Focus — 2025 Roadmap

```
╔══════════════════════════════════════════════════════════════════╗
║  Q1 2025   ██████████░░░░  75%   Hybrid RAG + Reranking         ║
║  Q2 2025   ████████░░░░░░  60%   Agentic Systems (Tool Use)     ║
║  Q3 2025   ████░░░░░░░░░░  30%   Multi-Modal RAG (Vision)       ║
║  Q4 2025   ██░░░░░░░░░░░░  15%   On-Device / Edge LLM Deploy    ║
╚══════════════════════════════════════════════════════════════════╝
```

- 🔬 **Experimenting with** — ColBERT, SPLADE, late interaction models
- 🏗️ **Building** — Modular RAG framework (plug-and-play retrievers)
- 📚 **Studying** — Mixture of Experts, speculative decoding
- 🚢 **Deploying** — Production eval pipelines (RAGAS + custom metrics)

---

## 🏆 Achievement Unlocked

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=tusharpandey436&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7" />
</p>

---

## 🌐 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR-LINK">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:tusharpandey436@gmail.com">
    <img src="https://img.shields.io/badge/Email-Drop%20a%20Mail-ea4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://your-portfolio.dev">
    <img src="https://img.shields.io/badge/Portfolio-Live-00f7ff?style=for-the-badge&logo=vercel&logoColor=black" />
  </a>
  <a href="https://twitter.com/YOUR-HANDLE">
    <img src="https://img.shields.io/badge/Twitter-Follow-1da1f2?style=for-the-badge&logo=twitter&logoColor=white" />
  </a>
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=tusharpandey436&color=00f7ff&style=for-the-badge&label=PROFILE+VIEWS" />
  <img src="https://img.shields.io/github/followers/tusharpandey436?style=for-the-badge&color=00ff88&labelColor=0d1117&label=FOLLOWERS" />
</p>

<p align="center">
  <i>"Production systems aren't built in tutorials. They're forged in debugging sessions at 2am."</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0a0a0f&height=140&section=footer&text=Built%20Like%20a%20Product.%20Not%20a%20Profile.&fontSize=18&fontColor=00f7ff&animation=twinkling&fontAlignY=65" />
</p>
